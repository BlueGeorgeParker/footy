# Footy Simulator

Top-down Aussie rules in the browser, 24 a side. Play the computer, or send a friend a link and play each other online.

**Play:** https://bluegeorgeparker.github.io/footy/

## Playing a friend

1. Open the game and press **Play a friend online**.
2. Send your friend the link it shows. They open it and press **Join match**.
3. You're Home (blue, kicking right); they're Away (red, kicking left). The computer plays everyone else.

The match runs in the host's browser, so the host keeps their tab open and in front. The two browsers connect directly (via [PeerJS](https://peerjs.com)); there's no game server.

## Controls

| Key | What it does |
| --- | --- |
| WASD | Run |
| Left-click, pull back, let go | Kick. Further pull, longer kick, wider landing area |
| Right-click, pull back, let go | Handball |
| Click a teammate | Take them over when you don't have the ball |
| Q | Take over the teammate closest to where the ball is coming down |
| Space | Tap: jump the way you're running (can't be tackled mid-jump), or jump for a mark when the ball's dropping near you. Hold: wind up a diving tackle, let go to dive |
| Shift | Hold for a speed boost; run into an opponent without the ball to knock them out of the way |
| 1-5 | Power-ups (5 is the ground slam) |
| Wheel | Zoom |
| P | Pause |

Everything is in `index.html`. Save that one file to play the computer offline.
