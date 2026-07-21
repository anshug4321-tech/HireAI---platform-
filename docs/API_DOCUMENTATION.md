# HireAI API Documentation

## Authentication

POST /api/auth/login

POST /api/auth/logout

POST /api/auth/forgot-password

POST /api/auth/reset-password

---

## Candidate

POST /api/candidate/register

GET /api/candidate/profile

PUT /api/candidate/profile

POST /api/candidate/upload-resume

---

## HR

POST /api/hr/create-job

GET /api/hr/jobs

PUT /api/hr/job/:id

DELETE /api/hr/job/:id

---

## Questions

POST /api/questions/generate

POST /api/questions/create

GET /api/questions

PUT /api/questions/:id

DELETE /api/questions/:id

---

## Interview

POST /api/interview/start

POST /api/interview/submit-answer

POST /api/interview/end

GET /api/interview/report

---

## AI

POST /api/ai/evaluate

POST /api/ai/match-score

POST /api/ai/generate-feedback

---

## Reports

GET /api/reports/pdf

GET /api/reports/excel

---

## Admin

GET /api/admin/dashboard

GET /api/admin/analytics

GET /api/admin/settings
