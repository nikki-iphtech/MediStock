# MediStock

**MediStock** is an educational Android application for inventory management, developed as a learning project. The application consists of two separate apps: a **User app** and an **Admin app**, with backend APIs built using Flask and hosted on PythonAnywhere.

## Features

### User App

- **User Registration & Login**: Simple account creation and authentication.
- **Admin Approval**: Admin approval required for new accounts. Users can register, but an admin must approve their accounts before they can access the application.
- **Order Management**: Users can create orders for products listed by the admin. Orders are categorized into pending, approved, and disapproved tabs based on admin actions.
- **Sales Management**: Users can sell products and maintain a comprehensive sales history.
- **Profile Management**: Users can update their account details such as name, email, and phone number, etc.

### Admin App

- **User Management**: Admins can add new users, view all approved users, manage pending user requests, and disapprove users.
- **Product Management**: Admins can add, view, and manage products available for orders.
- **Order Approval**: Admins can approve or disapprove orders placed by users.
  
## Technology Stack

### User and Admin Apps

- **Kotlin**: The modern programming language for Android development.
- **Jetpack Compose**: Android’s modern toolkit for building native UI.
- **Retrofit**: A type-safe HTTP client for Android and Java.
- **Navigation Component**: Handle all app navigation.
- **Preference Data Store**: Store key-value pairs in a more efficient way.

### APIs

- **Flask**: A lightweight WSGI web application framework in Python.

### Architecture

- **MVVM (Model-View-ViewModel)**: Ensuring a clear separation of concerns and a clean architecture.

## Learning Experience

Developing MediStock has been an amazing learning experience. Here are some of the key things I learned:

- **API Development with Flask (Python)**: I learned how to create and manage APIs, allowing the app to communicate with the server effectively.
- **API Integration with Retrofit**: I figured out how to connect the app to APIs, making network requests and handling responses smoothly.
- **MVVM Architecture**: I understood how to structure the app using the Model-View-ViewModel architecture, making the code cleaner and easier to manage.
- **Jetpack Compose**: I explored building user interfaces with Jetpack Compose, creating responsive and dynamic UI elements.
- **Logic Building**: I improved my problem-solving skills by designing and implementing complex features like user registration, admin approval, order management, and sales tracking.

This project has been full of learning opportunities and has helped me grow as a developer.

## Getting Started

### API Hosting

The backend APIs for MediStock are hosted on PythonAnywhere. Ensure to update your base URL in the Retrofit configuration to point to the hosted API.

### Prerequisites

- **Android Studio**: The official IDE for Android development.
- **Python 3.x**: Required for running the Flask API.

### Installation

#### User and Admin Apps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Muhammad-Noman59/MediStock.git
    ```

2. **Open in Android Studio**:
    - Open the `UserApp` or `AdminApp` folder in Android Studio.

3. **Build and Run**:
    - Build the project and run it on an emulator or a physical device.

#### APIs

1. **Navigate to the API Directory**:
    ```bash
    cd MediStock/APIs
    ```

2. **Set Up a Virtual Environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install Flask**:
    ```bash
    pip install flask
    ```

4. **Run the Flask App**:
    ```bash
    flask run
    ```

Gif Preview :

![Funny GIF](https://i.imgflip.com/9x3xi9.gif)

![Descriptive alt text](https://i.imgflip.com/9x3xn0.gif)

![My GIF](https://imgflip.com/gif/9x3xts.gif)

![Funny GIF](https://i.imgflip.com/9x3xxt.gif)

![Funny GIF](https://i.imgflip.com/9x3y4e.gif)

![Demo](https://i.imgflip.com/9x3y8c.gif)

![Funny GIF](https://i.imgflip.com/9x3ylz.gif)

![My GIF](https://i.imgflip.com/9x3yv1.gif)

![Funny GIF](https://i.imgflip.com/9x3z33.gif)

![Funny GIF](https://i.imgflip.com/9x3z8o.gif)

![Funny Meme GIF](https://i.imgflip.com/9x3zbn.gif)

![Funny GIF](https://i.imgflip.com/9x3zel.gif)


