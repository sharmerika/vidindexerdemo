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

## Scene Preview  
![Magic Moment](thumbnails/HogLeg.jpg)
##  Reflections

This no-code demo helped me understand how machine learning models behave in cinematic, creative contexts. It’s a reminder that AI can be powerful, fascinating—and sometimes delightfully imperfect.

> This demo didn’t require writing scripts, because it didn’t need to.  
> Azure Video Indexer made the experience intuitive, visual, and fun to explore.  
> (API integration is something I might try next!)



**License**: MIT  
**Created by**: [Sharmaine Erika](https://www.linkedin.com/in/sharmaine-erika-boling-delgado/)
