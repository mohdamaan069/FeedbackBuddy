# Feedback Buddy

Welcome to Feedback Buddy! This project is designed to help gather feedback from students on various courses throughout their semesters. By providing a platform for students to submit their feedback, instructors can gain valuable insights into the quality of their courses and areas for improvement.

## Features
- **User-Friendly Interface**: The frontend is built using HTML and CSS to provide a simple and intuitive user experience.
- **Backend Processing**: PHP is utilized for backend processing, handling form submissions, and interacting with the MySQL database.
- **Database Storage**: All feedback entries are stored securely in a MySQL database, ensuring data integrity and accessibility.
- **XAMPP Server**: Feedback Buddy is designed to run on the XAMPP server environment, making it easy to set up and deploy locally.

## Getting Started
To get started with Feedback Buddy on your local machine, follow these steps:

1. **Clone the Repository**: Clone this GitHub repository to your local machine using the following command:
    ```
    git clone https://github.com/your-username/feedback-buddy.git
    ```

2. **Set Up XAMPP**: Download and install XAMPP if you haven't already. You can download XAMPP from [here](https://www.apachefriends.org/index.html).

3. **Start XAMPP Services**: Start the Apache and MySQL services in XAMPP.

4. **Import Database**: Import the provided MySQL database schema `feedback_buddy.sql` into your MySQL server using phpMyAdmin or any other MySQL management tool.

5. **Configure Database Connection**: Navigate to the `backend` directory and open the `config.php` file. Update the database connection details (`$dbHost`, `$dbUsername`, `$dbPassword`, `$dbName`) with your MySQL credentials.

6. **Run the Application**: Open your web browser and navigate to `http://localhost/feedback-buddy` to access Feedback Buddy.

## Usage
- Students can visit the Feedback Buddy website and provide feedback for their courses by filling out the feedback form.
- Instructors can then view and analyze the feedback collected through the admin interface.

## Contributing
We welcome contributions from the community to improve Feedback Buddy. If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a new Pull Request.

## License
This project is licensed under the [MIT License].

## Acknowledgements
- We would like to thank all contributors to this project.
- Special thanks to the organizers and participants of the HackTheChain 2.0 hackathon for their support and feedback.
  
Thank you for using Feedback Buddy! If you have any questions or feedback, feel free to contact us.
