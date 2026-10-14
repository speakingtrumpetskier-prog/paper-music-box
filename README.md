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
- **How it plays** opens a view inside the box: the paper slides toward you under a row of fifteen star wheels, and where a hole passes under a wheel, the wheel drops in, the paper rolls it a quarter turn, and its upper point flicks the comb tooth above it. Every wheel and tooth moves with the real strip, and the panel names the notes sounding.

## Songs and scenes

Each song has a scene that comes up slowly behind the box once the music has been playing for a while, and fades as the spring runs down.

| Song | Scene |
| --- | --- |
| Nearer, My God, to Thee | Paper lanterns rising off a night sea |
| Drunken Sailor | On deck at night under a swinging lantern; the chords throw spray over the rail |
| Canon in D | A baroque garden at dusk; three swans follow one course, as the three violins do, and eight fountain jets follow the bass |
| Twinkle, Twinkle | A lake at night; the melody draws a constellation |
| Ode to Joy | A city on a river; each melody note bursts as a firework on the beat |
| Frère Jacques (a three-voice round) | A village at dawn; three bells in the tower, one per voice |
| Gymnopédie No. 1 | Looking out through a rainy window at a Paris apartment building across the street; the melody sends drops running down the glass |
| Dies Irae | A cathedral nave; every chant note lights a candle |
| Blank strip | Northern lights that follow the notes you punch |

## Sources

All songs are in the public domain. Arrangements are moved onto the comb's white keys where needed.

- **Nearer, My God, to Thee:** Lowell Mason's tune Bethany (1856), from the [Hymnary.org score](https://hymnary.org/tune/bethany_mason), moved from F to C.
- **Gymnopédie No. 1:** Erik Satie (1888), from the [Mutopia Project edition](https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=37). Written on the C rows and played on a comb tuned up a whole step, so it sounds in Satie's D. The strip loops the first section; the middle section needs a note the comb does not have in that key.
- **Dies Irae:** the 13th-century chant, first verse, from the score in [Wikipedia's article](https://en.wikipedia.org/wiki/Dies_irae). It is in D Dorian, on the white keys. The second time through, a second voice sings a fourth below, as in early organum.
- **Drunken Sailor:** traditional shanty in D Dorian, from the score on [German Wikibooks](https://de.wikibooks.org/wiki/Liederbuch/_What_shall_we_do_with_the_drunken_sailor).
- **Canon in D:** Pachelbel, from the [Mutopia Project edition](https://www.mutopiaproject.org/cgibin/piece-info.cgi?id=2047) of the original parts for three violins and bass. The bass plays its ground alone, then the violins enter two bars apart through the first sixteen bars of their line. Played on a comb tuned up a whole step, so it sounds in D.

The comb has 15 notes, C4 to C6 on the white keys, like the common 15-note paper-strip kits; a few songs tune it up a whole step, as a box built for that key would be. The view inside the box follows the star-wheel design those kits use. The sound is synthesized in the browser with the Web Audio API.
