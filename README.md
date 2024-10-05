# TDD / BDD Final Project: eCommerce Product Catalog Microservice


This repository contains the template to be used for the Final Project for the Coursera course **Introduction to TDD/BDD**.

## Overview

In this final project, I created a microservice for the product catalog backend of an eCommerce application. Administrators can use the application’s user interface to effectively manage the product catalog.

The project is divided into two parts:

### Part 1: REST API Development

In the first part of the project, I implemented Test Driven Development (TDD) principles to create a REST API that allows users to perform the following operations on products:

- Create
- Read
- Update
- Delete
- List products by various attributes

I utilized the provided starter code, which includes the implementation and tests for the **Create** functionality. This code serves as a template for creating my own repository on GitHub.

### Part 2: Behavior Driven Development (BDD) Scenarios

In the second part of the project, I wrote BDD scenarios to test the administrative user interface to ensure it behaves as expected.

**Setup Requirements:**
- Python 3.8
- Selenium
- Behave

I created a steps file to load background data from my BDD scenarios into the service before executing each scenario. Additionally, I developed a feature file containing the BDD scenarios to verify the expected behavior of the user interface.

**CRUD Functions:**
In addition to the basic CRUD functions, the microservice allows searching for products by:
- Category
- Availability
- Name

## Tasks

In this project I used good Test Driven Development (TDD) and Behavior Driven Development (BDD) techniques to write TDD test cases, BDD scenarios, and code, updating the following files:

```bash
tests/test_models.py
tests/test_routes.py
service/routes.py
features/products.feature
features/steps/load_steps.py
```

## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

John Rofrano, Senior Technical Staff Member, DevOps Champion, @ IBM Research

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
