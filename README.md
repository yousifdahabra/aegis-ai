<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

>  Aegis AI empowers users to take control of their online safety with personalized, interactive tests that adapt to their responses. Featuring real-time voice interactions, it identifies vulnerabilities and teaches effective security practices, helping users protect themselves from cyber risks.

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
| Start Test  | Listen Question | Answer Question | Result
| ---| ---| ---| ---| 
| ![Landing](readme/app/starttest.png)  | ![fsdaf](readme/app/speak.png) | ![fsdaf](readme/app/listen.png) | ![fsdaf](readme/app/result.png) |

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

| Intro Screen (GIF) | Start Test (GIF) | Expert Requests |
| --- | --- | --- |
| <img src="./readme/implementation/intro_screen.gif" alt="Intro Screen" width="300px" height="600px"> | <img src="./readme/implementation/start_test.gif" alt="Start Test" width="300px" height="600px"> | <img src="./readme/implementation/expert_request.jpg" alt="Expert Requests" width="300px" height="600px"> |

| Test List | Expert Test List | Login Screen |
| --- | --- | --- |
| <img src="./readme/implementation/test_list.jpg" alt="Test List" width="300px" height="600px"> | <img src="./readme/implementation/expert_test_list.jpg" alt="Expert Test List" width="300px" height="600px"> | <img src="./readme/implementation/login.jpg" alt="Login Screen" width="300px" height="600px"> |

| Input Question | Interactive Question | Multiple Select Question |
| --- | --- | --- |
| <img src="./readme/implementation/input_question.jpg" alt="Input Question" width="300px" height="600px"> | <img src="./readme/implementation/intractive_question.jpg" alt="Interactive Question" width="300px" height="600px"> | <img src="./readme/implementation/multible_select_question.jpg" alt="Multiple Select Question" width="300px" height="600px"> |

| Single Select Question |  |  |
| --- | --- | --- |
| <img src="./readme/implementation/single_select_question.jpg" alt="Single Select Question" width="300px" height="600px"> |  |  |

### Admin Screens (Web)

| User Requests | Application Overview | Test Details |
| --- | --- | --- |
| ![User Requests](./readme/admin/user_request.png) | ![Application](./readme/admin/application.png) | ![Test Details](./readme/admin/test_details.png) |

| Test List | User List (Dark Mode) | User List |
| --- | --- | --- |
| ![Test List](./readme/admin/test_list.png) | ![User List Dark](./readme/admin/user_list_dark.png) | ![User List](./readme/admin/user_list.png) |

| Add Test (GIF) |  |  |
| --- | --- | --- |
| <img src="./readme/admin/add_test.gif" alt="Database Diagram" width="755px"> |  |  |

<br><br>


<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

###  Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project uses advanced prompt engineering techniques to optimize the interaction with natural language processing models. By skillfully crafting input instructions, we tailor the behavior of the models to achieve precise and efficient language understanding and generation for various tasks and preferences.

<br><br>

<!-- AWS Deployment -->
<!-- <img src="./readme/title8.svg"/>

###  Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br> -->

<!-- Unit Testing -->
<!-- <img src="./readme/title9.svg"/>

###  Dynamic Security Design: Leveraging Prompt Engineering for Smarter Assessments:

- This project employs advanced prompt engineering to design a structured, dynamic system for cybersecurity assessments. By leveraging a JSON-based framework, it ensures seamless integration and adaptability, tailoring questions to user behaviors and responses. The design emphasizes diverse question formats, interactive voice features, and adaptive sequencing to maintain engagement and relevance. With a focus on simplicity and effectiveness, the project provides actionable insights and inspiration for addressing online safety challenges, fostering improved habits and understanding of cybersecurity risks.

<br><br> -->


<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up AegisAI locally, follow these steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [example](https://example.com)
2. Clone the repo
   git clone [github](https://github.com/your_username_/Project-Name.git)
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

Now, you should be able to run AegisAI locally and explore its features.