# PlaywrightFW

A Playwright automation testing framework to get started with modern web automation testing.

## 📋 Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running Tests](#running-tests)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)

## 📖 Overview

PlaywrightFW is a test automation framework built with Playwright, designed to run end-to-end tests across multiple browsers (Chromium, Firefox, and WebKit).

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup Steps

1. Clone the repository:
```bash
git clone https://github.com/Savitapanwar/PlaywrightFW.git
cd PlaywrightFW
```

2. Install dependencies:
```bash
npm install
```

3. Install Playwright browsers:
```bash
npx playwright install
```

## ⚙️ Configuration

Configuration is managed in `playwright.config.ts`. Key settings include:
- Browser types (chromium, firefox, webkit)
- Base URL
- Timeout settings
- Parallel execution
- Reporter settings (HTML, JSON)

## 🧪 Running Tests

### Run all tests:
```bash
npm test
```

### Run tests in a specific file:
```bash
npx playwright test example.spec.ts
```

### Run tests in headed mode:
```bash
npx playwright test --headed
```

### Run tests in debug mode:
```bash
npx playwright test --debug
```

### View test report:
```bash
npx playwright show-report
```

## 📁 Project Structure

```
PlaywrightFW/
├── tests/              # Test files
│   └── example.spec.ts # Example test cases
├── playwright.config.ts # Playwright configuration
├── package.json        # Project dependencies
├── README.md          # This file
└── playwright-report/  # Test reports (generated)
```

## 📦 Dependencies

- **playwright**: End-to-end testing framework
- **@playwright/test**: Test runner and assertions

## 📝 License

MIT
