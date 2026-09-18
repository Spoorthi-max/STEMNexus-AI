# 🌐 STEMNexus AI

### Multilingual Generative AI Platform for Accessible STEM Learning

> STEMNexus AI is a Generative AI-powered educational platform that simplifies complex STEM concepts through multilingual explanations, difficulty-based learning, localized real-world analogies, and audio-based learning support.

---

## 📌 Problem Statement

Many students, particularly those from rural and regional-language backgrounds, face difficulties understanding Science, Technology, Engineering, and Mathematics (STEM) concepts because a large amount of educational content is primarily available in English.

This language barrier can make complex concepts harder to understand and reduce student engagement with STEM subjects.

STEMNexus AI addresses this challenge by providing:

- Multilingual STEM explanations
- Difficulty-adaptive learning
- Localized real-world examples
- Audio-based explanations
- Generative AI-powered educational content

The goal is to make STEM education more accessible, understandable, and engaging for learners from diverse linguistic backgrounds.

---

# 🚀 Project Overview

STEMNexus AI is an AI-powered learning platform that uses Generative AI to dynamically generate explanations for STEM concepts according to the learner's:

- Subject
- Concept
- Preferred language
- Educational level

The system generates explanations in multiple languages and supplements them with familiar examples and analogies, particularly inspired by local Karnataka contexts.

The platform also provides audio narration using Text-to-Speech technology, allowing learners to consume educational content through both reading and listening.

### Currently Supported Languages

- 🇬🇧 English
- 🇮🇳 Kannada
- 🇮🇳 Hindi

---

# 🎯 Objectives

The primary objectives of STEMNexus AI are:

- 🌍 Reduce language barriers in STEM education.
- 🧠 Simplify complex STEM concepts using Generative AI.
- 🎓 Adapt explanations to different educational levels.
- 🌾 Provide familiar and localized real-world analogies.
- 🔊 Enable audio-based learning.
- 📚 Encourage self-paced learning.
- 🤝 Make STEM education more inclusive and accessible.

---

# ✨ Key Features

## 🌍 1. Multilingual STEM Learning

The platform generates explanations in multiple languages.

### Supported Languages

- English
- Kannada
- Hindi

This allows students to understand STEM concepts using their preferred language.

---

## 🎓 2. Difficulty-Based Learning

Explanations can be adapted according to the learner's educational level.

### Learning Levels

- Primary Level
- Secondary Level
- Pre-University Level

The same concept can therefore be explained with different levels of complexity.

---

## 🌾 3. Localized Learning

STEMNexus AI uses familiar real-world examples and Karnataka village-based analogies to explain abstract concepts.

For example, a scientific or mathematical concept can be connected to:

- Farming
- Village infrastructure
- Water usage
- Local transportation
- Everyday household activities

This helps learners connect theoretical concepts with situations they already understand.

---

## 🔊 4. Audio Learning

The platform converts generated explanations into speech using Google Text-to-Speech (gTTS).

This provides:

- Audio-based learning
- Improved accessibility
- Alternative learning format
- Support for learners who prefer listening

---

## 🤖 5. Generative AI Content

STEMNexus AI uses Google's Gemini API to dynamically generate educational explanations.

Instead of relying only on predefined content, the system can generate explanations based on the user's selected:

- STEM subject
- Concept
- Language
- Difficulty level

---

## ⚡ 6. Interactive Learning Interface

The application provides a simple interface where users can:

1. Select a STEM subject.
2. Select their learning level.
3. Enter a concept.
4. Select a preferred language.
5. Generate an explanation.
6. View the localized analogy.
7. Listen to the generated explanation.

---

# 🔄 Application Workflow

```text
                    ┌───────────────────┐
                    │      User         │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ Select Subject    │
                    │ & Difficulty      │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ Enter STEM        │
                    │ Concept           │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ Streamlit         │
                    │ Frontend          │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ Gemini API        │
                    │ Generative AI     │
                    └─────────┬─────────┘
                              │
                              ▼
             ┌─────────────────────────────────┐
             │      Educational Content        │
             │                                 │
             │ • Concept Explanation           │
             │ • Multilingual Output           │
             │ • Localized Analogy             │
             └───────────────┬─────────────────┘
                             │
                             ▼
                    ┌───────────────────┐
                    │      gTTS          │
                    │ Text-to-Speech     │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ Final Learning    │
                    │ Output            │
                    │                   │
                    │ Text + Audio      │
                    └───────────────────┘
## Technologies Used

### Frontend

* Streamlit

### Backend

* Python

### AI Model

* Gemini 2.5 Flash

### Audio Generation

* Google Text-to-Speech (gTTS)

### Environment Management

* Python Virtual Environment

---

## Project Structure

```text
team-02
│
├── app.py
├── README.md
├── requirements.txt
├── Multilingual_STEM_Explainer.pptx
└── .gitignore
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run app.py
```

---

## Future Enhancements

* Additional Indian language support.
* Image and diagram generation.
* STEM quizzes and assessments.
* Voice-based interaction.
* Offline educational mode.
* Personalized learning recommendations.

---

## Conclusion

STEMNexus AI  Explainer demonstrates how Generative AI can make education more inclusive and accessible. By combining multilingual explanations, localized analogies, and audio support, the platform helps students understand STEM concepts in a simple and engaging manner.

This project contributes toward bridging educational gaps and promoting accessible learning for all.
