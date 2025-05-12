![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%2300f?style=for-the-badge&logo=sql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) 

## Overview
SkillSync is an ATS-Lite platform designed to connect job seekers with relevant job openings based on their skills and the requirements of job postings. This project aims to provide a streamlined and efficient way for both individuals looking for works and employers seeking talent to find the right match - no fluff.

## Tech Stack
* **Frontend:** Javascript, React, Redux, Tailwind CSS
* **Backend:** Python (Flask), SQLAlchemy
* **Database:** SQL (e.g., PostgreSQL, MySQL, SQLite - initially SQLite for development)
* **Other:** Git for version control

## Features
* **Job Seeker:**
    * Account creation and profile management.
    * Ability to add and manage skills.
    * Browsing and searching job listings.
    * Viewing job details.
    * Submitting job applications with a cover letter.
    * Basic application tracking.
* **Employer:**
    * Account creation and company profile management.
    * Posting new job listings with skill requirements.
    * Viewing received applications.
    * Basic application status management.
## Getting Started

Follow these steps to get the project set up locally for development:

### Prerequisites

* **Python 3.x** installed on your system.
* **pip** (Python package installer) installed.
* **Node.js** and **npm** (Node Package Manager) installed (for the frontend).
* **Git** installed for version control.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/JuliaTDunc/SkillSync.git](https://github.com/JuliaTDunc/SkillSync.git)
    cd SkillSync
    ```

2.  **Set up the backend (Python/Flask):**

    ```bash
    # Create and activate a virtual environment
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    # venv\Scripts\activate   # On Windows

    # Install backend dependencies
    pip install -r requirements.txt
    ```

3.  **Set up the frontend (React):**

    ```bash
    cd frontend
    npm install
    ```
### Running the Application

1.  **Start the backend (Flask):**

    ```bash
    flask --app app.py run --debug
    ```

2.  **Start the frontend (React):**

    ```bash
    cd frontend
    npm start
    ```

## Contributing

We welcome contributions! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix (`git checkout -b feature/your-feature-name`).
3.  Make your changes and commit them (`git commit -am 'Add some feature'`).
4.  Push to the branch (`git push origin feature/your-feature-name`).
5.  Open a pull request on GitHub.

Please adhere to the project's coding standards and guidelines.

