# N8N-AGENTIC-AI-build-ai-agent

# n8n - Secure Workflow Automation for Technical Teams
- n8n is a workflow automation platform that gives technical teams the flexibility of code with the speed of no-code. With 400+ integrations, native AI capabilities, and a fair-code license, n8n lets you build powerful automations while maintaining full control over your data and deployments.

## Key Capabilities
- Code When You Need It: Write JavaScript/Python, add npm packages, or use the visual interface
- AI-Native Platform: Build AI agent workflows based on LangChain with your own data and models
- Full Control: Self-host with our fair-code license or use our cloud offering
- Enterprise-Ready: Advanced permissions, SSO, and air-gapped deployments
- Active Community: 400+ integrations and 900+ ready-to-use templates

## Quick Start
- Try n8n instantly with npx (requires Node.js):
  npx n8n

## Or deploy with Docker:
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
Access the editor at http://localhost:5678
