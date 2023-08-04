# API Test Automation | Karate DSL

## Description
Karate DSL api test automation example

## Prerequisites
- Java 12 and above
- Maven

## Installation
```bash
$ mvn install
```

## Running the Tests

#### 1. Run all tests
```bash
$ mvn clean test
```

#### 2. Run tests for a specific feature e.d users
```bash
$ mvn clean test -Dtest=UsersRunner
```

#### 3. Run tests for tagged scenarios e.g @smoke
```bash
$ mvn clean test -Dkarate.options="--tags @Smoke"
```

#### 4. Run tests ecxept tagged scenarios e.g @smoke
```bash
$ mvn clean test -Dkarate.options="--tags ~@Smoke"
```

# Public API 
```
https://reqres.in
```