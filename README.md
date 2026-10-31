# Enterprise AI

AI prototypes for enterprise support and IT operations, designed and built by [Srinivasa Karri](https://www.linkedin.com/in/srinivasakarri/).

**Live site:** https://enterpriseaiassistant.github.io/

## The prototypes

Four prototypes that work together across enterprise support and automation: the Enterprise Assistant provides guided support, the Team Assistant equips the support team, the Onboarding Assistant prepares users, and Ticket Intake Automation streamlines backend operations.

| Prototype | What it does | Page |
|---|---|---|
| Enterprise Assistant | Answers application-specific questions, guides troubleshooting, and escalates unresolved issues through controlled ticket creation in Jira or ServiceNow. | [enterprise-assistant.html](enterprise-assistant.html) |
| Team Assistant | Answers support questions from the team's own documentation, surfaces resolution steps, and cites the source document so every answer can be verified. | [team-assistant.html](team-assistant.html) |
| Onboarding Assistant | Guides users through setup steps and required policies so onboarding is completed in a structured, consistent way. | [onboarding-assistant.html](onboarding-assistant.html) |
| Ticket Intake Automation | Reads incoming emails, classifies issues, routes requests to Jira or ServiceNow, and automates ticket creation, notification, and assignment. | [ticket-intake-automation.html](ticket-intake-automation.html) |

Each prototype page covers the problem, the solution, the technology stack and integration approach, and use case and architecture diagrams. The Enterprise Assistant and Onboarding Assistant pages link to working demos.

## How the site is built

- **Static site:** plain HTML, CSS, and JavaScript in each page, with no frameworks, external libraries, or build step.
- **Interactive features:** JavaScript adds a slide-style presentation mode and zoomable diagrams.
- **AI-assisted development:** the content, code, and diagrams were created with ChatGPT. Recent updates are made with OpenAI Codex through branches and pull requests.
- **Hosting:** GitHub Pages, published from the `main` branch.

## Repository layout

```
index.html                     Home page with links to each prototype
enterprise-assistant.html      Enterprise Assistant prototype page
team-assistant.html            Team Assistant prototype page
onboarding-assistant.html      Onboarding Assistant prototype page
ticket-intake-automation.html  Ticket Intake Automation prototype page
privacy-policy.html            Privacy policy for the Enterprise Assistant prototype
*.png                          Use case, architecture, and process flow diagrams
```

## Run it locally

Open `index.html` in a browser, or serve the folder and visit http://localhost:8000:

```
python3 -m http.server 8000
```

## Notes

These are prototypes for demonstration, not production systems. They use sample data only. Please don't enter sensitive, confidential, or production data into the demos.

## Contact

Srinivasa Karri · [LinkedIn](https://www.linkedin.com/in/srinivasakarri/)
