# Enhancing Task Management with Reinforcement and Deep Learning

An AI-powered task management system that combines Reinforcement Learning and Deep Learning to deliver personalized, context-aware productivity recommendations.

The project integrates Proximal Policy Optimization (PPO) and Decision Transformers (DT) through an ensemble inference mechanism to balance real-time adaptability with long-term strategic planning.

---

## Features

- AI-driven personalized task recommendations
- MBTI-based personality-aware task planning
- Real-time chatbot interaction
- Hybrid PPO + Decision Transformer architecture
- Ensemble inference for balanced decision-making
- Sentiment-aware recommendation system
- React-based responsive frontend
- Node.js + Express backend APIs
- MongoDB integration for user and analytics storage

---

## Project Overview

Traditional productivity tools often rely on static prioritization systems and fail to adapt to changing user behavior. This project introduces a hybrid AI framework that dynamically adjusts task recommendations based on:

- User personality type (MBTI)
- Sentiment and conversational context
- Historical interaction patterns
- Real-time feedback and task urgency

The system acts as an intelligent productivity assistant capable of learning both short-term behavioral changes and long-term user preferences.

---

<img width="1226" height="588" alt="mbtiout1" src="https://github.com/user-attachments/assets/5706f2e3-5fd7-42e2-b1ee-575f6bc29447" />

<img width="756" height="848" alt="mbtiout2" src="https://github.com/user-attachments/assets/840f130e-ddd1-40b0-8b8b-38c14ca6f76e" />

<img width="1856" height="742" alt="mbtiout3" src="https://github.com/user-attachments/assets/a544d23a-356c-487f-a98d-7932a835e7a8" />




## Architecture

### Frontend
- React.js
- Interactive chatbot interface
- User personality and preference forms
- Real-time response rendering

### Backend
- Node.js
- Express.js REST APIs
- MongoDB database integration
- AI model orchestration

### AI Components

#### Proximal Policy Optimization (PPO)
Used for:
- Real-time decision adaptation
- Feedback-based learning
- Dynamic task prioritization

#### Decision Transformer (DT)
Used for:
- Long-term behavioral modeling
- Sequential task planning
- Historical pattern learning

#### Ensemble Mechanism
Combines PPO and DT outputs using weighted inference to generate balanced and context-aware recommendations.

---

## API Endpoints

| Endpoint | Description |
|----------|-------------|
| `/api/users` | Store user profile and MBTI data |
| `/api/chat` | Chatbot conversational endpoint |
| `/api/feedback` | Collect user feedback |
| `/api/analytics` | Retrieve usage and sentiment analytics |
| `/api/combined_response` | Generate ensemble AI recommendations |

---

## Example Recommendation

```text
"Focus on urgent tasks this morning and allocate time later today for long-term goals."
```

The system adapts recommendations based on:
- Personality type
- Emotional tone
- Task context
- Historical behavior

---

## Tech Stack

### Frontend
- React.js
- HTML/CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### AI / ML
- Python
- Stable-Baselines3
- OpenAI Gym
- Transformer-based architectures

---

## Future Improvements

- Online reinforcement learning updates
- Dynamic ensemble weighting
- Calendar and productivity app integration
- Expanded personality modeling
- Advanced analytics dashboard

---

## Research Contributions

This project demonstrates:
- Hybrid AI decision systems
- Personality-aware task management
- Integration of Reinforcement Learning with Transformer architectures
- Context-aware conversational productivity assistants

---

## Author

**Agnevesh Jagdish**  
Integrated M.Sc. Data Science  
Amrita Vishwa Vidyapeetham

---

## License

This project is intended for academic and research purposes.
