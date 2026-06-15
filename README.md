# ElectraVote: Secure Electronic Voting Infrastructure

## Overview

ElectraVote is a secure electronic voting system designed to conduct online elections efficiently and transparently. The platform enables administrators to manage elections and candidates while allowing registered voters to cast votes through a secure digital interface.

The system focuses on maintaining vote integrity, preventing duplicate voting, and generating reliable election results.

---

## Features

- Secure online voting system
- User authentication and authorization
- Admin panel for election management
- Candidate registration and management
- Voter registration and verification
- Prevention of duplicate voting
- Secure vote storage
- Automated result generation
- Database-driven architecture

---

## Technologies Used

### Backend
- Python
- FastAPI

### Database
- PostgreSQL
---

## System Architecture

The application follows a client-server architecture:

1. User interacts with the application interface
2. FastAPI handles API requests and business logic
3. PostgreSQL stores user, election, candidate, and voting data
4. Results are generated from securely stored votes
---

## Installation and Setup

### 1. Clone the repository

```bash
git clone <repository-url>
```

### 2. Navigate to the project folder

```bash
cd ElectraVote
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate environment:

Windows:
```bash
venv\Scripts\activate
```

Mac/Linux:
```bash
source venv/bin/activate
```

---

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Database Configuration

Create a PostgreSQL database and update the database connection details in the configuration file.

Example:

```
DATABASE_URL =
postgresql://username:password@localhost/database_name
```

---

## Running the Application

Start the FastAPI server:

```bash
uvicorn app.main:app --reload
```

The application will run on:

```
http://127.0.0.1:8000
```

API documentation:

```
http://127.0.0.1:8000/docs
```

---

## Security Features

- Authentication-based access control
- Unique voter verification
- Duplicate vote prevention
- Secure database transactions
- Data validation

---

## Future Improvements

- Add biometric authentication
- Implement blockchain-based vote verification
- Add advanced encryption techniques
- Develop a frontend interface
- Deploy using cloud infrastructure

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Backend development using FastAPI
- Database management with PostgreSQL
- Secure application development
- Building real-world software systems

---
