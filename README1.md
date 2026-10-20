# W3D2_n8n_selfhosting
VPS hosting purchased and n8n is activated 

# n8n Workflow Automation on Hostinger VPS

## Overview

This project documents the deployment and configuration of **n8n**, an open-source workflow automation platform, on a Hostinger VPS.

## Objectives

- Learn workflow automation using n8n.
- Integrate applications using APIs and webhooks.
- Explore AI agent and RAG workflow automation.
- Run workflows on a self-hosted VPS.

## Technology Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Hostinger VPS | Server hosting |
| Docker | Container deployment |
| Ubuntu Linux | Server operating system |
| HTTPS | Secure web access |

## Architecture

`User → Browser → HTTPS → Hostinger VPS → Docker → n8n`

## Deployment Steps

1. Purchase a Hostinger VPS plan.
2. Deploy the n8n VPS template.
3. Verify that the n8n Docker container is running.
4. Access the n8n web interface.
5. Create and test workflows.

## Project Structure

```text
n8n-project/
├── README.md
├── workflows/
│   └── sample-workflow.json
└── docs/
    └── deployment-notes.md
```

*Note: This is an example structure. Create these folders only if you use them.*

## Security Considerations

- Use HTTPS for remote access.
- Protect login credentials and API keys.
- Never commit passwords, tokens, or private environment files to GitHub.
- Back up workflows and persistent data regularly.

## Learning Outcomes

- Self-hosted workflow automation
- Docker container management
- API and webhook integration
- Foundations of AI workflow automation

## References

- [n8n Documentation](https://docs.n8n.io/)
- [Hostinger VPS Hosting](https://www.hostinger.com/vps-hosting)
- [Docker Documentation](https://docs.docker.com/)

## Author

Your Name

## License

Specify a license if you intend to distribute this project.

