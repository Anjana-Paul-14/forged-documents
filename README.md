# Fake Document Detection using Python and Flask
## Introduction
A mini-project developed in Python with Flask to detect fake documents using a hashing technique. The system allows the admin to input an original template by cutting and hashing specific portions (e.g., heading and logo). When a new document is submitted, the system compares the pixel values of the original document and the submitted document to determine authenticity.

## Features
1. Admin Dashboard
- Template Submission: Admin can submit an original document template by specifying areas to be hashed.
2. Document Verification
- User Submission: Users can submit documents for verification.
- Pixel Value Comparison: The system compares pixel values of specified areas to detect discrepancies.
## Project Structure
1. Backend (Python and Flask)
- Routes: Define routes for admin actions (template submission) and user actions (document verification).
- Controllers: Implement controllers to handle template hashing and document verification.
- Hashing Technique: Use a custom hashing technique to hash specified areas of the original document.
2. Frontend (HTML, CSS, and Flask templates)
- Admin Interface: Allow admin to submit original document templates.
- User Interface: Enable users to submit documents for verification.
