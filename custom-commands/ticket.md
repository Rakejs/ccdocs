---
description: ticket functions to create and delete Ticket
---

# Ticket Functions

### $isTicket\[channelid\] or $isTicket

returns true/false .true if the channel is a Ticket.

#### $newTicket\[name;message\(optional\);catergoryid\(optional\);return id yes/no;error message\(optional\)\]

creates a new Ticket with name.Will send the message in the channel if provided and throw the error if a error happened.

### $closeTicket\[error message\(optional\)\]

closes the Ticket .If the Channel is not a ticket it will throw a error

