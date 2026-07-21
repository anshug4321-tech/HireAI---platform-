# HireAI Database Schema

## Users
- id
- name
- email
- password
- role (Admin / HR)

## Candidates
- id
- full_name
- phone
- email
- education
- college
- experience
- skills
- resume_url
- portfolio_url
- linkedin_url

## Jobs
- id
- job_title
- department
- experience_required
- description
- skills

## Questions
- id
- job_id
- question
- difficulty
- marks
- time_limit

## Interviews
- id
- candidate_id
- job_id
- interview_date
- status

## Answers
- id
- interview_id
- question_id
- answer

## AI Reports
- id
- interview_id
- technical_score
- communication_score
- confidence_score
- overall_score
- match_percentage
- recommendation

## Proctoring Logs
- id
- interview_id
- eye_tracking
- phone_detection
- multiple_face
- background_voice
- suspicious_activity
