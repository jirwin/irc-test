# irc-test
The goal of this project is to build a standard set of test cases that exercise the [node-irc](https://github.com/martynsmit/node-irc) library against a set of real IRC servers.

While there is an IRC specification, a lot of IRC servers implement their own features and in some cases violate the spec. While the original intention of node-irc was to implement the spec, it has evolved to support as many different ircds as possible.

Ideally this will be completely automated, but the primary objective is to make testing against live servers much easier.

## Test Flow
1. Connect to IRC server
2. Join channel
3. Send message to channel
4. Echo message from user sent to channel
5. Successfully part from channel
6. Disconnect from server

## Top Ten Networks
- IRCnet
- QuakeNet
- EFnet
- Rizon
- Undernet
- ChLame
- IRC-Hispano
- OFTC
- LinkBR
- ChatZona

### Other Networks of Note
- Freenode
- Snoonet