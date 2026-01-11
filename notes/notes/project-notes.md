1️⃣ Project Overview

This project demonstrates how to build a secure cloud-based file storage system using Microsoft Azure Blob Storage.
It allows users to store, access, and share files securely using cloud services.

The project is inspired by real-world systems like Google Drive and OneDrive, but implemented at a beginner level.

2️⃣ Azure Services Used
🔹 Azure Blob Storage

Used to store files (blobs) in containers

Supports unstructured data (images, videos, documents)

Highly scalable and durable

🔹 Azure Storage Account

Parent resource that holds Blob Storage

Provides access keys and security configurations

🔹 Blob Containers

Logical grouping of blobs (files)

Containers can be private or public

🔹 Shared Access Signature (SAS)

Secure way to share files without exposing storage keys

Time-limited and permission-based access

🔹 Azure Portal

Used to create, manage, and monitor all resources

No code required for this beginner project

3️⃣ Key Features Implemented
📂 File Upload

Files are uploaded to Azure Blob Storage containers

Supports multiple file types (PDF, images, text files, etc.)

🗂️ File Organization

Files stored inside containers

Each container acts like a folder

🔄 File Versioning

Keeps track of older versions of a file

Helps recover deleted or overwritten files

🔐 Secure File Sharing

Files shared using SAS URLs

Access expires automatically after a set time

☁️ Cloud Accessibility

Files are accessible from anywhere using Azure Portal or URL

4️⃣ Architecture Overview
📐 Architecture Flow

User uploads a file

File is stored in Azure Blob Storage

Blob versioning tracks changes

SAS token generates secure access

Authorized users download the file

🧱 Architecture Components

Client (User)

Azure Portal

Storage Account

Blob Container

Blob (File)

5️⃣ Security Measures

Containers are private by default

No public access enabled

File sharing only via SAS

Time-bound and permission-based access

Storage keys are never exposed publicly

6️⃣ Why Blob Storage?
Feature	Benefit
Scalability	Stores unlimited data
Durability	Data replicated automatically
Cost-effective	Pay only for used storage
Secure	Integrated Azure security
Easy to use	GUI-based setup

7️⃣ Limitations (Beginner Scope)

No frontend UI (like Google Drive)

No user authentication system

Managed entirely through Azure Portal

No backend APIs

These limitations are acceptable for a beginner cloud project.

8️⃣ Learning Outcomes

Through this project, I learned:

Basics of cloud storage

How Azure Blob Storage works

Secure file sharing using SAS

Importance of versioning

Cloud resource management

Real-world cloud architecture concepts

9️⃣ Future Enhancements

Add user authentication (Azure AD)

Build frontend using HTML/CSS/React

Use Azure Functions for file handling

Automate uploads and downloads

Add logging and monitoring

10️⃣ Conclusion

This project demonstrates a fundamental understanding of cloud storage concepts using Azure.
It serves as a strong beginner-level cloud project suitable for learning, resumes, and interviews.
