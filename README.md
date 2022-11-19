# dayz-server-fake-players
Memory opcode that allows you to spoof/fake the player count of a Dayz server binary which is reported back via steam A2S.

This allows you to inject a set number of "ghost" players which show up in the server browser. The value is dynamic so if a real player joins it will increase. i.e 20 fake players + 1 real player = 21 reported players on the server.

You can code inject these opcodes at the stated address. 

The op code requires a hexidemical value which represents the total amount of players you wish to inject. 
https://www.rapidtables.com/convert/number/decimal-to-hex.html
