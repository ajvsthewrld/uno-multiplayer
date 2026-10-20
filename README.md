# UNO Rooms

Online multiplayer UNO game for 2 to 8 players. Rooms use 5 character codes and invite links.

## Run

Requires Node.js 18 or later.

```bash
npm install
npm start
```

Open http://localhost:3000. For friends on other networks, deploy this project to a Node.js hosting service that supports WebSockets, such as Render or Railway. Configure the start command as `npm start`.

## Rules

7 cards each, 30 second turns, +2 stacks on +2 and +4 stacks on +4 only, wild +4 anytime, matching numbers across colours, multiple matching numbered cards with the first matching the pile and last setting the colour, optional play of a drawn card, and 10 second UNO catch window with a 2 card penalty. Expired turns draw 1 or accept the stack. Two player reverse acts as skip.

## Limitations

This is a playable starter project, not a production service. Rooms are stored in server memory and reset on restart. Disconnecting a player ends the current match. No account system, reconnect, anti abuse protection, or persistent leaderboards yet.
