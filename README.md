# Opportunity Aggregation Platform

A comprehensive, fully automated platform for discovering, aggregating, and matching humanitarian, development, government, academic, and private sector opportunities across Sudan and East Africa.

## 🎯 Vision

Build the most modern and comprehensive opportunities platform, serving as the primary source for jobs, trainings, scholarships, consultancies, volunteering opportunities, and career development resources.

## ✨ Features

### Core Features
- **Automated Data Collection**: Intelligent aggregation from 40+ approved sources
- **Smart Import Engine**: Duplicate detection, expiration tracking, auto-categorization
- **AI Categorization**: Automatic classification into 24+ job categories
- **CV Parsing**: Extract education, experience, skills automatically
- **AI Matching Engine**: Match opportunities to user profiles (0-100% score)
- **Advanced Search**: Filter by job title, skills, location, salary, deadline
- **Job Alerts**: Email, SMS, WhatsApp, push notifications
- **Analytics Dashboard**: Comprehensive insights and trends
- **Multi-Language Support**: English & Arabic
- **Community Resources**: CV templates, interview prep, career guides
- **Premium Features**: Early alerts, AI optimization, career roadmap

## 🛠 Tech Stack

- **Backend**: Node.js, Express.js, PostgreSQL, Redis
- **Frontend**: React, Redux, Material-UI, Tailwind CSS
- **Mobile**: React Native (iOS & Android)
- **AI**: OpenAI API, NLP
- **Search**: Elasticsearch
- **Notifications**: Email, SMS (Twilio), WhatsApp
- **Deployment**: Docker, GitHub Actions

## 📁 Project Structure

```
backend/          - Express.js API
frontend/         - React application
mobile/           - React Native app
docs/             - Documentation
docker-compose.yml - Container orchestration
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 13+
- Redis 6+
- Docker (optional)

### Setup with Docker

```bash
docker-compose up -d
```

### Manual Setup

**Backend:**
```bash
cd backend
npm install
npm run migrate
npm run dev
```

**Frontend:**
```bash
cd frontend
npm install
npm run dev
```

## 📚 Documentation

- [Architecture](./docs/ARCHITECTURE.md)
- [Database Schema](./docs/DATABASE.md)
- [API Documentation](./docs/API.md)
- [Project Roadmap](./PROJECT_ROADMAP.md)

## 🔐 Security

- JWT Authentication + 2FA
- Role-based access control
- Rate limiting
- GDPR compliance
- Audit logging

## 📈 Scalability

Supports:
- 100,000+ concurrent users
- 50,000+ opportunities
- 1,000+ organizations
- Millions of page views

## 📝 License

MIT License - see LICENSE file

---

**Last Updated**: June 2026 | **Version**: 1.0.0
