# Scale Map

VST3 plugin (Windows) that shows scales and positions on a guitar fretboard inside the DAW.

- 16 scales, 12 keys, 7 tunings (incl. 7-string and 4-string bass)
- Positions: 3 notes per string or CAGED
- Labels: note names, intervals or dots
- Click a note to hear it; "Tocar posição" plays the pattern up and down (own BPM or the DAW's)
- Audio input is passed through untouched

Built with [AudioPlugSharp](https://github.com/mikeoliphant/AudioPlugSharp).

## Install
1. Download the `ScaleMapVST3Plugin` artifact from the latest successful build (Actions tab).
2. Extract it into `C:\Program Files\Common Files\VST3\ScaleMap`.
3. Rescan plugins in the DAW. Requires the .NET 10 Desktop Runtime.
