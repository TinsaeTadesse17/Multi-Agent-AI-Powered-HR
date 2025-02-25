# Candidate Management System Frontend

This repository contains the frontend for a candidate management system, built with Next.js, React, and Material-UI (MUI). The application enables HR or recruitment teams to manage and track candidate screening and interview processes.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)

---

## Overview

The Candidate Management System Frontend is designed to integrate with a NestJS backend. It allows users to:

- List all job applicants retrieved from the backend.
- Display applicant details, including CV and current status.
- Handle status updates through popups for screening and interview processes.

---

## Features

- Next.js & React for client-side rendering and routing.
- Material-UI (MUI) for a modern, responsive user interface.
- TypeScript for type safety and better developer experience.
- Popup Modals for screening and interview status updates.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/candidate-management-frontend.git
   ```
2. Navigate to the project folder:
   ```bash
    cd candidate-management-frontend
   ```
3. Install dependencies:
  ```bash
  npm install
  ```
4. Usage
  Ensure the NestJS backend is running and configured to serve data at the endpoint your frontend expects.

  Start the development server:

  ```bash
  npm run dev
  ```
  This will launch the application at http://localhost:3001.

Open your browser to:
http://localhost:3001
You can then navigate to the job applicants page (for example, /jobs/123 if you have a job with ID 123).
