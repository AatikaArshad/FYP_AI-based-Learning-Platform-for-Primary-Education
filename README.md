# FYP_AI-based-Learning-Platform-for-Primary-Education

# AI-based Teaching Platform for Primary Students

## Overview

The AI-based Teaching Platform aims to provide accessible and engaging education for children in rural areas of Pakistan, especially targeting primary students in grades 1-5. This platform is designed to bridge the educational divide by leveraging Artificial Intelligence (AI) and Natural Language Processing (NLP) technologies. It integrates curriculum-aligned content with the Socratic method and uses Roman Urdu to facilitate learning in underserved communities.

## Problem Statement

Millions of children, especially girls, in rural Pakistan lack access to primary education due to financial, social, and cultural constraints. Existing educational platforms do not cater to the local language needs, especially for children who are unfamiliar with English. The lack of foundational skills hampers their future learning opportunities.

## Our Solution

Our solution is a child-friendly AI-based platform, **Ilm Dost**, that:

* **Engages** students using a conversational dialogue system in Roman Urdu.
* **Guides** students through grade-5 mathematics concepts using the Socratic method.
* Provides a **web-based interface** that can be accessed on low-cost devices.
* Aligns with the **Sindh Board curriculum** to provide relevant and practical learning material.

## Key Features

* **Interactive AI Tutor**: The AI system uses the Socratic method to guide students through problems step by step.
* **Curriculum Aligned**: Focuses on Grade 5 Math topics based on the Sindh Board curriculum.
* **Multilingual Support**: Uses Roman Urdu and English, making the platform accessible to a wider audience.
* **Mobile-Friendly**: A responsive UI/UX that works across different devices.
* **Trackable Progress**: Students can monitor their learning progress through the app.

## Technical Details

### Dataset Creation

The project includes a custom dataset of Socratic-style dialogues in English and Roman Urdu. This dataset will be used to fine-tune a large language model (LLM) for educational purposes.

### Tech Stack

* **Frontend**: React.js for a responsive, user-friendly interface.
* **Backend**: Node.js with Express to handle authentication, data storage, and user management.
* **AI Integration**: FastAPI for querying the fine-tuned LLM model that delivers Socratic responses.
* **Database**: A relational database (such as MySQL, PostgreSQL, or SQLite) for storing user data, chat history, and progress tracking.

### Deployment

The platform will be deployed using a MERN stack (MongoDB, Express, React, Node.js) to ensure scalability and ease of integration with other AI microservices.

## How to Run the Project Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/username/repositoryname.git
   cd repositoryname
   ```

2. **Install dependencies:**

   * Frontend:

     ```bash
     cd frontend
     npm install
     ```

   * Backend:

     ```bash
     cd backend
     npm install
     ```

3. **Start the project:**

   * Start the frontend:

     ```bash
     npm start
     ```

   * Start the backend:

     ```bash
     npm run dev
     ```

4. The application will be available at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and create a pull request with your improvements.

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature').
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Roadmap

* **Dataset Creation**: Extract math topics from textbooks and create a conversational dataset.
* **Model Training**: Fine-tune an open-source LLM using the dataset.
* **App Development**: Build the web application with a chat interface and integrate the AI model.
* **Testing & Evaluation**: Conduct trials with Grade 5 students to gather feedback and improve the platform.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

* **Socrates** for the Socratic method of teaching.
* **Meta** for the open-source LLM used in this project.
* **FastAPI** for AI model integration.
* **Relational Database** for database storage.



