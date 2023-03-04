# Loowps Bitwig Presets & Projects

Some of my Bitwig presets, clips and projects which might be worth sharing.

### 🔊 [Spotify] / [Apple Music] / [Bandcamp] / [Soundcloud]

## 📋 Presets

### [Note Range (Download)](https://github.com/loowps/bitwig-resources/raw/main/Bitwig-v4.2/Note%20Range.bwpreset)

A Note Grid preset which allows you to limit the input notes to a user defined range. The lower limit is set by Min
and the upper limit by Max. Notes which exceed the limits are fold back by an octave +/-. You can change the priority
of the calculation by toggling the Min->Max button.

### [Seeded Random Melody (Download)](https://github.com/loowps/bitwig-resources/raw/main/Bitwig-v4.2/Seeded%20Random%20Melody.bwpreset)

A Note Grid Preset which uses seeded pseudo random numbers to generate a melody with random pitch, velocity, step
length and step on/off. This preset is meant to illustrate a possible use case and probably could be improved further
and adapted to your needs.

### [Loowps Sequencer (Download)](https://github.com/loowps/bitwig-resources/raw/main/Bitwig-v4.2/Loowps%20Sequencer.bwpreset)

A mono sequencer with variable note length, probability, delay/shuffle, gate length, pitch, pitch lag, velocity and 16
midi CC values.

## 📋 Projects

### [Flex Sequencer (Download)](https://github.com/loowps/bitwig-resources/raw/main/Bitwig-v4.3/Flex%20Sequencer%20(CC%20to%20Notes)%20-%20Loowps.bwproject)

An example project which provides a 6x monophonic track sequencer that uses cc automation drawn in by pen as its note
source. Automation values > 0 cause a note on event, semitone changes re-trigger the current note with the new pitch and
values == 0 lead to note off events.

Turning quantization off and altering the pattern lengths of the different clips
can lead to experimental / free form rhythms hence the cringe name 'flex sequencer'. Further parameter automation
should be added to the target tracks. Sadly a bug which offsets the automation on load prevents storing the sequencer
setup group as bwscene.

My related bitwish: pen tool in piano roll should add a mode which allows drawing in notes that way - mouse down
causes a new note which last as long the mouse is pressed or the mouse y position is changed to a new semitone which
adds a new note and so on. Shift modifier key could then be used to switch between quantized / not quantized drawing.
Could be named monophonic brush tool.


[Spotify]: https://open.spotify.com/artist/2jOQrKX3rRoZORPfFcXaYU
[Apple Music]: https://music.apple.com/us/artist/loowps/1326334750
[Bandcamp]: https://loowps.bandcamp.com
[Soundcloud]: https://soundcloud.com/loowps
