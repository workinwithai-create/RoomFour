# RoomFour

Four-bar room desk for bedroom producers and AI-music finishers.

The loop is full. The hook or vocal has no pocket. Session players mute one chair for four bars so the next section hits with room — piano leaves, kit thins, bass holds, nylon yields, brass sits out — then the track can finish.

Live samples only — FluidR3 acoustic grand, upright bass, nylon guitar, trumpet, violin, and acoustic kit from the PreEight bank pinned to commit `d58301e4a494555f411a2afbc448b724136eee76`.

No oscillators. Audio never leaves the tab.

## Distinct from yesterday and the rest of the line

| Tool | Job |
| --- | --- |
| TagFour | Four-bar last-line tag after the money chorus |
| ModEight | Last-chorus key change |
| LiftTwo | Two bars of climb into the hook |
| PreEight | Eight bars before the hook |
| AfterHook | Eight bars after the hook |
| EndEight | Last eight bars of the record |
| LastHook | Last chorus is the money chorus |
| MuteEight | Eight-bar subtraction |
| TightFour | Four bars that lock the pocket |
| **RoomFour** | Four bars that open room by muting one chair so the next section can land |

Yesterday's ship was LiftTwo / TagFour family. RoomFour is the missing pocket of air inside the loop you already have.

## Form

1–8 full pocket · 9–12 room

## Play

- A · Full loop
- B · With room
- 8 · Room only

## Pricing recommendation

One-time **$19** on Gumroad. Mirror on Lemon Squeezy. Optional $9 add-on inside Forge Pass ($24/mo).

This is a finite desk, not a recurring studio. Do not subscribe it standalone. Sell next to the other live-chair desks with a pinned X demo and a ReleaseForge catalog card. Bedroom finishers already buy $9–$29 one-shots.

Best place to sell: Gumroad (producers buy one-time tools there) + Lemon Squeezy as merchant of record. Link from workinwithai.com beside the Forge line.

## Stack

Static HTML/CSS/JS. Deploy on Vercel team `release-forge`.

## Acceptance (section 9)

1. Export at 92 BPM, 8 bars, 48 kHz → exactly 1,001,739 samples; first transient within 1 ms of sample 0.
2. Import WAV at bar 1 of 92 BPM DAW, loop 4× — no clicks at seam, no drift.
3. Play, switch tab 30 s, return — stopped cleanly, no stacked notes.
4. Change recipe / BPM while playing — heard within one bar, no restart.
5. Block sample host, reload — UI names missing instruments.
6. Longest pad sustains to end of note.
7. Grep: no @main / @gh-pages, no Math.random in export path, voice names match samples.

## License

MIT. workinwithai-create. Free to use; README states one-time pricing for the commercial desk.
