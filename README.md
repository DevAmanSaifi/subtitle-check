# Subtitle Check

Subtitle Check helps video editors review SRT subtitles for timing and readability before export. It runs locally in a browser and works with Hinglish, Hindi in Devanagari, and other scripts.

## Run it

1. Open **index.html** in a modern browser.
2. Open an SRT file or paste its contents. Select **Try a sample** to see the checker in action.
3. Select **Check subtitles**. Use the cue block numbers in the report to find the flagged cues in your editor.

## Checks

- Missing cue numbers and missing or invalid timestamp lines
- Empty captions and timestamps pasted inside captions
- Overlapping cues, out-of-order starts, and invalid durations
- Reading speed and line length, with adjustable defaults of 20 characters per second and 42 characters per line

Reading speed and line length use visible character clusters when supported by the browser. The checker treats the limits as editing defaults. It accepts UTF-8 and UTF-16 files with a byte-order mark. Subtitle files stay on your device. Review and make edits in your subtitle editor.

## Contributing

For a bug report, include the smallest sample that reproduces the issue, the browser you used, and what you expected to see. Use synthetic or cleared subtitle text for public examples.

## License

MIT. See [LICENSE](LICENSE).
