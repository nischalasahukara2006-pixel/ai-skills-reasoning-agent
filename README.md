# Multi-Agent Smart Troubleshooting Assistant (Reasoning Track)

## Problem Solved
When developers or enterprise users hit complex cloud ecosystem orchestration errors (such as `AADSTS50020`), the root cause is often difficult to pinpoint, leading to broken developer workflows and configuration drift. This project solves that by building a multi-step reasoning agent workflow to automatically diagnose structural identity errors and safely apply fixes.

## Features & Functionality
- **Multi-Step Reasoning Loop**: Segregates concerns between a root-cause diagnostic agent and a tactical remediation agent.
- **Model Context Protocol (MCP) Interoperability**: Implements the Azure MCP pattern to tie LLM decisions directly to secure, auditable cloud operations.

## Technologies Used
- **Microsoft Foundry** (LLM Backbone)
- **Microsoft Agent Framework** (Multi-agent routing pipeline)
- **Azure MCP Pattern** (Secure tool gateway execution)
- **Python** & **GitHub Copilot** (Development velocity)
