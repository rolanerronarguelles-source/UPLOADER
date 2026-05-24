Uploader

A secure, scalable, and production-ready Photo Album Management application built with Django and Python. This system utilizes Class-Based Views (CBVs) for efficient CRUD operations, enforces strict Role-Based Access Control (RBAC), integrates Cloudinary for cloud media management, and is optimized for deployment on Render using a PostgreSQL database.

 Live Links & Deliverables
Live Application URL: https://uploader-uxk1.onrender.com

Source Code Repository: https://github.com/rolanerronarguelles-source/UPLOADER.git

Key Features
Class-Based Views (CBVs): Built using Django's structured generic views (ListView, DetailView, CreateView, UpdateView, DeleteView) to ensure a clean, maintainable, and DRY (Don't Repeat Yourself) codebase.

Role-Based Access Control (RBAC): Integrated with Django's native authentication framework.

Standard Users: Can view public albums, create their own albums, and manage their own photos.

Album Administrators: Possess full administrative overrides, including deleting inappropriate content and managing user permissions.

Cloudinary Integration: Fully configured for cloud-based media storage. Local storage is disabled to ensure stateless production execution.

Production-Ready Security: Protected against common vulnerabilities using secure environment variables via django-environ, strict ALLOWED_HOSTS, and CSRF configurations.

🛠️ Tech Stack & Architecture
Backend Framework: Django (Python)

Database: PostgreSQL (Provisioned via Render)

Media Storage: Cloudinary CDN

Deployment Platform: Render

WSGI Server: Gunicorn
