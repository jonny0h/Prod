# Prod

https://www.reddit.com/r/AskProgramming/comments/awdlfj/need_help_to_create_a_simple_ping_checkin_signal/

Hello, and I would greatly appreciate some help on developing an application that allows a student to ping an instructor to come over to the cubicle.

Context: I work in an dentistry clinic, as a clinic technology officer. We have over 100 Windows 10 workstations in the clinic, that are all on the school's AD network. I have been tasked with creating a solution (whether it be using software that is already available, or writing my own) for a student to ping from their workstation to an aisle supervisor's computer, to notify an instructor to come over to the student's cubicle. Students are not allowed to leave their cubicle while in gown with a patient, and must signal an instructor to come over. One instructor will usually supervises =<10 students.

Any advice would be welcomed. Does something like this already exist?

For administrative issues, I want to write a web app (with a short url) where a student would go to the website, select their instructor and ping them to come over. This would alleviate installing a small app on every workstation, but I could deploy through AD to keep it all internal.

Visually (high level) I was thinking, once you start the app (sign into website) you type in your name, you select your instructor, then there is a grey box that when clicked, turns green, signalling to an instructor's computer to come over. The instructor's computer will be able see the time stamp it was sent, and which student.

It would be amazing if I could tie the sessions in and operator name from a SQL DB pull through the Dental Software we currently use automatically, but this is a 'nice to have feature'. Having an instructor create their pod or 'room' then having student's select it would be good. This notification I set up, could just be like flipping an token where a a list of student name will change color with a timestamp when it flipped.

The emphasis is to have a very simple design.

I do not know what language to code in, if it should be a web app or local install setup.

Please any direction would be amazing.

Would love any feedback, and greatly appreciate it.

Thanks!
