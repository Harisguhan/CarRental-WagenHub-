# WagenHub

      WagenHub is a car rental system designed to provide seamless vehicle booking experiences for users while offering an easy-to-manage platform for admins. This project is built using **Spring Boot** for the backend and **React with Vite** for the frontend.

## Features

### **Admin Features:**

- Add, update, and remove cars.
- Manage user reservations and payments.
- View booking and payment history.

### **User Features:**

- Search and book available cars.
- Choose a preferred pickup date and location.
- Secure payment processing (Future improvement: **Stripe integration**).

### **Upcoming Enhancements:**

- **Stripe Payment Gateway** for secure transactions.
- **License Verification via DigiLocker** to ensure user authenticity.
- **Enhanced UI/UX** for better user experience.
- **Deployment-Ready Configuration** for production use.

## Tech Stack

### **Backend:**

- Spring Boot
- Hibernate (JPA)
- MySQL (Database)

### **Frontend:**

- React.js (Vite)
- Axios (API communication)
- React Router (Navigation)

## Installation & Setup

### **Backend Setup:**

1. Navigate to the backend directory:
   ```sh
   cd WagenHub-Backend/WagenHub-backend
   ```
2. Install dependencies and build the project:
   ```sh
   mvn clean install
   ```
3. Configure the **application.properties** file with your MySQL credentials.
4. Run the Spring Boot application:
   ```sh
   mvn spring-boot:run
   ```

### **Frontend Setup:**

1. Navigate to the frontend directory:
   ```sh
   cd WagenHub-Frontend/lastf
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm run dev
   ```

## API Endpoints (Example)

| Method | Endpoint        | Description              |
| ------ | --------------- | ------------------------ |
| GET    | /cars           | Fetch all available cars |
| POST   | /cars           | Add a new car (Admin)    |
| POST   | /users/register | User registration        |
| POST   | /users/login    | User login               |
| POST   | /bookings       | Book a car               |

## Deployment Considerations

- **Docker Support:** Future enhancement to containerize the application.
- **CI/CD Integration:** Automate deployment using GitHub Actions.
- **Cloud Deployment:** AWS, Azure or Google Cloud for production hosting.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request with your improvements.


