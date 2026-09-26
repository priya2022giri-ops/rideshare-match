# RideShare Match

A verified carpool-matching app for students and coworkers who live near each other and travel the same route to campus or work. Built for CSCE 3444 (Software Engineering), Group 5.

## Team

| Member | Role |
|---|---|
| Priya Giri | Auth & Identity Lead |
| Rupesh Bista | Matching & Routing Lead |
| Sudip Sharma | Messaging & Payments Lead |
| Joshua Vadalas | Platform & QA Lead |

## What it does

- Sign in with a verified school/work email, or SSO (Google Workspace / Okta)
- Post a commute route and get matched with nearby riders/drivers on the same schedule
- See a verified driver badge (vehicle make/model/plate)
- Chat with a match and confirm a carpool
- Automatic in-app cost-splitting between rider and driver
- Live GPS trip tracking with ETA sharing once a carpool starts
- Rate a trip and reach a safety/escort support line if needed

Full requirements are in the project's SRS document (see `/docs`).

## Tech Stack

- **Frontend:** [fill in once decided — e.g. React Native / Flutter for mobile, React for web]
- **Backend:** [fill in — e.g. Node.js / Express, or Django]
- **Database:** [fill in — e.g. PostgreSQL]
- **Auth:** School/work email verification + SSO (Google Workspace, Okta)

## Project Structure
​```
/docs         SRS, Production Plan, and other project documents
/client       Frontend application
/server       Backend API and services
/README.md    You are here
​```


## Getting Started

```bash
# Clone the repo
git clone <repo-url>
cd rideshare-match

# Install dependencies (once set up)
cd server && npm install
cd ../client && npm install

# Run locally (once set up)
npm run dev
```

## Branch Workflow

One feature branch per task from the Production Plan, named `feature/<task-id>-<short-description>`, e.g. `feature/T5-user-profile-service`. Open a pull request into `main` when a task is ready for review.

## Task Tracking

See the team's Trello board (linked in the course Information Sheet) for current task status, and the Production Plan spreadsheet for the full task breakdown.

## License

Class project for CSCE 3444 — University of North Texas.
