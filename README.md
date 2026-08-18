# 🔐 PDF Lock

**PDF Lock** is a secure desktop application designed to make protecting and managing PDF documents simple, reliable, and convenient.

Instead of forcing users to remember a different password for every protected PDF, PDF Lock provides a centralized account-based system where users can securely manage all of their locked documents and their associated passwords from one place.

## ✨ Why PDF Lock?

Managing multiple password-protected PDF files can quickly become inconvenient. PDF Lock solves this problem by combining **PDF encryption, password management, and centralized document organization** into a single desktop application.

With PDF Lock, users only need to remember their **account username and account password**. Once logged in, they can access their protected PDFs and the passwords associated with them.

## 🚀 Key Features

### 🔒 Lock PDF Files
Protect a PDF with a password directly from the application.

The original document is **never modified**. PDF Lock creates a separate copy and applies the protection to that copy, keeping the original file completely untouched.

### 🔓 Unlock PDFs
Unlock protected PDF copies whenever needed using the password stored for the corresponding document.

### 🗂️ Centralized PDF Management
View all protected PDFs from a single dashboard.

Users can easily see:
- PDF file names
- Locked documents
- Associated passwords
- Document information
- Available actions

### 🔑 No Need to Remember Every PDF Password
Each protected PDF can have its own password, while the user only needs to remember their **PDF Lock account credentials**.

The application keeps the document-password relationship organized so users don't have to memorize dozens of different passwords.

### 🛡️ Original File Protection
PDF Lock follows a **copy-first approach**:

```text
Original PDF
     │
     ▼
Create a Copy
     │
     ▼
Protect the Copy
     │
     ▼
Locked PDF
```

Your original PDF remains unchanged and available exactly as it was.

### 👤 User Accounts
Each user has their own account and can access their protected documents through their personal account.

### 📊 Secure Dashboard
A dedicated dashboard provides a clear overview of the user's protected PDF collection, making it easy to find and manage documents.

### 🔎 Easy Organization
Search and manage protected documents without manually browsing through folders or trying to remember where each locked copy was stored.

## 🎯 Designed for Simplicity

PDF Lock is built around three principles:

**Lock. Unlock. Protect.**

The interface is designed to be simple enough for everyday users while providing the functionality required to manage multiple protected PDF documents efficiently.

## 🔐 Security Philosophy

PDF Lock is designed with document safety in mind.

The application separates the **original document** from the **protected copy**, reducing the risk of accidentally modifying or damaging the user's original PDF.

Account authentication provides a single access point for managing the user's protected documents.

> **Your original PDF stays untouched. Your protected copy handles the security.**

## 🖥️ Application Flow

```text
        ┌─────────────────┐
        │     Sign In     │
        │ Username +      │
        │ Account Password│
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │    Dashboard    │
        │                 │
        │  My Locked PDFs │
        └────────┬────────┘
                 │
        ┌────────┴─────────┐
        ▼                  ▼
   🔒 Lock PDF        🔓 Unlock PDF
        │                  │
        ▼                  ▼
  Create protected    Open protected
       copy                PDF
```

## 🧩 Main Components

PDF Lock can be organized around several core components:

- **Authentication System** — user account management
- **PDF Protection Engine** — password-protecting PDF copies
- **PDF Unlocking System** — opening protected documents
- **Document Manager** — tracking protected PDFs
- **Password Manager** — associating passwords with documents
- **Dashboard** — centralized document management
- **File System Manager** — safely creating and organizing protected copies

## 🎨 User Experience

The application uses a clean, modern visual identity based around a soft blue color palette and the **codili** brand.

The interface emphasizes:

- Minimal and intuitive controls
- Clear visual feedback
- Consistent blue security-themed icons
- PDF and lock visual elements
- Simple navigation
- Professional desktop-app aesthetics

## 📌 Example Use Case

Imagine a user has:

```text
Project.pdf
Invoice.pdf
Thesis.pdf
Confidential.pdf
Research.pdf
```

Instead of remembering five different passwords:

```text
Project.pdf      → password #1
Invoice.pdf      → password #2
Thesis.pdf       → password #3
Confidential.pdf → password #4
Research.pdf     → password #5
```

the user simply signs into PDF Lock with their account and accesses their protected documents from the dashboard.

Each PDF can still have its own password while the application keeps everything organized.

## 🛠️ Project Status

**PDF Lock is under development.**

The project is being developed as a desktop application with a focus on secure PDF protection, simple document management, and a professional user experience.

## 🔮 Future Improvements

Possible future features include:

- Password generation
- Password strength indicators
- Secure password storage improvements
- PDF preview
- Document categories
- Advanced search and filtering
- Backup and restore
- Activity history
- Automatic protected-copy organization
- Improved authentication security
- Optional cloud synchronization

## ⚠️ Security Notice

PDF Lock is intended to provide convenient PDF protection and document management. For production use, sensitive credentials and PDF passwords should be stored using appropriate cryptographic protection and secure credential-storage practices rather than plain text.


## Requirements
- Python 3.6 or higher
- PyQt5
-pikepdf
- (Add any other libraries you used, e.g., PyPDF2, cryptography, etc.)

## How to Run
1. Install the requirements:
pip install -r requirements.txt

2. Run the application:
python main.py

## Download
Download the ready-to-run `.exe` file from the [Releases]page.

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
### 🔐 PDF Lock

**Lock. Unlock. Protect.**

Developed by **codili** — *We Code Your Success.*
