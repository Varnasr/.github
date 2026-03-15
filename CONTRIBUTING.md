# Contributing to OpenStacks

Thank you for considering a contribution. OpenStacks is built by and for development practitioners, and contributions from the field are what make it useful.

## What We're Looking For

- **Scripts and tools** that solve real problems in development research, MEL, or program evaluation
- **Sample data** (synthetic or anonymised) that lets others test scripts without needing their own datasets
- **Bug fixes** and improvements to existing code
- **Documentation** that makes tools easier to understand and adopt
- **Notebooks** showing worked examples with real analysis workflows

## Before You Start

1. **Check existing issues** — someone may already be working on it
2. **Open an issue first** for large changes — let's discuss the approach before you build
3. **One thing per PR** — keep pull requests focused on a single change

## How to Contribute

1. Fork the repository
2. Create a branch (`git checkout -b your-feature`)
3. Make your changes
4. Test your code — if the repo has tests, make sure they pass
5. Commit with a clear message describing what and why
6. Push and open a pull request

## Code Standards

**Python:**
- Python 3.8+ compatible
- Use pandas idioms (vectorised operations over loops)
- Include docstrings for public functions
- Add type hints where they improve clarity

**R:**
- Use tidyverse conventions where appropriate
- Include roxygen-style comments for functions
- Test with `testthat` if the repo has a test suite

**Stata:**
- Include header comments with purpose, inputs, and outputs
- Use local macros over globals
- Label variables and values

**All languages:**
- Keep dependencies minimal — don't add a package for something you can write in 5 lines
- Include a usage example in comments or docstring
- Use the repo's existing data formats and conventions

## Sample Data Guidelines

- Never commit real respondent data, even if "anonymised"
- Generate synthetic data that preserves realistic distributions and relationships
- Include a data dictionary or inline comments explaining each variable
- Use CSV as the default format unless there's a strong reason not to

## Documentation

- Update the README if your change adds new files or capabilities
- Keep language direct — say what the tool does, not what it aspires to do
- Don't add documentation for features that don't exist yet

## What Happens Next

1. A maintainer will review your PR, usually within a few days
2. We may suggest changes — this is collaborative, not adversarial
3. Once approved, your contribution gets merged to main

## Not Sure Where to Start?

Look for issues labelled `good first issue` or `help wanted`. Or open a discussion — we're happy to suggest tasks that match your skills.

---

Part of [OpenStacks for Change](https://openstacks.dev). Created by [Varna Sri Raman](https://on-web.link/varna).
