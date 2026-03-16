show all classes..ready to be copy pasted - hrms/
│
├── main.py                  # App entry point, includes routers only
│
├── core/                    # Core utilities and configs
│   ├── security.py          # Password hashing & JWT utilities
│
├── db/                      # Database connection and models
│   ├── database.py          # SQLAlchemy engine, session, Base
│   └── models.py            # All database table models
│
├── dependencies/            # Common dependencies
│   └── db.py                # get_db() dependency for DB sessions
│
├── auth/                    # Authentication feature
│   ├── api.py               # Auth API endpoints (login/register)
│   ├── service.py           # Auth business logic
│   └── schema.py            # Pydantic models for auth requests/responses
│
├── employee/                # Employee feature
│   ├── api.py               # Employee API endpoints (CRUD)
│   ├── service.py           # Employee business logic
│   └── schema.py            # Pydantic models for employee requests/responses
│
└── utils/                   # Optional utility functions
    └── helpers.py           # e.g., validation, extra helpers
