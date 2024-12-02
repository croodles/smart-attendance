# SMART ATTENDANCE

This project is a web application named "Smart Attendance," developed by Croodles. It provides various functionalities for managing attendance efficiently.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js**: Make sure you have Node.js installed on your machine. You can download it from [nodejs.org](https://nodejs.org/).
- **Database**: You need to have a database set up. Currently, the project uses MongoDB, but we are planning to ditch MongoDB in the future for a different database solution.

## Getting Started

Follow these steps to set up and run the application:

1. **Clone the Repository**

   Clone the repository to your local machine using the following command:

   ```bash
   git clone <repository-url>
   ```

   Replace `<repository-url>` with the actual URL of the repository.

2. **Navigate to the Project Directory**

   Change your working directory to the project folder:

   ```bash
   cd smart-attendance
   ```

3. **Install Dependencies**

   Install the required dependencies using npm:

   ```bash
   npm install
   ```

4. **Set Up Environment Variables**

   Create a `.env` file in the root of the project and add your database connection string:

   ```plaintext
   MONGODB_URI=<your-database-connection-string>
   ```

   Replace `<your-database-connection-string>` with your actual database connection string. **Note:** We are planning to ditch MongoDB, so ensure that the connection string is updated accordingly when the database changes.

5. **Run the Application**

   Start the application using the following command:

   ```bash
   npm start
   ```

   The application will start running on `http://localhost:4000/` by default.

6. **Access the Application**

   Open your web browser and navigate to `http://localhost:4000/` to access the application.

## Features

- **User Portal**: Users can log in to manage their attendance.
- **Admin Dashboard**: Admins can manage attendance records and user details.

## Troubleshooting

- If you encounter any issues, ensure that your database service is running and that the connection string in the `.env` file is correct.
- Check the console for any error messages that may provide more information about the issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Developed by Croodles.
- Inspired by the need for a modern attendance management solution.
