# Buzz
[Buzz Website]([https://www.spigotmc.org/resources/vulcan-anti-cheat-advanced-cheat-detection-1-7-1-19-2.83626/](https://buzzanticheat.com/)

## Anticheat Notes
- Buzz is no longer for sale, and was discontinued without warning by its developer's.

## How to detect
- Buzz transactions are same for every player, and start at -32767.
- Buzz transactions are sent every tick.
- Buzz will simulate velocity via lagbacks if it detects the player cancelling S12.
- Buzz desyncs the player if it detects the player messing with transactions in any way. Whether its delaying the response, editing uid, etc.
- Buzz desyncs the player on detected bad packets.
