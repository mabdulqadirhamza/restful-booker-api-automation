# API Automation - Restful Booker

API test automation framework for Restful Booker using Playwright Test

## Description

Automated API testing suite for the Restful Booker API (https://restful-booker.herokuapp.com). This framework provides comprehensive test coverage for booking management operations including authentication, CRUD operations, search functionality, and validation scenarios. Built with Playwright Test for reliable and fast API testing.

## Features

- ✅ Complete CRUD operations testing
- 🔐 Authentication & authorization tests
- 🔍 Search and filtering capabilities
- ✔️ Input validation testing
- 🏥 Health check monitoring
- 📊 HTML test reports
- 🔄 Reusable helper utilities
- ⚡ Parallel test execution

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## Installation

```bash
npm install
```

## Project Structure

```
API_Automation_Restful_Booker/
├── tests/
│   ├── auth/              # Authentication tests
│   ├── booking/           # Booking CRUD & validation tests
│   ├── ping/              # Health check tests
│   └── utils/             # Helper functions
├── playwright.config.js   # Playwright configuration
└── package.json
```

## Running Tests

```bash
# Run all tests
npx playwright test

# Run specific test file
npx playwright test tests/booking/booking-crud.spec.js

# Run tests in headed mode
npx playwright test --headed

# Run tests with UI mode
npx playwright test --ui
```

## View Test Reports

```bash
npx playwright show-report
```

## Test Coverage

### Authentication
- Valid/invalid credential testing
- Token generation

### Booking Operations
- Create booking
- Retrieve booking
- Update booking
- Delete booking
- Search bookings
- Input validation

### Health Check
- API availability monitoring

## Configuration

Base URL and headers are configured in `playwright.config.js`:
- Base URL: `https://restful-booker.herokuapp.com`
- Default headers: JSON content-type and accept

## Tags

`api-testing` `playwright` `test-automation` `restful-booker` `javascript` `nodejs` `api-automation` `e2e-testing` `crud-operations` `rest-api` `testing-framework` `playwright-test` `ci-cd` `quality-assurance` `automated-testing`

---

[![GitHub](https://img.shields.io/badge/GitHub-mabdulqadirhamza-181717?style=for-the-badge&logo=github)](https://github.com/mabdulqadirhamza)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mabdulqadirhamza/)

⭐ If you find this project helpful, please consider giving it a star!
