 "MALWARE SCANNER WEB"

Welcome to the Malware Scanner Web project.
This tool helps test and improve online defensive security through three main features:

File Scanner → Detect possible malware in uploaded files

URL Scanner → Identify dangerous or suspicious websites

Password Checker → Check the strength and security of passwords

1. Main Features
File Scan :

Users can upload files (.exe, .pdf, .txt, .zip, etc.).

The system analyzes the file and calculates its hash to compare with a malware database.

It then clearly shows the scan result, the type of threat (if any), and the risk level.

URL Scan :

Users paste a URL into a field.

The system checks the site’s reputation and detects phishing or malware URLs.

The result shows whether the link is safe or dangerous, with more details.

Password Checker :

Users enter a password in a secure field.

The system:

Checks password complexity (length, character types, etc.)

Verifies if the password has been leaked in data breaches

Gives a score out of 100 and personalized tips to improve it

PDF Report Export :

After each scan (file, URL, or password), users can download a PDF report containing:

Detailed scan results

Risk level or password score

Security recommendations

Date and digital signature

2. User Interface :

The application has a structured and interactive interface, bringing multiple cybersecurity tools together on one platform.

On the main page, users see three main sections:

File Scan – “Choose file” button + analysis result display

URL Scan – Input field + “Analyze” button → instant result

Password Checker – Secure input + score display + tips + crack time estimate

Example Outputs :

--- File Scan Result ---
Name: example.pdf
Status: No malware detected

--- URL Scan Result ---
URL: http://malicious-site.com
Status: Dangerous — Phishing detected

--- Password Check ---
Password: azerty123
Score: 15/100 (WEAK)
Tips: Add uppercase letters, symbols, and increase the length.

3. Tools & Technologies :

Python → Main programming language

Flask / Django → Backend framework for the web interface

HTML / CSS / JS → Responsive user interface

ReportLab / FPDF → Generate PDF analysis reports

MongoDB → Database for storing users, scan history, and malware signatures

4. How to Use :

Open the app in your browser → http://localhost:5000

Create a personal account to access the tools

Use one of the three modules (File / URL / Password)

View the detailed results displayed under each form

Download a PDF report if needed
