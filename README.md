# Spoken transcripts: Context7 indexing test

Test dataset for an experiment: does Context7 index and serve spoken content (YouTube video
transcripts) well out of the box?

- `transcripts/vigorous-steve/`: 25 videos from the Vigorous Steve YouTube channel (mostly livestream Q&A).
- `transcripts/alex-hormozi/`: 25 videos from the Alex Hormozi YouTube channel.

Each file is one video: title, YouTube URL and publish date, then YouTube's caption track as one
line per caption segment, `[hh:mm:ss] text` (the standard timed-transcript export). Captions are
YouTube's (mostly automatic), unedited: no chapters, no speaker labels.
