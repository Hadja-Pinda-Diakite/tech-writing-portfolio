# Developer Quickstart Guide: local Environment Setup
This guides walks you through setting up a standard web development on your local machine using Node.js, Git, AND VS code.
## Prerequisites
Before you begin,  install the following before:
* **Operating System:** Windows 10/11, macOS, or Linux
* **Terminal access:** Command Prompt, PowerShell, or macOS Terminal
---

## Step 1: Install Node.js

You need Node.js to run JavaScript application locally

1. download the **LTS (Long Term Support)** installer from nodejs.org.
2. Run the installer, accepting the default configuration settings.
Verify the installation by running the following command in your terminal:

`node -v`
> **Expected Output:** `v18.xx` or higher.

---

## Step 2: Clone the Starter Project
Clone the official starter template repository to your local computer: 

`git clone https://github.com/exemple/starter-app.git`
`cd starter-app`

---

## Step 3: Install Dependencies & Run

1. Install project dependencies: `npm install` 

2. Start the local development server: `npm start`

3. open your browser and navigate to `http://localhost:3000` to view the application live.

---

### Troubleshooting

| Issue | Cause | Solution |
| :--- | :--- | :--- |
| `command not found: node` | The system can not find the Node.js | Restart your terminal or reinstall Node.js |
| `Port 3000 in use` | Another app is using the port | Run `PORT=3001 npm start` |
