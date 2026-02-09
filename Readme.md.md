# VulnShop - Web Application Security Lab

An intentionally vulnerable e-commerce web application for security education and training.

## ⚠️ Security Warning

**This application contains intentional vulnerabilities for educational purposes only.**
- DO NOT deploy to production
- DO NOT use real personal data
- DO NOT attempt to exploit systems outside this lab environment
- FOR EDUCATIONAL USE ONLY

## Overview

VulnShop is a realistic e-commerce web application designed to teach web application security concepts through hands-on exercises. It includes intentionally vulnerable code that students must identify, test, and fix.

## Features

- **Realistic E-commerce UX**: Shop, cart, checkout, orders, support, forum
- **Intentional Vulnerabilities**:
  - Cross-Site Scripting (XSS): Reflected, Stored, DOM-based
  - SQL Injection simulation using sql.js (SQLite in WASM)
  - Business logic flaws (client-side validation, coupon tampering)
- **Security Education Focus**:
  - Safe vs vulnerable implementations side-by-side
  - Detailed lab instructions and templates
  - Realistic testing scenarios

## Lab Structure

### Phase 1: Reconnaissance & Mapping
- Map input sources and output sinks
- Identify data persistence locations
- Create source-to-sink map

### Phase 2: Testing & Documentation
- Test XSS vulnerabilities
- Test SQL injection simulation
- Document findings in provided templates

### Phase 3: Fix Implementation
- Fork repository and implement fixes
- Replace vulnerable code with secure alternatives
- Submit pull request with explanations

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/your-org/vulnshop-lab.git
cd vulnshop-lab