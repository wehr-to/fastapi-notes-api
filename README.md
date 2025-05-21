# fastapi-notes-api
An API-only Notes App built with FastAPI. This project demonstrates key backend principles including RESTful design, token authentication, CRUD operations, and secure API practices.

# ✅ Features
- Full CRUD for notes
- JWT token-based authentication
- OpenAPI/Swagger docs auto-generated
- API key support for protected endpoints (optional)
- Security audits baked in

# 🔓 Security Audit Checklist (Implemented or Flagged)
- Input validation (prevent XSS, SQLi)
- Secure token handling (expiration, HTTPS only)
- Rate limiting (future enhancement)
- HTTP header hardening (e.g., CORS, CSP)

# 📦 Getting Started
1. Clone the repo
2. Create a virtual environment and install dependencies
3. Set environment variables (see `.env.example`)
4. Run with `uvicorn app.main:app --reload`

# 🚀 Future Enhancements
- Rate limiting (e.g., via SlowAPI)
- Role-based access control (RBAC)
- API key support for external access
- Dockerized deployment

# 🧠 Learning Goals
- Understand REST API patterns
- Implement auth with JWT
- Harden APIs against common vulnerabilities
- Use Swagger docs effectively for API testing

## 🤝 Contributions
Pull requests are welcome! If you’d like to add features, improve security hardening, optimize code, or extend functionality, feel free to open an issue or PR. This is a learning-focused lab project, and collaboration is encouraged.

🛠️ Notes
Each script is written for clarity and easy customization.
Comments are included to explain logic and recommended tweaks.
Scripts were tested on Ubuntu 22.04 unless otherwise noted.
