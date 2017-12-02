Readme file for final project

Author=Kevin Roeske
github=https://github.com/kevinroeske/322final.git

Description:

Allows multiple users to register their names and calendars, and view common free times amongst comrades for the purpose of scheduling meetings
when everyone is free.

Known bugs:

1) I couldn't get time zone awareness to work, so I took it out. I know this was a major feature, but it is what it is. Without removing
the code for timezones, I would be submitting a non-working solution.

2) There are some issues with the automated email invitations, namely that there may be stray characters to remove from the generated email
addresses before the email will send properly. It came down to the wire and I didn't have time to write a pasring method to clean them up. The
user will need to pay attention to what they're doing.
