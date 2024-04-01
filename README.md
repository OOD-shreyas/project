Night Owls - Isaac Acosta, Cayden Haas, Eddie Brito

CSCI 428

# **OwlGuard**

It is a password manager application designed to securely store your passwords.

## **Implementation:**

Focuses on the verification process.

- Two-Factor Authentication (2FA): Implementing 2 layers of authentication to verify the identity of users and devices.
  - Password
  - QR Code - leads to a passcode
    
- Using Authentication Apps: Add an account by scanning the QR code.
  - Examples: Duo, Google Authenticator, Authy, and etc..
  - Dynamic Passcode Generation: Continuously generating new authentication codes for all devices and endpoints.

## **Design:**

- Login page
  - Username
  - Password
  - 2FA Code (shows up after 2FA is enabled)
  - Login button
    
- Home page
  - Password Log
    - Add password
    - Show password
    - Delete password
  - Update/Enable 2FA
    - Generates QR Code
    - Set 2FA Code
  - Logout button
