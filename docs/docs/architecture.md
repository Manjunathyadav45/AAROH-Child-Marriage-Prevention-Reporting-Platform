# AAROH - System Architecture

## 1. Frontend
Technology: React

Purpose:
- Display the website.
- Allow users to submit reports.
- Show information to authorised users.

## 2. Backend
Technology: Python FastAPI

Purpose:
- Process user requests.
- Handle report submissions.
- Connect frontend with database.
- Manage user permissions.

## 3. Database
Technology: PostgreSQL

Purpose:
- Store user accounts.
- Store report information.
- Maintain report status.
- Store authorised activity records.

## 4. AI and Machine Learning
Technology: Python and Scikit-learn

Purpose:
- Assist in report classification.
- Help prioritise reports.
- Provide classification confidence scores.

## 5. Security
- Secure authentication.
- Role-based access.
- Protect sensitive information.
- Maintain audit records.
- Restrict access to authorised personnel.

## 6. Human Verification
AI recommendations will be reviewed by authorised human reviewers before any intervention.

## 7. Overall Workflow
User → Frontend → Backend → Database → AI Assistance → Human Review → Authorised Action
