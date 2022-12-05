# Buzz
[Buzz Website](https://buzzanticheat.com/)

## Anticheat Notes
- Buzz is no longer for sale, and was discontinued without warning by its developer's.
- Buzz is rarely used now, however one notable server that still uses it is play.minelatino.com, a cracked spanish server which peaks at bout 1k players a day. They use Buzz 1.0.7

## How to detect
- Buzz transactions are same for every player, and start at -32767.
- Buzz transactions are sent every tick.
- Buzz will simulate velocity via lagbacks if it detects the player cancelling S12.
- Buzz desyncs the player if it detects the player messing with transactions in any way. Whether its delaying the response, editing uid, etc. The only packets you will still receive are keep alive, and the only packet the server will process from you is chat.
- Buzz desyncs the player on detected bad packets.

- Send silly message ``` jd9jyQaj=J7fzA:PN4H~*`s}AZP\39T<we<knAb~4gd+S=- ```
- ^ If buzz it will respond with buzz license, vers, server vers, and you'll get access to buzz alerts
