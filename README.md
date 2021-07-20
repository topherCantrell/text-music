# text-music
Text music representation

  - Octave
  - Volume
  - Duration
  - Note
  - Accidentals
  - Attributes

  ```
  o2v3:4.G#_A_o+v+Bb
  ```

  `tones = parse(base_octave=2,base_volume=3,".......")`

  Tones is a list of entries: [midiNote,duration]

  `freq = get_frequency(midiNote)`

  Split on whitespace