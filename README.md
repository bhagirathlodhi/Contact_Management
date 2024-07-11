# Smart Contact Manager

Smart Contact Manager is a web application built using Java 8 and Spring Boot. It allows users to manage their contacts efficiently. Users can sign up, sign in, edit their profiles, and add multiple contact numbers.

## Features

- User Registration (Sign-Up)
- User Login (Sign-In)
- Edit User Profile
- Add, Edit, and Delete Contacts
- View List of Contacts

## Technologies Used

- Java 8
- Spring Boot
- Spring Security
- Hibernate (JPA)
- MySQL
- Thymeleaf (for templating)
- Bootstrap (for UI)

## Getting Started

### Prerequisites

- JDK 8 or higher
- Maven
- MySQL Server

### Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/yourusername/smart-contact-manager.git
    cd smart-contact-manager
    ```

2. **Configure the Database**
    - Create a MySQL database named `contact_manager`.
    - Update the `application.properties` file with your MySQL database configuration.

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/contact_manager
    spring.datasource.username=root
    spring.datasource.password=rootpassword
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.show-sql=true
    spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5Dialect
    ```

3. **Build and Run the Application**
    ```sh
    mvn clean install
    mvn spring-boot:run
    ```

4. **Access the Application**
    Open your browser and navigate to `http://localhost:8080`.

## Usage

### User Registration (Sign-Up)
- Navigate to the Sign-Up page.
- Fill in the required details such as username, email, password, and confirm password.
- Click on the "Sign Up" button to create a new account.

### User Login (Sign-In)
- Navigate to the Sign-In page.
- Enter your email and password.
- Click on the "Sign In" button to log in to your account.

### Edit User Profile
- Once logged in, navigate to the "Profile" page.
- Edit your personal details such as name, email, and password.
- Click on the "Update Profile" button to save changes.

### Manage Contacts
- Navigate to the "Contacts" page.
- **Add Contact**: Click on the "Add Contact" button, fill in the contact details (name, phone number, email, etc.), and click "Save".
- **Edit Contact**: Click on the "Edit" button next to a contact, update the contact details, and click "Save".
- **Delete Contact**: Click on the "Delete" button next to a contact to remove it.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgements

- Thanks to the Spring Boot and Java communities for their excellent documentation and support.

---

Feel free to customize this README file according to your project's specifics. Happy coding!
