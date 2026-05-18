🔍 Multimodal AI Content Detector
A web application that detects whether content is AI-generated. Currently supports text analysis, with image and video detection in development.

Status: In Progress


Why I Built This
AI-generated content is increasingly difficult to distinguish from human-created work. Most existing tools only handle one input type. This project aims to build a unified pipeline that handles text, images, and video under one interface — and makes the detection reasoning transparent to the user.

Current Features

📝 Text detection — rule-based engine that analyzes textual patterns (perplexity, burstiness, sentence structure) to determine whether a message is AI-generated or human-written


Planned Features

🖼️ Image detection — identify AI-generated or manipulated images using a pretrained model
🎥 Video detection — frame-by-frame analysis aggregated into a single confidence verdict
📊 Confidence scoring — results returned as a percentage with a plain-language explanation


Tech Stack
LayerTechnologyText DetectionC++(Planned) BackendPython, FastAPI(Planned) Image DetectionHuggingFace pretrained model(Planned) Video ProcessingOpenCV(Planned) FrontendReact

Roadmap

 Text detection — rule-based classification engine
 Text detection — ML classifier (scikit-learn)
 FastAPI backend with file upload endpoint
 Image detection via HuggingFace
 Video frame extraction (OpenCV)
 React frontend with upload UI
 Confidence score display
 Deploy


Author
Temidayo Aiyeonegun
B.Sc. Computer Science | Memorial University of Newfoundland
