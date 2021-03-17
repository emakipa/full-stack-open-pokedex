### Linting, testing and building (Python application)

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

### Setting up CI

Alternatives for setting up CI:

* CircleCI
* Travis CI
* GitLab CI/CD
* TeamCity
* Shippable

### Self-hosted or a cloud-based environment

Information needed to make the decision (for example): 

* managing infrastructure
  - CI/CD systems require resources and the health of the services has to be maintained
* security and trust
  - focus on the security of CI/CD systems in needed. Trust in the external provider needs to evaluated
* integrations
  - how easily different solutions integrate with other tools or systems that are used
* expense
- price of managed CI/CD and self-hosted service

In general, for a small to medium software project not having any special requirements, a cloud-based solution is probably more suitable. There is no need for setting up your own system and it should be cheaper for smaller projects. Larger projects usually need resources and in larger companies there may be many projects taking advantage of it. Then a self-hosted CI setup is probably the choice.