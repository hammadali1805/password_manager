# Password Manager

The Password Manager is a Python-based desktop application that allows users to securely store and manage their passwords for various platforms. It uses encryption to protect sensitive information and provides features for adding, fetching, and changing passwords.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Contributors](#contributors)

## Features

- **Secure Password Storage**: The Password Manager securely stores your passwords using encryption, ensuring that your sensitive information remains confidential.

- **Platform Management**: You can add and manage passwords for various platforms, making it easy to organize and retrieve your login credentials.

- **Password Retrieval**: Retrieve your saved passwords for a specific platform by providing the platform's name and the secret key.

- **Change Secret Key**: Change the secret key used for encryption to enhance security.

## Installation

1. Clone or download the project from the [GitHub repository](https://github.com/hammadali1805/password_manager).

2. Install the required Python packages:
   ```bash
   pip install pywin32
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## How to Use

### Home Screen

- Launch the application to access the home screen, which provides an overview of the software's functionality and options.

### Add Password

- Click the "Add" option in the menu to add a new password for a platform.

- Enter the platform name, password, confirm password, and the current secret key.

- Click "Submit" to securely store the password.

### Fetch Password

- Click the "Fetch" option in the menu to retrieve a saved password.

- Enter the platform name and the current secret key.

- The password will be displayed if it exists for the specified platform.

### Change Secret Key

- Click the "Settings" option in the menu to change the secret key used for encryption.

- Enter the old key, new key, and confirm the new key.

- Click "Change" to update the secret key.

## Contributors

- [Hammad Ali](https://github.com/hammadali1805) - Project Lead and Developer
---

Thank you for using the Password Manager! If you have any questions or encounter any issues, please feel free to [create an issue](https://github.com/hammadali1805/password_manager/issues) on the GitHub repository. Your security and convenience are our top priorities.
