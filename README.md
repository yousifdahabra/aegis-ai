<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

>  Aegis AI empowers users to take control of their online safety with personalized, interactive tests that adapt to their responses. Featuring voice interactions, it identifies vulnerabilities and teaches effective security practices, helping users protect themselves from cyber risks.

## User Stories
### User
- **As a user, I want to take a simple quiz about online safety, so I can understand how to protect myself from cyber threats.**
- **As a user, I want to get helpful tips after the quiz, so I can learn better ways to stay safe when using the internet.**
- **As a user, I want to request a custom test from an expert, so that it matches my specific needs and challenges.** 

### Expert
- **As an expert, I want to manage all user requests and review their previous tests and results, so I can provide better insights and support.**

- **As an expert, I want to view additional user request details, such as social links, to better understand their context and needs.**

- **As an expert, I want to create custom test questions for each user based on their past test results and new information, so the tests are tailored to their improvement areas.**

### Admin
- **As an admin, I want to have the same capabilities as an expert, so I can manage user requests and tests effectively.**

- **As an admin, I want to manage users, review their profiles, and delete their accounts if necessary, to maintain a secure and organized platform.**

- **As an admin, I want to review user requests to become experts by checking their certifications or other required files, to ensure only qualified individuals are approved.**

<br><br>
<!-- Tech stack -->
<img src="./readme/title3.svg"/>

###  AegisAI is built using the following technologies:

