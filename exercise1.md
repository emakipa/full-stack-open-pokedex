# Linting, testing and building (Python application)

Some linters are combination of other tools used for logical or/and stylistic lint. Linting tool examples for Python:

* flake8
  - pyflakes for static analysis tool 
  - pycodestyle (former pep8) for code style  
* pylama
  - pyflakes
  - pycodestyle 
  - Pylint for logical and stylistic lint

Testing tools for Python:

* pytest, unittest, doctest and nose unit testing
* pytest, integration testing

Python is an interpreted language, there is no need for a build step.

# Setting up CI

Alternatives for setting up CI:

* CircleCI
* Travis CI
* GitLab CI/CD
* TeamCity
* Shippable

# Self-hosted or a cloud-based environment?

Information needed to make the decision (for example): managing infrastructure, security and trust, integrations and expense.

In general, for a small to medium software project not having any special requirements, a cloud-based solution is probably more suitable. There is no need for setting up your own system and it should be cheaper for smaller projects. Larger projects usually need resources and in larger companies there may be many projects taking advantage of it. Then a self-hosted CI setup is probably the choice.