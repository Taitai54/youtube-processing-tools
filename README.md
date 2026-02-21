# YouTube Processing Tools

A curated collection of processed YouTube video content -- transcripts, summaries, extracted links, and course tracking data.

## Contents

### Transcripts
- Full text transcripts extracted from YouTube videos, stored as `.txt` files
- Organized by topic into `Categorized_Transcripts/` folders:
  - **Technology** -- AI tools, automation, no-code platforms
  - **Health** -- Health and wellness content
  - **Education** -- Learning resources and tutorials

### Link Extraction
- Structured CSV files with links extracted from YouTube video descriptions
- Columns: Video Title, Video URL, Description Links, Link Description

### PDF Summaries
- Archived PDF summaries of YouTube video content
- Primarily covering AI tools, SEO, no-code platforms, and productivity topics

### Course Tracking
- SkillLeap AI course curriculum tracking (URLs and durations)
- Midjourney course section tracking

## Structure

```
youtube-processing-tools/
  Categorized_Sections/        # Video transcripts (17 videos)
  Categorized_Transcripts/     # Transcripts sorted by topic
    Education/
    Health/
    Technology/
  2024-10-23_Get list/          # 45 PDF summaries of YouTube videos
  Useful links from youtube/   # AI agent summaries and meeting notes
  *.csv                         # Extracted links and course tracking
  *.xlsx                        # Curated video lists
```

## Note

This is a data/output repository. The processing tools used to generate these outputs (transcript extraction, link scraping, categorization) were run locally and are not included in this repo.
