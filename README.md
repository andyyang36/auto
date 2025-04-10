## AI Job Application Autofill Assistant
---

This project aims to automate the process of filling out job applications by intelligently reusing and generating responses based on a user's past inputs.

The system will store a database of previously answered job application questions (e.g. "Tell us about a time you worked on a team") and learn to recognize when new questions are paraphrased versions of old ones (e.g. "Describe a collaborative experience"). When it detects a match, it will reuse the stored response. If there is no good match, it will generate a new answer using the user's stored profile information — without making anything up.
It will also ensure that newly encountered questions and their answers are saved to the database for future use, making the assistant smarter and faster over time.

## Status
---
This is an early-stage project focused on the logic layer for question matching and smart answer generation. Chrome extension, UI, and backend integration are currently WIP.
