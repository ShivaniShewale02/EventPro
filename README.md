
# EventPro

EventPro is an easy-to-use event management platform where users can view and register for various events. The platform allows users to submit their contact details (email, name, and contact number) to register for events. Admins can manage the events, view registrations, and also interact with users through a contact form.

## Features

- **Event Registration:** Users can view and register for events using their contact details (email, name, and contact number).
- **Admin Event Management:** Admins can upload new events and manage existing ones.
- **Registration Management:** Admins can view the list of users who have registered for each event.
- **User Contact Form:** Users can contact the admin through a contact form for queries or support.
- **Local Storage for Responses:** Admins can view user responses to the contact form, which are stored in local storage for easy access.

## Technologies Used

EventPro is built using the following technologies:

- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - Local Storage (for storing user responses from the contact form and registrations)

- **Backend:**
  - Java Spring Boot (for building the backend API)
  - Hibernate (for database interaction and ORM)

## Installation

To get started with EventPro, follow the steps below.

### Prerequisites

Make sure you have the following installed:

- JDK (version >= 11)
- Node.js (version >= 14)
- npm (version >= 6)
- A MySQL or PostgreSQL database

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/eventpro.git
   ```

2. Navigate to the project directory:

   ```bash
   cd eventpro
   ```

3. For the backend:
   - Open the `backend` folder and import it into your IDE (e.g., IntelliJ IDEA or Eclipse).
   - Set up your database (MySQL/PostgreSQL) and add the connection details in `application.properties` (e.g., database URL, username, password).

4. Install frontend dependencies:

   ```bash
   cd frontend
   npm install
   ```

5. Run the backend:

   In the `backend` folder, run:

   ```bash
   ./mvnw spring-boot:run
   ```

6. Run the frontend:

   In the `frontend` folder, run:

   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.

## Usage

### For Users:

- View and register for events by providing your contact details (email, name, and contact number).
- Fill out the contact form to send messages or inquiries to the admin.

### For Admins:

- Upload and manage events through the admin interface.
- View the list of users who have registered for each event.
- View user inquiries from the contact form responses stored in local storage.

## Contributing

We welcome contributions to make EventPro even better!

### Steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

EventPro is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, feel free to open an issue or contact at work.shivanishewale@gmail.com
