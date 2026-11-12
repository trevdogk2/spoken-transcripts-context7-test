# Spoken transcripts: Context7 indexing test (format B)

Test dataset for a Context7 indexing experiment: 50 YouTube videos, 25 from Vigorous Steve (mostly livestream Q&A) and 25 from Alex Hormozi.

Each file in `transcripts/<channel>/` is one video:

- YAML frontmatter: title, channel, publish date, URL.
- `##` headings: the uploader's own chapter titles from YouTube, where the video has them.
- The text is YouTube's auto-generated captions, grouped into 1-3 minute paragraphs. Each paragraph starts with a clickable `[mm:ss]` link to that moment in the video.
- `Viewer question (read aloud):` lines are live-chat questions, in the viewer's own words, placed at the moment the host read them out. They are matched from the archived live chat.

The captions are automatic, so they contain recognition errors. There are no speaker labels and no summaries.

Variant C adds a "### Viewer question at [mm:ss](link): ..." heading above each read-aloud question.
