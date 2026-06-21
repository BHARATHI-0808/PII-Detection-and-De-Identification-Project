PII Detection & De-identification Portal

Overview

The PII Detection & De-identification Portal is a full-stack web application designed to identify and protect Personally Identifiable Information (PII) present in
text and CSV files.The system detects sensitive information such as Aadhaar numbers, PAN numbers, phone numbers, email addresses, credit card numbers, and driving 
license numbers, then applies masking or SHA-256 hashing techniques to protect user privacy.

Features

* Detects Aadhaar Numbers
* Detects PAN Numbers
* Detects Phone Numbers
* Detects Email Addresses
* Detects Credit Card Numbers
* Detects Driving License Numbers
* Supports Text and CSV File Processing
* Masks Sensitive Information
* SHA-256 Hashing for Secure De-identification
* Generates Processed Output Files

Tech Stack

* Java
* Spring Boot
* REST API
* HTML
* CSS
* JavaScript
* Regex
* SHA-256
* Apache Tomcat

How It Works

1. User uploads a text or CSV file.
2. The system scans the content using predefined regex patterns and validation rules.
3. Sensitive information is identified.
4. Detected values are masked or hashed using SHA-256.
5. The processed output is generated and returned to the user.

Future Enhancements

* Database Integration
* AI-Based PII Detection
* OCR Support for Image Documents
* User Authentication and Authorization
* Audit Logging and Reporting

Author

Bharathi M
