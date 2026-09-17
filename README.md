NovelHub: Modern Digital Reading Platform
NovelHub is a cross-platform digital novel reading application engineered to deliver a seamless reading experience for users while providing robust content management tools for authors and administrators. Built with a modern full-stack architecture, this project leverages Flutter for the mobile frontend and Laravel for the backend RESTful API.

Motivation & Problem Statement
The platform was built to address content fragmentation in digital reading spaces by enforcing strict Role-Based Access Control (RBAC). This architecture ensures high-quality content curation, protects platform integrity, and maintains clear operational boundaries between readers, creators, and moderators.

🛠️ Tech Stack & Architecture
Frontend (Mobile): Flutter (Dart)

Backend (REST API): Laravel 12 (PHP)

Database: MySQL

Authentication: Laravel Sanctum (Token-Based API Authentication)

Design Patterns: RESTful API Architecture, MVC Pattern, Controller-Service-Model Pattern

🎯 Key Features
👤 Reader (User)
Content Discovery: Browse and search through available novel libraries.

Personalization: Add preferred novels to a personal Favorites list.

Reading Progress: Chapter-level bookmarking to seamlessly resume reading from where you left off.

✍️ Author
Content Lifecycle Management: Full CRUD (Create, Read, Update, Delete) capabilities for managing novels and chapters independently.

🛡️ Administrator
Content Moderation: Publish or unpublish works by toggling statuses between Draft and Published.

Quality Assurance: Review drafts and remove inappropriate or policy-violating content to maintain community standards.

⚙️ Technical Highlights (For Recruiters)
Secure API Integration: Stateful and stateless API security using Laravel Sanctum to guard sensitive endpoints.

Custom RBAC Middleware: Fine-grained authorization layer segregating access permissions across Readers, Authors, and Admins.

Normalized Database Schema: Designed for relational integrity supporting complex interactions across Users, Novels, Chapters, and Favorites.

Scalable Codebase: Clean backend abstraction using a Service-Oriented Approach to streamline long-term maintainability.
