# Social Mail Server

The social mail server is an SMTP and IMAP mail server that aims to reimagine e-mail.

It still uses a TXT DNS record but in order to send an e-mail to any address you must first send a friend request to the address and have the other person accept the friend request. This friend request also includes a PGP key for the user, so all messages sent to your mail server are always encrypted. Friend requests can also be flooded, and there should be some methods to prevent friend requests from flooding an inbox like rate limiting, or global registry which blacklists certain e-mail addresses or domains that do not behave themselves.

Further there are types of mailboxes for certain requests. Like there is a mailbox for advertiser requests. And there are friends and work friends. There is also a category for website messages like passwords, and messages from webistes. And also mailboxes for social messages, both short form like twitter and longer form like blog posts. There is also link sharing capability built into the server.



