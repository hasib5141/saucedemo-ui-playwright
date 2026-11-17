# SauceDemo UI Automation Framework (Playwright JS)

An end-to-end UI automation framework built with **Playwright (JavaScript)** using the **Page Object Model (POM)** design pattern for [SauceDemo](https://www.saucedemo.com/).

## Project Structure

```text
saucedemo-ui-playwright/
├── fixtures/           # Custom Playwright fixtures for POM injection
├── pages/              # Page Object classes (BasePage, Login, Inventory, Cart, Checkout)
├── test-data/          # Centralized credentials, customer info, and sort constants
├── tests/              # Isolated test specs (Q1, Q2, Q3) & Sequential suite
├── utils/              # Reusable helper functions (price parsing & math validation)
├── playwright.config.js
└── package.json