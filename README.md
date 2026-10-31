# PrepOS – AI-Powered Placement Preparation Platform

<p align="center">
  <strong>Prepare Smarter. Practise Better. Perform Confidently.</strong>
</p>

<p align="center">
  An AI-powered placement preparation platform designed to help students and job seekers improve their technical interview skills through adaptive readiness assessments, dynamic AI mock interviews, live coding practice, and personalised performance analytics.
</p>

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Key Features](#-key-features)
- [Feature Breakdown](#-feature-breakdown)
- [System Architecture](#-system-architecture)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Application Workflow](#-application-workflow)
- [Quick Start](#-quick-start)
- [Environment Configuration](#-environment-configuration)
- [API Documentation](#-api-documentation)
- [Database Schema](#-database-schema)
- [Testing](#-testing)
- [Development Roadmap](#-development-roadmap)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)
- [Original Repository](#-original-repository)

---

## 🚀 Project Overview

**PrepOS** is an AI-powered placement preparation platform that provides students with a structured environment to practise technical interviews and assess their placement readiness.

The platform combines artificial intelligence, full-stack web development, coding environments, and performance analytics to create a personalised interview preparation experience.

Candidates can evaluate their technical skills, participate in AI-generated mock interviews, solve coding problems, receive dynamic follow-up questions, and analyse their performance through detailed scorecards.

The platform is designed around different company categories:

- FAANG
- Fintech
- Product-based companies
- Service-based companies

### Project Information

| Attribute | Details |
|---|---|
| Project Name | PrepOS |
| Category | Artificial Intelligence / Full-Stack Development |
| Project Type | Collaborative Group Project |
| Version | 0.1.0 Beta |
| Status | Active Development |
| Primary Purpose | Placement and Technical Interview Preparation |

---

## 🎯 Problem Statement

Students preparing for campus placements often face difficulties in understanding their actual placement readiness.

Traditional preparation methods may not provide:

- Personalised technical interview practice.
- Realistic interview simulations.
- Dynamic questions based on previous answers.
- Structured evaluation of technical knowledge.
- Detailed performance analytics.
- Clear recommendations for improvement.

PrepOS aims to address these challenges through an integrated AI-based preparation platform.

---

## ⭐ Key Features

### 1. Adaptive Placement Readiness Dashboard

Provides an overview of a candidate's placement readiness.

- Overall placement readiness score.
- Skill-wise performance benchmarking.
- Company-tier readiness comparison.
- Skill-level radar charts.
- Identification of strengths and weaknesses.
- Personalised improvement recommendations.

### 2. AI-Powered Dynamic Mock Interviewer

Provides an interactive technical interview experience.

- AI-generated technical questions.
- Dynamic follow-up questions based on candidate responses.
- Topic-based interview sessions.
- Difficulty-based question selection.
- Evaluation of technical reasoning and communication.
- Interview session scorecards.

### 3. Live Coding Workspace

Provides an integrated coding environment for technical interview practice.

- Monaco Editor integration.
- Coding problem statements.
- Code submission and explanation capture.
- Interview-based coding practice.
- Support for evaluating code quality and problem-solving approaches.

### 4. Performance Analytics and Feedback

Helps candidates understand their interview performance.

- Technical accuracy assessment.
- Code quality evaluation.
- Edge-case reasoning assessment.
- Time and space complexity evaluation.
- Communication and explanation assessment.
- Performance scorecards.
- Personalised improvement recommendations.

---

## 🔍 Feature Breakdown

### Placement Readiness Assessment

The readiness assessment evaluates candidates across different technical skill areas.

The platform uses weighted skill benchmarks to calculate an overall readiness score.

Example assessment dimensions include:

- Data Structures and Algorithms (DSA).
- System Design.
- Technical problem-solving.
- Programming proficiency.
- Communication and explanation skills.

### AI Interview Simulation

The mock interview workflow follows an interactive question-and-answer process.

1. Candidate selects an interview topic and difficulty.
2. The system generates an initial technical question.
3. Candidate submits an answer, code snippet, or explanation.
4. The AI analyses the submitted response.
5. A relevant follow-up question is generated.
6. The process continues until the interview is completed.
7. A final performance scorecard is generated.

### Interview Evaluation

The interview evaluation considers multiple dimensions.

| Evaluation Category | Assessment Parameters |
|---|---|
| Technical Accuracy | Correctness and approach |
| Code Quality | Code structure and readability |
| Problem Solving | Logical reasoning |
| Edge Cases | Handling unusual inputs |
| Complexity Analysis | Time and space complexity |
| Communication | Clarity and articulation |
| Overall Performance | Combined interview assessment |

---

## 🏗️ System Architecture

PrepOS follows a full-stack architecture consisting of frontend, backend, database, and AI integration layers.

### Architecture Overview

```text
                 ┌───────────────────────────┐
                 │       CANDIDATE           │
                 │                           │
                 │ Dashboard / Interview     │
                 │ Coding / Analytics        │
                 └─────────────┬─────────────┘
                               │
                               ▼
                 ┌───────────────────────────┐
                 │      FRONTEND LAYER       │
                 │                           │
                 │ Next.js                   │
                 │ React                     │
                 │ TypeScript                │
                 │ Tailwind CSS              │
                 │ Monaco Editor             │
                 └─────────────┬─────────────┘
                               │
                         API Communication
                               │
                               ▼
                 ┌───────────────────────────┐
                 │       BACKEND LAYER       │
                 │                           │
                 │ Python                    │
                 │ FastAPI                   │
                 │                           │
                 │ Readiness Scoring         │
                 │ Interview Management      │
                 │ Response Evaluation       │
                 └────────┬──────────┬───────┘
                          │          │
                ┌─────────▼───┐  ┌───▼────────────┐
                │ AI LAYER    │  │ DATABASE LAYER │
                │             │  │                │
                │ OpenAI API  │  │ PostgreSQL     │
                │             │  │ Prisma         │
                └─────────────┘  └────────────────┘
```

### Frontend Layer

**Technologies:** Next.js, React, TypeScript, Tailwind CSS.

Responsibilities:

- Candidate dashboard.
- Placement readiness visualisation.
- Mock interview interface.
- Live coding environment.
- Performance analytics.
- Communication with backend APIs.

### Backend Layer

**Technologies:** Python and FastAPI.

Responsibilities:

- Interview session management.
- Readiness score calculation.
- AI question generation.
- Candidate response processing.
- Interview scorecard generation.
- Backend API management.

### AI Integration Layer

**Technology:** OpenAI API.

Responsibilities:

- Technical question generation.
- Dynamic follow-up question generation.
- Candidate response analysis.
- Interview feedback generation.
- Personalised recommendations.

### Database Layer

**Technologies:** PostgreSQL and Prisma.

Responsibilities:

- Candidate profile information.
- Skill benchmarks.
- Interview session information.
- Performance scores.
- Feedback and assessment records.

---

## 💻 Technology Stack

| Category | Technology |
|---|---|
| Frontend Framework | Next.js 14 |
| UI Library | React 18 |
| Programming Language | TypeScript |
| Styling | Tailwind CSS |
| Backend Language | Python |
| Backend Framework | FastAPI |
| Database | PostgreSQL |
| ORM | Prisma |
| AI Integration | OpenAI API |
| Code Editor | Monaco Editor |
| Data Visualisation | Recharts |
| API Documentation | Swagger UI |
| Containerisation | Docker |
| Version Control | Git and GitHub |

---

## 📁 Project Structure

The following is an overview of the documented application directories and configuration files.

```text
PrepOS/
│
├── apps/
│   │
│   ├── backend/
│   │   ├── app/
│   │   │   └── main.py
│   │   ├── requirements.txt
│   │   ├── .env.example
│   │   └── venv/
│   │
│   └── web/
│       ├── package.json
│       ├── .env.example
│       └── ...
│
├── infra/
│   └── docker-compose.yml
│
├── docs/
│   ├── ARCHITECTURE.md
│   ├── API.md
│   └── SETUP.md
│
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

*Note: This is an illustrative structure based on the original setup documentation. It is not a verified, exhaustive listing of every source file.*

---

## ⚙️ Quick Start

Follow the steps below to configure and run the original PrepOS application locally.

### Prerequisites

Install the following software before starting:

| Requirement | Version |
|---|---|
| Node.js | 18+ |
| Python | 3.10+ |
| PostgreSQL | 14+ |
| Git | Latest stable version |
| OpenAI API Key | Required for AI integration |

Useful resources:

- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Git](https://git-scm.com/)
- [OpenAI API Platform](https://platform.openai.com/api-keys)

### Step 1: Clone the Original Repository

```bash
git clone https://github.com/SujithRK768/PrepOS.git

cd PrepOS
```

### Step 2: Backend Setup

Navigate to the backend directory:

```bash
cd apps/backend
```

Create a Python virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create the environment configuration file:

```bash
cp .env.example .env
```

On Windows, you can also copy the file manually.

### Step 3: Database Setup

There are two ways to configure PostgreSQL.

**Option A: Using Docker**

Navigate to the infrastructure directory:

```bash
cd infra
```

Start PostgreSQL:

```bash
docker-compose up -d
```

**Option B: Manual PostgreSQL Setup**

Create a database:

```bash
createdb prepos
```

Update the database connection string in the backend `.env` file.

### Step 4: Frontend Setup

Navigate to the frontend directory:

```bash
cd apps/web
```

Install dependencies:

```bash
npm install
```

Create the frontend environment configuration:

```bash
cp .env.example .env.local
```

### Step 5: Configure Environment Variables

Configure the backend and frontend environment variables as described in the next section.

### Step 6: Run the Applications

Open two separate terminals.

**Terminal 1 – Backend**

```bash
cd apps/backend

# Activate the virtual environment first

python -m uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

**Terminal 2 – Frontend**

```bash
cd apps/web

npm run dev
```

### Step 7: Verify the Setup

Once both applications are running, access:

| Service | Local URL |
|---|---|
| Frontend Application | http://localhost:3000 |
| Backend API | http://localhost:8000 |
| Swagger API Documentation | http://localhost:8000/docs |
| Backend Health Check | http://localhost:8000/health |

---

## 🔐 Environment Configuration

Environment variables are used to configure database connections, API access, and application settings.

### Backend Configuration

File: `apps/backend/.env`

```env
# Database Configuration
DATABASE_URL=postgresql://postgres:password@localhost:5432/prepos

# OpenAI API Configuration
OPENAI_API_KEY=your_openai_api_key

# Server Configuration
ENV=development
HOST=0.0.0.0
PORT=8000

# JWT Configuration (Future)
SECRET_KEY=your_secret_key
ALGORITHM=HS256
```

### Frontend Configuration

File: `apps/web/.env.local`

```env
NEXT_PUBLIC_API_URL=http://localhost:8000

NEXT_PUBLIC_APP_NAME=PrepOS
```

**Security Note:** Never commit real API keys, passwords, secret keys, or private credentials to GitHub. Use placeholder values in documentation and keep actual credentials in local environment files.

---

## 🔌 API Documentation

PrepOS uses FastAPI to manage communication between the frontend and backend.

### Base URL

```text
http://localhost:8000/api/v1
```

### Interactive API Documentation

FastAPI provides interactive API documentation through Swagger UI.

[Open Swagger Documentation](http://localhost:8000/docs)

### Core API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/readiness/score` | Calculate placement readiness |
| POST | `/interview/session/init` | Initialise interview session |
| POST | `/interview/session/{session_id}/answer` | Submit answer and receive follow-up |
| POST | `/interview/scorecard` | Generate interview scorecard |
| GET | `/interview/session/{session_id}` | Retrieve interview session |

### 1. Initialise Interview Session

**Endpoint:**

```http
POST /api/v1/interview/session/init
```

**Example Request:**

```json
{
  "candidate_id": "cand_123",
  "interview_topic": "DSA",
  "difficulty": "medium",
  "duration_minutes": 45,
  "num_questions": 3
}
```

**Example Response:**

```json
{
  "session_id": "550e8400-e29b-41d4-a716-446655440000",
  "candidate_id": "cand_123",
  "interview_topic": "DSA",
  "difficulty": "medium",
  "first_question": "Given an array of integers, find the two numbers that add up to a target...",
  "started_at": "2026-09-26T12:00:00Z"
}
```

### 2. Submit Answer and Generate Follow-Up

**Endpoint:**

```http
POST /api/v1/interview/session/{session_id}/answer
```

**Example Request:**

```json
{
  "session_id": "550e8400-e29b-41d4-a716-446655440000",
  "candidate_answer": {
    "question_id": "q1",
    "question_text": "Two Sum Problem...",
    "answer": "I would use a hash map...",
    "code_snippet": "def twoSum(nums, target):\n    seen = {}\n    for num in nums:\n        ...",
    "approach_explanation": "Hash map for O(n) time complexity",
    "time_taken_seconds": 540,
    "confidence": 85
  }
}
```

**Example Response:**

```json
{
  "session_id": "550e8400-e29b-41d4-a716-446655440000",
  "follow_up_question": "Good! Now, what if we need to handle duplicate numbers?",
  "rationale": "Follow-up generated based on candidate response analysis.",
  "question_number": 1,
  "is_final": false
}
```

### 3. Generate Interview Scorecard

**Endpoint:**

```http
POST /api/v1/interview/scorecard
```

**Example Request:**

```json
{
  "session_id": "550e8400-e29b-41d4-a716-446655440000",
  "candidate_id": "cand_123",
  "interview_topic": "DSA",
  "answers": []
}
```

**Example Response:**

```json
{
  "session_id": "550e8400-e29b-41d4-a716-446655440000",
  "candidate_id": "cand_123",
  "scorecard": {
    "technical_accuracy": {
      "correctness": 88,
      "approach": 82,
      "code_quality": 85,
      "edge_case_handling": 76,
      "time_complexity": 90,
      "space_complexity": 78
    },
    "communication": {
      "clarity": 87,
      "problem_understanding": 89,
      "articulation": 84,
      "collaboration": 88
    },
    "overall_score": 84.5,
    "strengths": [
      "Strong algorithmic thinking",
      "Clear code articulation"
    ],
    "areas_for_improvement": [
      "Edge case handling",
      "Trade-off explanation"
    ],
    "detailed_feedback": "..."
  },
  "recommendations": [
    "Continue practicing edge cases..."
  ],
  "generated_at": "2026-09-26T12:15:00Z"
}
```

### 4. Calculate Placement Readiness Score

**Endpoint:**

```http
POST /api/v1/readiness/score
```

**Example Request:**

```json
{
  "candidate_id": "cand_123",
  "answers": [
    {
      "question_id": "q1",
      "category": "DSA",
      "score": 88,
      "difficulty": "medium",
      "time_taken_seconds": 540,
      "confidence": 80
    }
  ]
}
```

**Example Response:**

```json
{
  "candidate_id": "cand_123",
  "overall_readiness_score": 81.64,
  "readiness_level": "Strong",
  "benchmark_scores": [
    {
      "category": "DSA",
      "score": 82,
      "weight": 0.3
    },
    {
      "category": "SYSTEM_DESIGN",
      "score": 76,
      "weight": 0.2
    }
  ],
  "generated_at": "2026-09-26T12:00:00Z"
}
```

*Note: The API payloads and responses above are illustrative examples from the project documentation, not guarantees of live API behaviour.*

---

## 🗄️ Database Schema

PrepOS uses PostgreSQL to organise candidate information, skill benchmarks, interview sessions, and feedback.

### 1. User Model

Stores candidate profile information.

| Field | Description |
|---|---|
| id | Unique user identifier |
| email | Candidate email |
| name | Candidate name |
| role | Candidate role |
| college | College or institution |
| graduationYear | Graduation year |
| targetTier | Target company category |
| createdAt | Record creation time |
| updatedAt | Last update time |

### 2. Skill Model

Stores candidate skill assessment information.

| Field | Description |
|---|---|
| id | Unique skill identifier |
| userId | Associated user |
| name | Skill name |
| domain | Skill category |
| score | Skill assessment score |
| percentile | Relative performance |
| targetLevel | Target proficiency level |
| confidence | Candidate confidence |
| lastAssessedAt | Last assessment date |

### 3. InterviewSession Model

Stores information about interview sessions.

| Field | Description |
|---|---|
| id | Unique session identifier |
| userId | Associated user |
| mode | Interview mode |
| status | Session status |
| questionSet | Interview questions |
| durationMinutes | Interview duration |
| overallScore | Overall score |
| technicalScore | Technical score |
| communicationScore | Communication score |
| summary | Interview summary |
| createdAt | Record creation time |
| updatedAt | Last update time |

### 4. Feedback Model

Stores candidate feedback and evaluation results.

| Field | Description |
|---|---|
| id | Unique feedback identifier |
| userId | Associated user |
| interviewSessionId | Related interview session |
| type | Feedback category |
| title | Feedback title |
| content | Feedback description |
| score | Feedback score |
| createdAt | Record creation time |

---

## 👨‍🎓 User Workflow

### Candidate Workflow

**Step 1 – Visit Dashboard**

- View overall placement readiness score.
- Review skill benchmarks across five dimensions.
- Check readiness for FAANG, Fintech, Product, and Service company categories.
- Identify strengths and areas requiring improvement.

**Step 2 – Start Mock Interview**

- Select interview topic and difficulty.
- Receive AI-generated technical questions.
- Write code using the Monaco Editor.
- Explain the problem-solving approach.
- Answer dynamic follow-up questions.
- Complete the interview session.

**Step 3 – Review Performance**

- View detailed interview scorecards.
- Analyse technical and communication performance.
- Review strengths and improvement areas.
- Receive actionable recommendations.
- Track performance across interview sessions.

---

## 🧪 Testing

Testing commands documented for the backend and frontend are provided below.

### Backend Testing

Navigate to the backend directory:

```bash
cd apps/backend
```

Run tests:

```bash
pytest --cov=app
```

### Frontend Testing

Navigate to the frontend directory:

```bash
cd apps/web
```

Run tests:

```bash
npm run test
```

Run test coverage:

```bash
npm run test:coverage
```

---

## 🛣️ Development Roadmap

### Current Release – v0.1.0 Beta

The original project documentation identifies the following phases as completed:

- [x] Phase 1: Database schema and readiness scoring API.
- [x] Phase 2: AI mock interviewer with LLM integration.
- [x] Phase 3: Frontend dashboard and analytics.
- [x] Phase 4: Documentation and consolidation.

### Phase 5 – Code Execution and Testing

- Judge0 API integration.
- Live code execution.
- Real-time code testing and validation.
- Test-case evaluation.

### Phase 6 – Voice and Speech

- Speech-to-text transcription.
- Audio interview capabilities.
- Real-time transcript generation.

### Phase 7 – Advanced Features

- User authentication and authorisation.
- Interview session persistence.
- Progress tracking dashboard.
- Peer benchmarking.
- Adaptive study recommendations.

### Phase 8 – Mobile and Enterprise

- React Native mobile application.
- Enterprise dashboard.
- Bulk candidate management.
- Advanced analytics and reporting.

---

## 🔧 Troubleshooting

### Backend Issues

**Error: `No module named 'app'`**

Possible solution:

- Navigate to the `apps/backend` directory.
- Activate the Python virtual environment.
- Run the backend from the correct working directory.

**Error: `Database connection refused`**

Possible solution:

- Verify that PostgreSQL is running.
- Check the `DATABASE_URL` value in `.env`.
- If using Docker, start the database using:

```bash
docker-compose up -d
```

**Error: `OPENAI_API_KEY not set`**

Possible solution:

- Add a valid OpenAI API key to the backend `.env` file.
- Verify that the environment variable is configured correctly.

[Get an OpenAI API Key](https://platform.openai.com/api-keys)

### Frontend Issues

**Error: `Module not found: @monaco-editor/react`**

Possible solution:

```bash
npm install
```

Run this command inside the `apps/web` directory.

**Error: `API connection refused`**

Possible solution:

- Ensure that the backend is running on port 8000.
- Check the `NEXT_PUBLIC_API_URL` value.
- Verify that the frontend is communicating with the correct backend address.

---

## 🤝 Contributing

Contributions from developers, designers, and other interested contributors are welcome in the original project repository.

### Contribution Workflow

**1. Fork the repository**

**2. Create a feature branch**

```bash
git checkout -b feature/your-feature-name
```

**3. Commit your changes**

```bash
git add .

git commit -m "Add your feature description"
```

**4. Push your branch**

```bash
git push origin feature/your-feature-name
```

**5. Open a Pull Request**

For detailed contribution guidelines, refer to:

[CONTRIBUTING.md](https://github.com/SujithRK768/PrepOS/blob/main/CONTRIBUTING.md)

---

## 📄 License

The original PrepOS project documentation identifies the project as licensed under the **MIT License**.

Refer to the original repository's [LICENSE file](https://github.com/SujithRK768/PrepOS/blob/main/LICENSE) for the licence terms.

---

## 🙌 Acknowledgements

This project represents a collaborative effort exploring the application of Artificial Intelligence and full-stack technologies in placement preparation and technical interview assessment.

Special acknowledgement to the original project maintainer and contributors for their work on the PrepOS platform.

---

## 🔗 Original Repository

This repository serves as a project documentation and portfolio reference for PrepOS.

**Original Source Repository:**

[github.com/SujithRK768/PrepOS](https://github.com/SujithRK768/PrepOS)

**Original Maintainer:**

[SujithRK768](https://github.com/SujithRK768)

The original repository contains the application's source code and implementation. Please refer to it for the latest code, project updates, and development activity.

---

<p align="center">
  <strong>PrepOS – Building Smarter Ways to Prepare for Opportunities.</strong>
</p>

<p align="center">
  Design. Develop. Practise. Improve.
</p>
