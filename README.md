# MIDITicksToMillisec
I made this C++ script with the help of one of my batchmates since I kept forgetting the "formula" of converting MIDI ticks to milliseconds whenever I needed to trim down long blanks at the end of my MIDI files on MIDIEditor.
This will open up a console that lets you manually enter either
- The resolution of your file, (PPQN, you can easily check that value using Falcosoft MIDI player)
- Tempo (make sure to keep a backup copy of your MIDI if it contains tempo changes. Choosing the lowest tempo value might be okay but it will probably leave some blank behind)
- The off tick of the last event, be it the final control change event, or most probably the final note-off event.
or
- Track time MM:SS
