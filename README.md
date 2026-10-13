# Paper Music Box

A paper-strip music box on a lamplit desk, in one HTML file. Punch holes in the paper, then turn the crank or wind the spring and listen.

**Play it:** https://speakingtrumpetskier-prog.github.io/paper-music-box/

Open `index.html` in a browser. It needs no build step and no server; the only outside request is the Google Fonts stylesheet.

## How to play

- Click the paper to punch a hole. Click a hole to tape it over.
- Grab the crank and move in circles of any size. Clockwise plays forward.
- Hold the brass key (or the W key) to wind the spring, then let go. The tune slows as the spring runs down.
- Touch the fan (or press Space) to stop it.
- Drag the paper or the bar along the bottom to move through the strip. Ctrl+Z undoes.

## Songs and scenes

Each song has a scene that comes up slowly behind the box once the music has been playing for a while, and fades as the spring runs down.

| Song | Scene |
| --- | --- |
| Twinkle, Twinkle | A lake at night; the melody draws a constellation |
| Ode to Joy | A city on a river; each melody note bursts as a firework on the beat |
| Frère Jacques (a three-voice round) | A village at dawn; three bells in the tower, one per voice |
| Nearer, My God, to Thee | Paper lanterns rising off a night sea |
| Blank strip | Northern lights that follow the notes you punch |

"Nearer, My God, to Thee" is Lowell Mason's tune Bethany (1856), transcribed from the [Hymnary.org score](https://hymnary.org/tune/bethany_mason) and moved to C. All songs are in the public domain.

The comb has 15 notes, C4 to C6 on the white keys, like the common 15-note paper-strip kits. The sound is synthesized in the browser with the Web Audio API.
