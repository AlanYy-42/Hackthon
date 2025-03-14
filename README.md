# StudyPath AI

Your Personal Academic Navigator - Revolutionizing Academic Planning with Edge AI Intelligence

## Project Overview

StudyPath AI transforms academic planning by leveraging Snapdragon's NPU to create a powerful, privacy-first platform for personalized academic guidance. Our solution addresses critical challenges in course selection, academic performance optimization, and career alignment that today's university students face.

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Seed the database with sample data:
   ```
   python seed_db.py
   ```
4. Run the application:
   ```
   python app.py
   ```
5. Open your browser and navigate to `http://localhost:5000`

## Features

- Intelligent Course Planning System
- Personal Learning Analytics
- Career Integration Module

## API Endpoints

- `/api/health` - Health check endpoint
- `/api/courses` - Get all courses
- `/api/courses/<course_id>` - Get a specific course
- `/api/students/<student_id>` - Get a specific student
- `/api/students/<student_id>/courses` - Get a student's courses
- `/api/recommendations` - Get course recommendations (POST)

## Sample Data

The seed script creates:
- 10 courses across Computer Science, Math, and English
- 3 students with different majors
- Course enrollments with various statuses

## Next Steps

1. Implement NPU integration for ML models
2. Add more sophisticated recommendation algorithms
3. Develop the learning analytics module
4. Create the career integration features
5. Enhance the UI with React Native or Flutter 