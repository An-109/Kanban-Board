# Kanban-board

The Candidate Search is meant for finding potentials employees for anything companies using a GitHub API and pulls users data from GitHub allowing you to choose the best of the best Candidates.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [License](#license)

---

## Features
- **Secure Login**: Authenticate users with username and password.  
- **JWT Authentication**: Use JSON Web Tokens for secure and persistent sessions.  
- **Session Management**: Expire sessions after inactivity, requiring re-authentication.  
- **Access Control**: Redirect users to the login page if they attempt to access the Kanban board without authentication.  



---

## Installation

1. **navigate to develop**:  
   - run: npm run seed
   - -run: npm run start

2. **Install dependencies**:  
    
   npm install  





## Usage

2. **Login**:  
   - Enter your username and password on the login page.  
   - Upon successful login, you'll be redirected to the Kanban board.  

3. **Session Management**:  
   - Sessions expire after a period of inactivity.  
   - Upon expiration, you’ll be redirected to the login page. 

## Deployment



- **Live Application URL**: [kanban-board](<https://kanban-board-pm5p.onrender.com/login>)
- **GitHub Repository**: [kanban-board](<https://github.com/An-109/Kanban-Board>)
