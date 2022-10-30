# Buzz
[Buzz Website](https://buzzanticheat.com/)

## Anticheat Notes
- Buzz is no longer for sale, and was discontinued without warning by its developer's.

## How to detect
- Buzz transactions are same for every player, and start at -32767.
- Buzz transactions are sent every tick.
- Buzz will simulate velocity via lagbacks if it detects the player cancelling S12.
- Buzz desyncs the player if it detects the player messing with transactions in any way. Whether its delaying the response, editing uid, etc. The only packets you will still receive are keep alive, and the only packet the server will process from you is chat.
- Buzz desyncs the player on detected bad packets.
