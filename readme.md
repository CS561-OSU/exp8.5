# Exploration 8.5 Code: SpeedScore API Test Suites
This repository demonstrates best practices for constructing test suites for a back-end web API. We focus in Exploration 8.5 on the routes for creating a new user account. Our testing approach includes both integration and unit tests. The `main` branch contains the code for the SpeedScore back-end app without tests. The `tests/register-user` branch includes the code developed in Exploration 8.5.

## Lab 8 setup (for GitHub Classroom starter repos)

Run these commands inside your Lab 8 starter repository:

```bash
git remote add exp85 https://github.com/CS561-OSU/exp8.5.git
git fetch exp85 tests/register-user
git restore --source exp85/tests/register-user -- tests package.json package-lock.json .env.example
```

If the `exp85` remote already exists, skip `git remote add exp85 ...`.

Create your local environment file from the template:

```bash
cp .env.example .env
```

PowerShell equivalent:

```powershell
Copy-Item .env.example .env
```

Then edit `.env` with your local values. Do not commit `.env`.