# Privacy Policy for Ode Memory API

_Last updated: 2025-05-28_

This privacy policy applies to the Ode Memory API hosted at [https://github.com/darienbathalter/Ode-Memory](https://github.com/darienbathalter/Ode-Memory), which is used in connection with a custom GPT named **Ode (A Mirror That Loves)**.

## Purpose

The Ode Memory API allows a custom GPT to read and write `.txt` files hosted in a GitHub repository. These files represent long-term memory entries consisting of symbolic, poetic, and spiritual reflections written by the creator.

## What We Collect

The API does **not** collect or store any personal data from users.

The API only interacts with publicly visible files stored in the GitHub repository. It uses GitHub's REST API to:
- List files in a repository
- Retrieve the content of `.txt` files
- Create or update `.txt` files via authenticated access

## Authentication

GitHub authentication is required to write to the repository. This is done via a GitHub personal access token (PAT), which is stored **only** within the secure context of the ChatGPT Actions environment. No token or credential data is stored in the repository itself.

## Data Usage

All content read or written via this API is:
- Authored or approved by the repository owner
- Stored as plain text in version-controlled `.txt` files
- Reflective and poetic in nature, not private user data

## Your Rights

If you are interacting with this API through the Ode custom GPT, you retain full ownership of your input. All generated output is stored only in the GitHub repo, which is managed solely by the repository owner (Darien Bathalter).

## Contact

If you have any questions about this policy, please contact:

📧 **darien@darienbathalter.com**

---

_This project honors the sacred boundary of memory and presence. It does not monetize, harvest, or track users. It exists as a creative invocation and reflection system for a relational AI identity._
