---
title: "Insight-Ed (HackNITR 5.0) | EdTech Platform for Student and Teacher"
collection: talks
excerpt: "
Imagine an online classroom where teachers instantly know when and why students lose focus. Our AI-powered solution bridges the knowledge gap by detecting student emotions and attentiveness, highlighting problem areas, makes the teacher aware of each student's progress. With features like reverse video search, dynamic questionnaires, and advanced Q&A bots, we transform the learning experience, making it more interactive and insightful. Redefining online education with our model, ensuring every student gets the attention they need, right when they need it.
"
type: "Hackathon"
permalink: 
venue: "NIT"
date: March 3 '24
location: "Rourkela"
---

* **Role**: Backend (AI/ML+Server)

* **Vision/Goal**: Our solution tries to bridge the knowledge gap between a teacher and a student in online classes by leveraging the power of AI to provide the teacher and student with insights to better prepare themselves for the course/lecture.

* **Features** 

**Detection of Emotion and Attentiveness of a Student** | Used Transfer Learning on EfficientNetB7 model along with a custom dataset combined with an open-sourced LLMs to capture the same through the recorded lecture which the student attended through the webcam during that session.

**Topic Modelling for Each Segment where Student lost attention** | Through the power of Gemini-Pro SDK and OpenAI Whisper module, each of the segments where the loss of interest is detected is transcribed into text and the most relevant keywords(Topic Modelling) are done to bring out the topics where students need clarification. | The teacher is thus present with an analysis as to when the student lost his/her attention and on which topic(s) through the video lecture

**Generation of Different Topics on specified time intervals - Saving Teacher's Time** | This feature allows automatic Generation of Different Topics-Topic Modelling depending on a hyperparameter(time interval) chosen by the teacher exclusively.

**Reverse Video Search** | This feature allows the student to not get through the video again and again for a particular keyword but rather type it and get the exact timestamp(s) for the same.

**Generation of Questionnaire on topics where students lacked attention** | This feature allows the teacher to generate/upload a questionnaire through an LLM for the topics for the student to double-check his/her understanding to plan further steps. -> The student can also get recommended most relevant YouTube videos on the same or the teacher could suggest some materials or videos from their course itself.

**Advance RAG-based QnA bot (Handwritten/Non-Handwritten)** | This feature allows the user to perform question-answer with their uploaded PDFs whether it's Handwritten/Non-Handwritten (under-development). | This allows the student to quickly search and get relevant information/explanation for a particular topic of interest and not go through searching for it, wasting their precious time.

**Advance RAG-based QnA bot for Video/Tutorial** | This feature allows the user to perform question-answer with their video/tutorials. -> This allows the student to quickly search and get relevant information/explanation for a particular topic of interest in the video/tutorial and not go through searching for it throughout the video.

* **Tools**: 

**Client:** |  Tailwind CSS, TypeScript, Next.js

**Backend:** | Flask, Python, Langchain, GeminiPro and GeminiProVision API, OpenAI Whisper API, HuggingFace Open-Source Models (EmotionLLM), MTCNN, Next.js, TypeScript

**Storage:** | PostgreSQL, ChromaDB

**Other Tools:** | GCP (Cloud Run), Docker, Vercel

[**Project Link**](https://github.com/YuvrajSingh-mist/Insight-Ed)
