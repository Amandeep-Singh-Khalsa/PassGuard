# PassGuard

PassGuard is a secure password manager application built with **Vite** and **React**. Designed to simplify the process of managing passwords, it provides a user-friendly interface to store, generate, and retrieve strong passwords.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Features

- **Secure Storage**: Encrypts passwords for safe storage.
- **Password Generator**: Generates random, strong passwords with customizable settings.
- **User-Friendly UI**: Clean, easy-to-navigate interface built with React.
- **Real-time Notifications**: Provides feedback using `react-toastify` for actions like saving, deleting, and copying passwords.
- **Fast Performance**: Optimized using Vite, ensuring a smooth user experience.


## Installation

### Prerequisites

Ensure you have **Node.js** and **npm** installed on your system. If not, download them [here](https://nodejs.org/).

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/passguard.git
   cd passguard
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Run the Development Server**:
   ```bash
   npm run dev
   ```

4. **Access the App**:
   Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage

1. **Add a New Password**:
   - Click on "Add Password" and enter details such as account name and password.
   - Save the password to securely store it in PassGuard.

2. **Generate a Password**:
   - Use the built-in password generator to create a strong, random password.
   - Customize the length and types of characters (e.g., numbers, symbols, letters).

3. **View and Manage Passwords**:
   - Access stored passwords securely.
   - Options to copy, edit, or delete passwords with a single click.

4. **Receive Real-time Feedback**:
   - Toast notifications appear for key actions, confirming successful storage, deletion, or password copying.

## Technologies Used

- **Vite**: Fast, opinionated frontend build tool for optimized performance.
- **React**: JavaScript library for building user interfaces.
- **React Toastify**: For smooth and customizable toast notifications.
- **CSS**: Styled to create a responsive and user-friendly UI.

