# Learnify - Online Academy

**Learnify** is an innovative online learning platform designed to make education interactive, engaging, and effective. It combines modern learning techniques and personalized support to enhance the educational experience for students, teachers, and administrators.

## Table of Contents
- Features
- Technologies Used
- Installation
- Usage
- Contributing
- License
- Contact

## Features

### For Students:
- **User Registration and Authentication**: Sign up and log in using email/password or Google.
- **Course Enrollment**: Browse and enroll in courses.
- **Interactive Learning**: Access educational content (videos, documents, quizzes).
- **Certifications**: Earn recognized certifications upon course completion.
- **Progress Tracking**: Monitor your learning progress and results.
- **Support**: Submit and track support requests.

### For Teachers:
- **Course Creation**: Create and manage courses with multimedia content.
- **Assessments**: Design quizzes and assignments for students.
- **Student Management**: Track student progress and performance.
- **Certification Issuance**: Issue certifications to students.

### For Administrators:
- **Platform Management**: Manage users, courses, and content.
- **Event Management**: Create and publish educational events.
- **Payment Management**: Handle secure transactions and subscriptions.
- **Support System**: Resolve user complaints and inquiries.

## Technologies Used
- **Backend**: Symfony (PHP framework)
- **Frontend**: JavaFX (for desktop application)
- **Database**: MySQL or PostgreSQL
- **Authentication**: Google OAuth, JWT
- **Payment Integration**: Stripe or PayPal
- **Version Control**: Git, GitHub

## Installation

### Prerequisites
- PHP (v8.0 or higher)
- Composer
- Java Development Kit (JDK) for JavaFX
- MySQL or PostgreSQL

### Steps
1. **Clone the repository**:
    ```bash
    git clone https://github.com/eyadabbaghi/learnify.git
    cd learnify
    ```
2. **Install Symfony dependencies**:
    ```bash
    composer install
    ```
3. **Set up the database**:
    - Update the `.env` file with your database credentials:
        ```bash
        DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/learnify"
        ```
    - Create the database and run migrations:
        ```bash
        php bin/console doctrine:database:create
        php bin/console doctrine:migrations:migrate
        ```
4. **Set up JavaFX**:
    - Ensure JDK is installed.
    - Open the JavaFX project in your IDE (e.g., IntelliJ IDEA or Eclipse).
    - Configure the JavaFX SDK in your IDE.

5. **Run the Symfony backend**:
    ```bash
    symfony server:start
    ```

6. **Run the JavaFX frontend**:
    - Launch the JavaFX application from your IDE or build and run it using:
        ```bash
        ./gradlew run
        ```

7. **Access the application**:
    - Backend: Open your browser and go to [http://localhost:8000](http://localhost:8000).
    - Frontend: Launch the JavaFX desktop application.

## Usage
- **Students**: Sign up, browse courses, and start learning.
- **Teachers**: Create courses and manage content.
- **Admins**: Manage the platform and handle support requests.

## Contributing
We welcome contributions! If you'd like to contribute to Learnify, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add your message here"
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, feel free to reach out:
- **GitHub**: [Learnify Repository](https://github.com/eyadabbaghi/learnify.git)
- **LinkedIn**: [Learnify LinkedIn](www.linkedin.com/in/learnify-learnify-8840bb34a)
- **Facebook**: [Learnify Facebook](https://www.facebook.com/share/15davzQ2NR/)

## Thank You!
Thank you for using **Learnify**! We hope it transforms your learning experience. 🚀
