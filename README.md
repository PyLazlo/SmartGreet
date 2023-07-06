# SmartGreet - project in progress
A python web app used for sending personalized greeting cards

Welcome to SmartGreet by Vatroslav Veble!

If you are like me, you like to send personalized greeting cards for holidays such as Christmas, Easter and New Year.
It is very tenacious to write a few  hundred emails with names and different cards as attachments for different groups 
of people (Dear John, Dear Jane, Dear Mr./Mrs. Doe, etc.) and even more time consuming.

There are some solutions out there but imo they are either too complex or paid.

I am creating this mini web app to solve my issue of sending greeting cards to over 500+ different email adresses.

The first version will have a database that you will need to fill out with your contacts and personalized messages, 
but in later versions I will add importing contacts from a .csv file with options to automatically add personalized
messages based on the name or surname of the contact (however this will require you to have all that information in
your contacts before exporting the .csv).

The database will have CRUD options so that you can change contact information and personalized greets if the need arises.

The App will have options to send cards to all contacts or contact groups.

I will also add a delayed sending option if you are using a gmail or some other free email account so that your email
doesn't get blacklisted for spam. If you are using your own server for sending email then you do not have to worry about this.
