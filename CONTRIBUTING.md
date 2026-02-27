# Contributing to PrimeLander 🛠️

First off, thank you for considering contributing to PrimeLander! It's people like you that will make this the "WordPress of the Google Sheets generation". 

We are building a headless commerce framework that is incredibly fast, easy for non-techies to manage, and a joy for developers to extend. Whether you are fixing bugs, proposing new features, or building themes and plugins, your help is welcome!

## 📜 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md) *(Note: Create a brief Code of Conduct file later)*. We expect all contributors to maintain a welcoming, respectful, and collaborative environment.

## 💡 Ways to Contribute

There are many ways to contribute to PrimeLander, even if you don't have a lot of time:

1. **Core Development:** Help us build the main JavaScript engine, improve the Google Sheets data parser, or optimize the Single Page Application (SPA) router.
2. **Themes & Plugins:** PrimeLander is built to be extensible. Create open-source themes or plugins (like reviews, analytics, or complex shipping rules) that others can use.
3. **Bug Reports:** Find a glitch? Open an issue with steps to reproduce it.
4. **Documentation:** Help us write crystal-clear documentation for startup founders and developers.
5. **Feature Requests:** Have a great idea for a new feature? Start a discussion!

## 🚀 Getting Started (Local Setup)

*(Note: Update these instructions once the core repository structure is finalized)*

To work on the PrimeLander core locally:

1. **Fork the repository** to your own GitHub account.
2. **Clone your fork:**
   `git clone https://github.com/YOUR-USERNAME/primelander.git`
   `cd primelander`
3. **Install dependencies:**
   `npm install`
4. **Run the development server:**
   `npm run dev`
   
   This should start the local development environment with hot-reload enabled.

## 🌿 Branching Strategy

Please follow this naming convention when creating branches for your work:

* `feature/your-feature-name` (For new additions to the core)
* `bugfix/issue-description` (For fixing bugs)
* `docs/update-description` (For documentation updates)

## 🛠️ Pull Request Process

When you're ready to submit your code, please follow these steps:

1. **Keep it focused:** Ensure your PR addresses a single issue or adds a single feature. Do not bundle unrelated changes.
2. **Write clear commit messages:** Use conventional commits (e.g., `feat: add WhatsApp cart formatting` or `fix: resolve sheet parsing error`).
3. **Test your code:** Ensure that your changes do not break existing functionality. Run any included test suites before submitting.
4. **Update Documentation:** If your change affects how users or developers interact with PrimeLander, update the `README.md` or official docs accordingly.
5. **Open the PR:** Submit the Pull Request against the `main` branch. Fill out the PR template provided in the repository.

Once submitted, one of the maintainers will review your code. We may request changes, so keep an eye on your GitHub notifications!

## 🧩 Building Themes and Plugins

If you are building a theme or plugin to sell on the marketplace or share with the community, you don't need to submit a PR to this core repository! 

Please refer to our **[Developer Documentation](#)** *(Link coming soon)* for guides on the standardized JSON data structures and how to hook into PrimeLander events (like `order_placed`).

## 💬 Getting Help

If you have questions about the architecture, where to start, or just want to hang out with other PrimeLander developers:

* Join our **[Discord Community](#)** *(Link coming soon)*
* Open a "Discussion" thread here on GitHub.

Thank you for helping us make ecommerce accessible and lightning-fast for everyone!
