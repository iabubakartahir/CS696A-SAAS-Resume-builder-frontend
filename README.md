# CS696A-SAAS-Resume-builder-frontend

## Quick Start
### Install dependencies
npm install

### Start development server
npm run dev
Open http://localhost:5173 🚀

See QUICK_START.md for 30-second setup guide

## Features

###  Template System
6+ professional templates (Modern, Classic, Creative, Premium)
CSS-based previews (no external images needed)
Template-specific color schemes
Real-time preview updates
Search and filter templates
### Resume Editor
Side-by-side editor and live preview
Step-by-step guided editing
Auto-save functionality (1-second debounce)
Drag-and-drop sections
Professional form validation
### Enhanced Date Pickers
HTML5 date inputs with calendar UI
Visual indicators (📅 calendar icons)
Format hints (MM/DD/YYYY)
Smart "Currently working here" checkbox
Disabled states for active positions
### AI-Powered Content
Summary Generation: AI writes professional summaries
Experience Bullets: AI generates achievement-focused bullet points
Context-aware suggestions based on job descriptions
Multiple response format handling
Success/error feedback alerts
### Export & Import
Export: PDF, DOCX, TXT formats
Import: Upload existing resume (PDF/DOCX)
AI-powered parsing with OpenAI
Preview before import
One-click download
### Authentication
Email/password authentication
Google OAuth integration
LinkedIn OAuth integration
JWT token management
Automatic token refresh
Protected routes
### Data Management
Auto-save every 1 second
Resume versioning
Delete with confirmation
Duplicate resumes
Cloud storage

## Key Components

### Resume Builder Component

The primary resume editing interface, featuring:

A structured 5-step guided workflow (Basics → Experience → Education → Skills → Summary)

Real-time resume preview with template-specific styling

Integrated AI-assisted sections, visually highlighted with blue backgrounds

Professional date pickers with format guidance

Automatic saving with a visible save-status indicator

#### Dashboard Component

Handles resume management and template selection, including:

Template gallery displayed in a responsive grid layout using CSS-based mockups

Search and category-based filtering for templates

Visual premium template indicators

Resume cards with edit and delete actions

Modal-based resume upload functionality

### Resume Upload Component

Provides a smooth file upload experience:

Drag-and-drop upload for PDF and DOCX files (up to 10MB)

A two-step workflow: parse → preview → import

AI-powered extraction of resume fields

Robust error handling with clear, user-friendly feedback

## Testing

### Authentication

✓ Register a new user account

✓ Sign in using existing credentials

✓ Log out and confirm correct redirection

✓ Verify access restrictions on protected routes

### Dashboard

✓ Resume templates load and render correctly

✓ Template search functionality works as expected

✓ Category-based filtering operates correctly

✓ New resumes can be created from selected templates

### Resume Builder

✓ Contact information updates are reflected in the live preview

✓ Date picker components open and function properly

✓ “Currently working here” option behaves correctly

✓ AI-generated summaries are created successfully

✓ AI-generated experience bullet points are generated

✓ Auto-save status indicator is displayed correctly

✓ Switching templates updates the resume preview in real time

### Import / Export

✓ PDF and DOCX resumes upload successfully

✓ Parsed resume content is displayed accurately

✓ Resume export functions correctly for PDF, DOCX, and TXT formats

 ## Screenshots
  
<img width="1263" height="620" alt="Screenshot 2025-12-17 at 9 41 29 AM" src="https://github.com/user-attachments/assets/14758ae9-d6d9-4b74-886b-c3a115eef753" />

 <img width="1271" height="728" alt="Screenshot 2025-12-17 at 9 42 18 AM" src="https://github.com/user-attachments/assets/0f80c698-d94b-4b93-aef9-1adf9f2bbc17" />

<img width="1271" height="705" alt="Screenshot 2025-12-17 at 9 42 39 AM" src="https://github.com/user-attachments/assets/6e57b928-3875-49a9-a4d7-c323748a103a" />

<img width="1237" height="695" alt="Screenshot 2025-12-17 at 9 43 07 AM" src="https://github.com/user-attachments/assets/b8b572a2-f070-40d2-85f7-b3d52a50da92" />

