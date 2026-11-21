# cowork-gmail-api

A private, personal-use Gmail integration. It runs locally on the owner's own computer and connects a handful of the owner's own Google accounts to a local automation assistant so that email can be searched, read, labelled and filed from one place.

## What it does

- Searches and reads mail in the owner's own Gmail accounts using the Gmail API.
- Applies and removes labels, archives messages and moves them between folders in those same accounts.
- Runs entirely on the owner's own machine. There is no hosted service, no public endpoint and no other users.

## What it does not do

- It does not send email on its own. Any outbound message is drafted for the owner to review and send manually.
- It does not share, sell or transmit mailbox contents to any third party.
- It is not offered to the public and has no sign-up.

## Scope requested

`https://www.googleapis.com/auth/gmail.modify`, which allows reading, labelling and moving messages. This is the minimum scope that supports filing mail into labels.

## Documents

- [Privacy policy](PRIVACY.md)
- [Terms of service](TERMS.md)

## Contact

tim@parsons.space
