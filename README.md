# Stellar Burgers — Unit Tests

Unit tests for the Stellar Burgers domain model (burger builder logic).

## Tech stack
Java 11 · JUnit 5 · Mockito · JaCoCo · Maven

## What's covered
- `Burger` — set buns, add / remove / move ingredients, price calculation, receipt generation
- `Ingredient` — parameterized tests across ingredient types
- `Bun`, `IngredientType`
- Dependencies isolated with **Mockito** mocks and stubs

**Code coverage:** 100% of the `Burger` class (lines and branches), measured with JaCoCo.

## Run tests
​```bash
mvn clean test
​```
Coverage report: `target/site/jacoco/index.html`
