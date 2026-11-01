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
| Signature S | Big Dipper · Texas Special · 635JM · Masterdesign '62 | 5-way |
| Sky S-Style | 635JM · Big Dipper · Texas Special · Masterdesign '62 | 5-way |
| Black No. 1 S | Big Dipper · Texas Special · 635JM · Masterdesign '62 | 5-way |
| Monterey S | Monterey stock · Big Dipper · Texas Special · 635JM | 5-way |
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

## Presets

| Preset | Guitar | Amp | In short |
|---|---|---|---|
| Gravity Butter Lead | Black No. 1 S, neck | Rock Two | the smooth, singing lead: two light overdrives, tape echo |
| Slow Dancing Room | Black No. 1 S, pos. 2 | Rock Two | warm clean with a touch of drive |
| Heart of Life Clean | Black No. 1 S, pos. 2 | Rock Two | soft, compressed fingerpicking clean |
| Edge of Desire Ambient | Black No. 1 S, neck | Rock Two | long echoes and reverb |
| Waiting World Clean | Signature S, pos. 4 | Rock Two | funky in-between clean |
| Belief Groove | Signature S, pos. 2 | Rock Two | rhythm clean with slapback |
| Vultures Quack | Signature S, pos. 4 | Rock Two | quacky, boosted rhythm |
| Covered Rain Blues | Black No. 1 S, neck | Blackface Super | slow blues, pushed hard |
| Bold Love Monterey | Monterey S, neck | Blackface Super | vibe + drive, 60s style |
| Wild Blue Sky | Sky S-Style, pos. 4 | Modern 100 | clean, glassy, 80s-tinged |
| Last Train Chorus | Sky S-Style, pos. 2 | Modern 100 | chorus and echo |
| Shouldn't Matter Lead | Sky S-Style, neck | Modern 100 | overdrive-channel lead |
| Crossroads Shuffle 335 | Cherry '64 Semi, bridge | Modern 100 | humbucker shuffle |
| No Such Thing Junior | Signature S, pos. 4 | Junior 15 | early-years small-combo clean |
| Why Georgia Junior | Signature S, pos. 2 | Junior 15 | compressed small-combo clean |

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
