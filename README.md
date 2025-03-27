# Dark-Web-Email-Breach-Checker

Overview:
The Dark Web Email Breach Checker is a cybersecurity tool that helps users find out if their email has been leaked in known data breaches. It uses the HaveIBeenPwned API and ensures privacy by hashing the email before checking it.

Features:
- Checks if an email has been part of a data breach.
- Uses SHA-1 hashing for security.
- Communicates with HaveIBeenPwned API.
- Provides a simple and easy-to-use interface.

How It Works:
1. The user enters an email.
2. The email is converted into a SHA-1 hash.
3. The first 5 characters of the hash are sent to the API.
4. The API returns possible breaches related to the email.
5. If the email is found in any breach, the user is notified.

Technology Used:
- Python for programming
- Gradio for user interface
- Requests for API communication
- Hashlib for email hashing
- HaveIBeenPwned API for checking breaches

Privacy and Security:
- The tool does not store emails.
- It uses SHA-1 hashing to protect user data.
- Only a part of the hash is sent to the API to maintain privacy.

Future Improvements:
- Adding more APIs to improve data breach tracking.
- Sending email alerts when new breaches are detected.
- Including more security features like multi-factor authentication guidance.

Developed By: [Meenakshi A]


