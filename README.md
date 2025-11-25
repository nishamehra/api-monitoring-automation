# API Monitoring Automation

This project provides automated hourly monitoring for multiple Postman API collections using GitHub Actions + Newman.

## How it Works

- Add your Postman collections inside /collections
- GitHub Actions runs them every hour
- Newman executes each collection
- Results are saved inside GitHub Action artifacts
- No laptop or server needed

## Add More Collections

Add any number of files in /collections like:

collections/
├── serviceA.json
├── serviceB.json
├── serviceC.json

They will run automatically.

## Manual Trigger

Go to:
GitHub → Actions → API Monitoring → Run workflow
