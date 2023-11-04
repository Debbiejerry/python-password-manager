# python-password-manager

## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Disclaimer](#disclaimer)

## About
The Password Manager is a simple Python command-line application that allows users to create accounts with usernames and securely store hashed passwords. Users can also log in using their credentials and verify their identity.

## Features
1. Account creation: Users can create an account by providing a username and a password. The password is securely hashed using the SHA-256 algorithm before storage.
2. Login: Users can log in by providing their username and password, and the system will verify their identity by comparing the stored hashed password with the provided password.

## Getting Started
To get started with the Password Manager, follow these instructions:

### Prerequisites
- Python 3.12.0 64 bit
- Text Editor [Vscode preferred with Python Extension installed from Microsoft]
  
### Installation
1. Clone the repository:
   git clone https://github.com/yourusername/password-manager.git
2. Change the project directory
   cd password-manager
3. Run the apllication
   python password_manager.py

## Usage
Run the application, and you will be prompted with the following options:

Enter 1 to create an account.
Enter 2 to log in.
Enter 0 to exit the application.
If you choose to create an account (1), you will be asked to enter your desired username and password. Your password will be securely hashed and stored.

If you choose to log in (2), you will be prompted to enter your username and password. The system will verify your identity by comparing the hashed password.

You can exit the application by entering 0.

## Contributing
Contributions to this project are welcome. To contribute, please follow these guidelines:

1 Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Test your changes.
5. Create a pull request with a clear description of your changes.

## License
This project is licensed under the MIT License. You can find the full license text in the LICENSE file.

## Disclaimer
This project is a simple demonstration of a password manager and was created following a tutorial by [W. J. Pearce](https://www.youtube.com/watch?v=tbhYxd2sfAE&t=2s) on YouTube. I would like to express my appreciation for the tutorial and encourage everyone to subscribe to W. J. Pearce's YouTube channel for more insightful content.
Please note that this project is not intended for production use. Always use a trusted and well-audited password manager for secure password storage.