### Flutter
The app is built with the [Flutter app development framework](https://flutter.dev/), enabling cross-platform development. This allows us to use a single codebase for mobile, desktop, and web applications.

### Laravel
The backend is powered by the [Laravel framework](https://laravel.com/), which provides a robust and secure API for handling user requests, managing authentication, and interacting with the database.

### Vue.js
For the web front-end, we use [Vue.js](https://vuejs.org/), a progressive JavaScript framework that builds responsive and dynamic user interfaces, providing seamless interactions on the web.

### MySQL
The project uses [MySQL](https://www.mysql.com/) as the relational database management system to store user data, quiz results, and security awareness progress securely.


<br><br>
<!-- UI UX -->
<img src="./readme/title4.svg"/>


> We began designing AegisAI by mapping the user flow, followed by creating wireframes and mockups. We iterated on the design until we achieved an ideal layout that ensures easy navigation and a seamless user experience.

- Project Figma design [Figma](https://www.figma.com/design/OSIpVHQafWlkto6pnhEM7t/Final-Project?node-id=0-1&t=LCd9DlfpPxIjU8cO-1)


### Mockups
  | Listen Question | Answer Question | Result
| ---| ---| ---| 
 | ![fsdaf](readme/app/speak.png) | ![fsdaf](readme/app/listen.png) | ![fsdaf](readme/app/result.png) |
### User Flow
   | Admin | 
   | ---| 
   | ![fsdaf](readme/user_flow/admin.png) | 

   | Expert | 
   | ---| 
   | ![fsdaf](readme/user_flow/securityexpert.png) | 

   | User | 
   | ---| 
   | ![fsdaf](readme/user_flow/user.png) | 

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

###  Leveraging [MySQL Workbench](https://www.mysql.com/products/workbench/), I crafted and implemented a robust, expertly designed database architecture to power seamless functionality.
| Database Diagram |
| --- |
| <img src="./readme/database/AegisAI.png" alt="Database Diagram" width="600px"> |


<br><br>


<!-- Implementation -->
<img src="./readme/title6.svg"/>


### User Screens (Mobile)

| Dynamic Test (GIF) | Voice Interaction (GIF) | AI Result (GIF) |
| --- | --- | --- |
| ![Dynamic Test](./readme/implementation/dynamic_test.gif) | ![Start Test](./readme/implementation/voice_interaction.gif) | ![AI Result](./readme/implementation/ai_result.gif)  |

| Test List  | Expert Test List | Intro Screen (GIF) |
| --- | --- | --- |
| ![Test List](./readme/implementation/test_details.gif) | ![Expert Test List](./readme/implementation/expert_test_list.jpg) | ![Login Screen](./readme/implementation/intro_screen.gif) |


### Admin Screens (Web)

| User List (Dark Mode) | User List |
| --- | --- |
| ![User List Dark](./readme/admin/user_list_dark.png) | ![User List](./readme/admin/user_list.png) |

| Test Details | Application Overview |
| --- | --- |
| ![Test Details](./readme/admin/test_details.png) | ![Application](./readme/admin/application.png) |


| Add Test (GIF) |  
| --- | 
| <img src="./readme/admin/add_test.gif" alt="Database Diagram" width="755px"> | 

<br><br>


<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

###  AI-Driven Prompt Engineering for Dynamic Cybersecurity Assessments:

- This project uses AI-based prompt engineering to create dynamic and adaptive cybersecurity assessments. By designing questions based on user responses, it provides interactive and personalized feedback to help users improve their online safety and adopt better security practices.

#### 1. Role Definition
- AI acts as a **cybersecurity expert and educator** to assess user habits.

#### 2. Question Generation
- Dynamically generated questions based on **user responses**.
- Question types include:
  - **Input (open-ended)**.
  - **Multiple choice**.
  - **Checkbox**.
  - **Voice interaction** using **Speech-to-Text (STT)**.

#### 3. Target Audience and Goal
- Designed for **everyday users** with minimal technical knowledge.
- Goal: Improve **online safety practices** and mitigate risks.

#### 4. Question Sequencing
- Engages users by varying question types.
- Avoids repetition for a smoother experience.

#### 5. JSON Response Format
- Standardized responses for questions and feedback.
- Example question JSON:
  ```json
  {
      "type_question": "<question_type_id>",
      "gpt_question_id": "<question_id>",
      "question": "<question_title>",
      "options": ["<option_1>", "<option_2>", "..."] "(if applicable)",
      "user_answer": ["<selected_option_1>", "<selected_option_2>", "..."] "(if applicable)"
   }
#### 6. Feedback and Analysis
- Provides actionable insights and a score summary in JSON.
- Example question JSON:
  ```json
   {
      "result": {
      "analysis": "<feedback_summary>",
      "score": "<user_score>%"
      }
   }
#### 7. Previous Questions
- Provides actionable insights and a score summary in JSON.
- Example input for previous questions JSON:
  ```json
   {
      {"id": "<question_id>", "type_question": "<question_type_id>", "user_answer": ["<option_1>, <option_2>"]}
   }
| Prompts |  
| --- |  
| ![GPT](./readme/gpt/gpt.png) |  


<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

###  AI Safety Solutions: Making Online Security Better with Scalable Deployment:

- This project uses AWS providing scalability, reliability, and strong performance. It runs on an EC2 instance.
- API Documentation: You can access detailed API documentation for this project through the following link [Postman](https://documenter.getpostman.com/view/15123466/2sAYQcFW1X)



### Postman Screens

| Login | Start Test (AI) |
| --- | --- |
| ![User Requests](./readme/postman/login.png) | ![Application](./readme/postman/start_test.png) |

| Answer Question (AI) | Result (AI)|
| --- | --- |
| ![Test Details](./readme/postman/answer.png) | ![Test List](./readme/postman/finish.png) |


<br><br>

<!-- Unit Testing -->
<!-- <img src="./readme/title9.svg"/>

###  Dynamic Security Design: Leveraging Prompt Engineering for Smarter Assessments:

- This project employs advanced prompt engineering to design a structured, dynamic system for cybersecurity assessments. By leveraging a JSON-based framework, it ensures seamless integration and adaptability, tailoring questions to user behaviors and responses. The design emphasizes diverse question formats, interactive voice features, and adaptive sequencing to maintain engagement and relevance. With a focus on simplicity and effectiveness, the project provides actionable insights and inspiration for addressing online safety challenges, fostering improved habits and understanding of cybersecurity risks.

<br><br> -->


<!-- How to run -->
<img src="./readme/title10.svg"/>

# AegisAI Installation Guide

> Follow these steps to set up **AegisAI** locally, from prerequisites to configuration and running the project.

---

## Prerequisites

Ensure the following are installed on your system before proceeding:

1. **Node.js** (for Vue.js frontend)
   ```sh
   npm install npm@latest -g
   ```

2. **Flutter SDK** (for the mobile application)
   - [Installation Guide](https://flutter.dev/docs/get-started/install)

3. **Laravel Framework** (for the backend)
   - [Installation Guide](https://laravel.com/docs/10.x/installation)

4. **Composer** (for PHP dependencies)
   - [Installation Guide](https://getcomposer.org/download/)

5. **Database** (e.g., MySQL)
   - Install MySQL or ensure it’s running locally.

---

## Installation

### 1. Clone the Repository
Clone the entire project, which includes the aegis-ai-web Front-end, aegis-ai-server Back-end, and aegis-ai-app Mobile app.
- Main Repo
   ```sh
   git clone https://github.com/yousifdahabra/aegis-ai.git
   ```

---

### 2. Backend Setup (Laravel)
Navigate to the `backend` folder:
```sh
cd backend
```

#### Install Dependencies
```sh
composer install
```

#### Environment Configuration
1. Copy the `.env.example` file to `.env`:
   ```sh
   cp .env.example .env
   ```
2. Update the `.env` file with your database credentials:
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=aegisai
   DB_USERNAME=root
   DB_PASSWORD=your_password
   ```

#### Generate Keys and Migrate Database
```sh
php artisan key:generate
php artisan migrate --seed
```

#### Run the Server
Start the Laravel backend:
```sh
php artisan serve
```
The backend API will be available at `http://127.0.0.1:8000`.

Repository: [Laravel Backend](https://github.com/yousifdahabra/aegis-ai-server)

---

### 3. Frontend Setup (Vue.js)
Navigate to the `frontend` folder:
```sh
cd frontend
```

#### Install Dependencies
```sh
npm install
```

#### Environment Configuration
1. Create a `.env` file in the `frontend` folder:
   ```sh
   touch .env
   ```
2. Add the backend API URL to the `.env`:
   ```env
   VUE_APP_API_URL=http://127.0.0.1:8000/api
   ```

#### Run the Frontend
Start the Vue.js development server:
```sh
npm run serve
```
The frontend will be available at `http://localhost:8080`.

Repository: [Vue.js Frontend](https://github.com/yousifdahabra/aegis-ai-web)

---

### 4. Mobile App Setup (Flutter)
Navigate to the `mobile` folder:
```sh
cd mobile
```

#### Install Dependencies
```sh
flutter pub get
```

#### Environment Configuration
1. Update the API base URL in the `lib/utils/config.dart` file:
   ```dart
   const String API_BASE_URL = 'http://127.0.0.1:8000/api';
   ```

#### Run the App
Start the Flutter development environment:
```sh
flutter run
```

Repository: [Flutter Mobile App](https://github.com/yousifdahabra/aegis-ai-app)

---
Now you’re all set to explore **AegisAI** locally! 🚀 Let me know if you face any issues during setup.

