🔐 Recovery Code Brute-Forcer
This is a multithreaded Python script to brute-force 4-digit recovery codes for a password reset form (reset_password.php).
It simulates requests using random X-Forwarded-For headers, includes retry logic for reliability, and attempts to set a new password upon successful recovery code detection.

🚀 Features
Multithreaded brute-force (default: 50 threads)

Random IP spoofing using X-Forwarded-For

Retry mechanism using requests and urllib3 for better resilience

Automatic password reset when the correct code is found

Graceful stopping of all threads once a valid code is discovered

🛠 Requirements
Python 3.x

requests and urllib3 libraries

🧪 Usage

You can customize:

num_threads to increase or decrease parallel attempts

new_password for your desired password after reset

