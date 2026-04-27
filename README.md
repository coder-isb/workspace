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


    ====
    Run this with your team 👇

Today I’ve got some interesting **FACT or MYTH** questions for you.
Your job: decide quickly—no overthinking 😄

---

**1. “The first website ever created is still online today.”**
Vote: ✅ Fact
Why: Created by Tim Berners-Lee (the scientist who invented the web in 1989), the original site is still accessible.

---

**2. “More training data always improves model performance.”**
Vote: ❌ Myth
Why: After a point, **data quality matters more than quantity**—noisy or biased data can reduce accuracy.

---

**3. “Python is named after the snake because its creator liked reptiles.”**
Vote: ❌ Myth
Why: It’s named after Monty Python (a famous 1970s comedy group known for absurd humor), not snakes.

---

**4. “Temperature in LLMs controls randomness of output.”**
Vote: ✅ Fact
Why: It’s a parameter in AI models—higher values increase randomness, lower values make outputs more predictable.

---

**5. “Dark mode reduces battery usage on all smartphones.”**
Vote: ❌ Myth
Why: It mainly helps on **OLED screens** (where pixels turn off individually), not LCDs.

---

**6. “Serverless means no servers to manage at all.”**
Vote: ❌ Myth
Why: Servers still exist—you just don’t manage them directly; cloud providers handle infrastructure.

---

**7. “The ‘@’ symbol in email addresses was chosen because it was rarely used in names.”**
Vote: ✅ Fact
Why: Ray Tomlinson (the engineer who sent the first email in 1971) chose it to clearly separate user and machine.

---

**8. “Bluetooth is named after a Viking king.”**
Vote: ✅ Fact
Why: Named after Harald Bluetooth (a 10th-century king who united tribes—like Bluetooth connects devices).

---

**9. “Observability is the same as monitoring.”**
Vote: ❌ Myth
Why: Monitoring shows **what failed**, observability helps understand **why it failed** using logs, metrics, and traces.

---

**10. “Vector databases are only useful for AI applications.”**
Vote: ❌ Myth
Why: Also used in **search engines, recommendation systems, and fraud detection** for similarity matching.

---

Let’s see who gets the most right 👀

