# ContinuumTUBE — Manual

## The window

| Area | What it does |
|---|---|
| **Library** (left) | Every guitar, amp, cabinet and pedal. Drag an item onto the rig, or double-click it. |
| **Pedalboard** (top) | Six slots before the amp. Drag a pedal onto another to swap them; the **x** removes it; the footswitch turns it on and off. |
| **Guitar** | Model, pickup set and selector position. **Your guitar** tells ContinuumTUBE which pickups you are really playing (single coil, humbucker, P90). Click the picture for the large view. |
| **Amp** | Gain, bass, middle, treble, master, presence. Changing amp also loads that amp's own cabinet. |
| **Cabinet** | Choose another cabinet, or **Off** if you use your own impulse responses after the plugin. |
| **FX loop** (bottom) | Four slots after the cabinet, for delays, reverbs and modulation. |
| **Stack Looper** | Four-track looper at the very end of the chain: it records everything you hear. See [Stack Looper](#stack-looper). |
| **Output** | Final volume. Keep the **OUT** meter out of the red. |
| **Preset / Save preset** | Factory presets and your own. Saved presets go to `Documents\ContinuumTUBE Presets`. |

The window can be resized or maximised: everything scales.

## Getting a good sound

1. Set your interface's instrument input so the **IN** meter peaks in the green/yellow, never red.
2. Set **Your guitar** to the pickups of the guitar you are playing.
3. Load a preset, then change the guitar model and the amp: that's where the character lives.
4. Add pedals before the amp for drive; time effects (delay, reverb, tremolo) usually sound best in the FX loop.

## Guitars

| Model | Pickup sets | Selector |
|---|---|---|
| Signature S | Glass Scoop · Hot Fifties · Round Vintage · Early '60s | 5-way |
| Sky S-Style | Round Vintage · Glass Scoop · Hot Fifties · Early '60s | 5-way |
| Black No. 1 S | Glass Scoop · Hot Fifties · Round Vintage · Early '60s | 5-way |
| Monterey S | Monterey stock · Glass Scoop · Hot Fifties · Round Vintage | 5-way |
| Cherry '64 Semi | Vintage humbuckers | 3-way |

## Amps

| Amp | Cabinet | Character |
|---|---|---|
| Rock Two | Rock 2x12 | Very clean and chimey, deep bass, forward mids. Warms up only at high gain. |
| Modern 100 | Modern 2x12 | Overdrive channel: vocal mids, smooth top, compressed sustain. |
| Junior 15 | Junior 1x12 | Small EL84-style combo: breaks up early, nasal mids, light bass. |
| Blackface Super | Blackface 4x10 | Scooped mids, sparkling highs, big headroom. |

## Pedals & effects

| Pedal | Type | Knobs |
|---|---|---|
| Green Screamer | mid-hump overdrive | Drive · Tone · Level |
| Centaur Drive | transparent overdrive | Gain · Treble · Output |
| Crown Drive | dynamic overdrive | Drive · Tone · Volume |
| Twin Drive | overdrive | Drive · Tone · Volume |
| Breaker Drive | amp-like overdrive | Gain · Tone · Volume |
| Rhino Drive | overdrive | Drive · Tone · Level |
| Blues Drive K | overdrive | Gain · Tone · Level |
| Blue Boost | clean boost | Boost · Tone · Level |
| Pickle Fuzz | fuzz | Sustain · Filter · Loudness |
| Studio Comp | compressor | Sustain · Attack · Level |
| XW Wah | wah | Pedal · Q · Level |
| Envelope Q | envelope filter | Sens · Peak · Mix |
| Sub Octave | octave down | Sub · Direct · Tone |
| Rotary Vibe | vibe | Speed · Depth · Mix |
| Script Phaser | phaser | Speed · Color · Mix |
| Vintage Chorus | chorus | Rate · Depth · Mix |
| Opto Tremolo | tremolo | Speed · Depth · Shape |
| Aqua Delay | analog delay | Delay · Feedback · Blend |
| Tape Echo | tape delay | Time · Repeats · Mix |
| Spring Reverb | spring reverb | Decay · Tone · Mix |
| Stone Verb | studio reverb | Decay · Tone · Mix |
| Hall Reverb | large hall with pre-delay | Decay · Tone · Mix |

## Presets

| Preset | Guitar | Amp | Drive | In short |
|---|---|---|---|---|
| Gravity Butter Lead | Black No. 1 S, neck | Rock Two | crunch | the smooth, singing lead: a transparent drive into a light mid-hump drive, tape echo |
| Slow Dancing Room | Black No. 1 S, pos. 2 | Rock Two | edge of breakup | clean that only breaks up when you dig in |
| Heart of Life Clean | Black No. 1 S, pos. 2 | Rock Two | clean | soft, compressed fingerpicking clean |
| Edge of Desire Ambient | Black No. 1 S, neck | Rock Two | clean | long echo into the Hall Reverb |
| Waiting World Clean | Signature S, pos. 4 | Blackface Super | clean | bright, funky in-between clean |
| Belief Groove | Signature S, pos. 2 | Rock Two | edge of breakup | rhythm with a touch of drive and slapback |
| Vultures Quack | Signature S, pos. 4 | Junior 15 | edge of breakup | quacky trio rhythm: a small combo nudged by a boost |
| Covered Rain Blues | Black No. 1 S, neck | Blackface Super | lead | slow blues: mid-hump drive into a cranked amp |
| Bold Love Monterey | Monterey S, neck | Blackface Super | crunch | vibe + amp-like drive, 60s style |
| Wild Blue Sky | Sky S-Style, pos. 4 | Modern 100 | clean | clean, glassy, 80s-tinged |
| Last Train Chorus | Sky S-Style, pos. 2 | Modern 100 | crunch | warm chorus and echo |
| Shouldn't Matter Lead | Sky S-Style, neck | Modern 100 | crunch | soft lead with a dynamic overdrive |
| Crossroads Shuffle 335 | Cherry '64 Semi, bridge | Modern 100 | lead | humbucker shuffle on the amp's own drive, no pedals |
| No Such Thing Junior | Signature S, pos. 4 | Junior 15 | clean | early-years small-combo clean |
| Why Georgia Junior | Signature S, pos. 2 | Junior 15 | clean | compressed small-combo clean |

Presets are level-matched: switching between a clean and a lead preset keeps a similar volume.
Loading a preset doesn't touch the looper.

## Stack Looper

The looper sits after the FX loop and the output volume, so it records exactly what you hear:
every pedal, the amp and the cabinet.

| Control | What it does |
|---|---|
| **REC / PLAY** footswitch | First press arms the first loop: with **AUTO** up, recording starts on your first note. Second press closes the loop, which plays at once. Each further press records a new layer on the next free track; a layer closes by itself after one loop. |
| **1 – 4** track pads | Click: mute / unmute that track (or record on it, if empty). Hold: clear that track. Ring colour: amber armed, red recording, green playing. |
| **STOP** | Stops all loops; press again to restart from the top. |
| **CLEAR** | Erases every track. |
| **LOOP** | Volume of the loops against your live playing. |
| **TONE** | Left darkens the loops, right thins them out, so they sit behind your playing. |
| **AUTO** | How easily your first note starts the recording. All the way left: recording starts as soon as you press. |

Loops keep playing when you change preset: loop a clean rhythm, switch to a lead preset and play
over it. Each track holds up to 60 seconds (30 seconds above 50 kHz).

## Standalone audio settings

**Options → Audio/MIDI Settings**: choose the device type, then your interface's input and output.

- **Windows Audio (Low Latency Mode)** gives the lowest latency in the standalone app.
- If you hear your guitar twice (dry + processed), your interface's direct monitoring is on.
- A yellow bar saying *"Audio input is muted"* appears on first launch to prevent feedback: click
  **Settings…** and untick *Mute audio input* once you are using headphones or speakers safely.

## Troubleshooting

| Problem | Fix |
|---|---|
| No sound in the standalone app | Check input/output in Audio/MIDI Settings and that the input isn't muted. |
| The plugin doesn't appear in the DAW | Make sure the whole `ContinuumTUBE.vst3` folder is in `C:\Program Files\Common Files\VST3`, then rescan. |
| Crackles | Raise the buffer size. |
| Too much distortion | Lower the interface's input gain or the amp's Gain. |
