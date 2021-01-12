# automate-a-daily-task
MLH Local Hack Day: Build 2021 Week-Long Challenge: Automate a Daily Task

## Task Statement
Think about the tasks you do on a daily basis. Is there anything in there you can automate? Social media posts? Sorting your inbox? Sending out the zoom invite for the family meeting? Pick one, automate it, and submit your hack on our Week-Long Devpost!

# Submission
## Attendance Bot

A command-line tool that scrapes live chat from youtube and messages you when a link is posted. With the entire country of India (and most of the world) being under lockdown due to Covid-19, universities have had to resort to online classes to complete whatever is left in the school year. My particular uni decided to settle on YT Live as the perfect platform for conducting these classes, and attendance is to be marked by filling in a Google form within 3 minutes of it being posted in the live chat. Under these trying circumstances, the semester exams are at risk of being cancelled, and as a result, attendance is more important than ever. We engineers live for attendance, but who has the time to attend five hours of classes a day when we've got much more important things to do? (Read: gaming and attending MLH Hackathons!) This tool, given a YouTube Live link, gets the source of the iframe in which the YT Live chat is hidden, then scrapes it and looks for a link. When a link is found, it uses a Discord webhook and Twilio for Python to notify pre-specified parties.
