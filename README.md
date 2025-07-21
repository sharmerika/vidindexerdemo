# Azure AI Video Indexer demo


This is a hands-on exploration of **Azure AI Video Indexer**—no code required. Using the portal, I analyzed a short gameplay clip from *Hogwarts Legacy* and observed how AI interprets motion, faces, sentiment, and scenes.

## What It Does

- Uploaded video to Azure Video Indexer Portal
- Generated transcript, scene segmentation, and sentiment mapping
- Detected quirky objects like “motorcycle” and “backpack”... in Hogwarts 
- Exported insights in `.vtt`, `.json`, thumbnails, and a full ZIP bundle

## Repo Contents

| Folder       | Description                                      |
|--------------|--------------------------------------------------|
| `video/`     | The source clip used for analysis                |
| `insights/`  | Transcripts and JSON metadata from Video Indexer |
| `thumbnails/`| Sample snapshots of detected scenes              |
| `zip/`       | Full artifact ZIP file with all outputs          |


# Azure Video Indexer Tags Summary
# Source: analysis.json

Keyword: "magic" — Confidence: 0.98
Keyword: "outdoor" — Confidence: 0.91
Keyword: "castle" — Confidence: 0.87
Keyword: "motorcycle" — Confidence: 0.67
Keyword: "backpack" — Confidence: 0.73
Keyword: "person" — Confidence: 0.95

## Source Video Access

The gameplay clip from *Hogwarts Legacy* used in this analysis is not publicly hosted due to privacy considerations.

> If you're interested in viewing the original indexed video, feel free to reach out directly—I’d be happy to share the link upon request!

# Notes:
- AI models sometimes mislabel complex or fantastical scenes.
- "motorcycle" and "backpack" were detected in a Hogwarts Legacy clip

##  Reflections
This no-code demo helped me understand how machine learning models behave in cinematic, creative contexts. It’s a reminder that AI can be powerful, fascinating, and sometimes delightfully imperfect.

> This demo didn’t require writing scripts, because it didn’t need to.  
> Azure Video Indexer made the experience intuitive, visual, and fun to explore.  
> (API integration is something I might try next!)



**License**: MIT  
**Created by**: [Sharmaine Erika](https://www.linkedin.com/in/sharmaine-erika-boling-delgado/)
