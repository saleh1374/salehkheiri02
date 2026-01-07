# Salehkheiri Migration v2

Migration of salehkheiri with full PostgreSQL database integration

## 📋 Project Description

This project is a migration of the original salehkheiri application with complete PostgreSQL database integration. It includes modern tech stack and best practices.

## 🛠 Tech Stack

- **Backend**: Node.js / Django / Python
- **Database**: PostgreSQL
- **ORM**: Prisma / SQLAlchemy
- **Frontend**: React / Vue.js (if applicable)
- **Deployment**: Docker / Supabase

## 📂 Project Structure

```
salehkheiri02/
├── src/              # Source code
├── database/         # Database schemas and migrations
├── config/           # Configuration files
├── docs/             # Documentation
└── README.md         # This file
```

## 🚀 Getting Started

### Prerequisites

- Node.js 16+ or Python 3.8+
- PostgreSQL 12+
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/saleh1374/salehkheiri02.git
cd salehkheiri02
```

2. Install dependencies
```bash
npm install
# or
pip install -r requirements.txt
```

3. Setup environment variables
```bash
cp .env.example .env
# Edit .env with your database credentials
```

4. Run database migrations
```bash
npm run migrate
# or
python manage.py migrate
```

5. Start the development server
```bash
npm run dev
# or
python manage.py runserver
```

## 📚 Database Schema

PostgreSQL database schema and migrations are located in the `database/` directory.

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```
DATABASE_URL=postgresql://user:password@localhost:5432/salehkheiri
NODE_ENV=development
PORT=3000
```

## 📖 Documentation

Detailed documentation is available in the `docs/` directory.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License.

## 👤 Author

**Saleh Kheiri**
- GitHub: [@saleh1374](https://github.com/saleh1374)

---

**Last Updated**: January 7, 2026
