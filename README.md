# Nabenik's Enterprise Java basic test

Hi and welcome to this test. As many technical interviews, main test objective is to establish your actual Enterprise coding skills, being:

* Java knowledge
* DDD knowledge
* General toolkits, SDK's and other usages
* Jakarta EE general skills

This repository is a [GitHub template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template), from which you have to create your own repository, fix the source code if required, add your answers to readme file, commit the solutions/answers to YOUR copy.

This document is structured using [GitHub Markdown Flavor](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code).

## General questions

1. How to answer these questions?

> Like this

Or maybe with code

```kotlin
fun hello() = "world"
```

2. Please describe briefly the main purpose for the following Jakarta EE specs, also add in your answer http links to actual implementations. Is this project using all specs?

- EJB
- Servlet
- CDI
- JAX-RS

3. Which of the following is an application server?

* Open Liberty
* Apache TomEE
* Eclipse Jetty
* Eclipse Glassfish
* Oracle Weblogic

4. In your opinion, what's the main benefit of moving from Java 11 to Java 17?

5. Is it possible to run this project (as is) over Java 17? Why?

6. Is it possible to run this project with GraalVM Native? Why?

7. How do you run this project directly from CLI without configuring any application server? Why is it possible?

## Development tasks

To solve this questions please use Gitflow workflow, still, your answers should be in the current branch.

Please also include screenshots on every task. You don't need to execute every task to submit your pull request but feel free to do it :).

0. (easy) Show your terminal demonstrating your installation of OpenJDK 11

1. (easy) Run this project using an IDE/Editor of your choice

2. (medium) Execute the movie endpoint operations using curl, if needed please also check/fix the code to be REST compliant

3. (medium) Write an SPA application using Angular, the application should be a basic CRUD that uses Movie operations, upload this application to a new Bitbucket repo and include the link as answer

4. (medium) This project has been created using Java EE APIs, please move it to Jakarta EE APIs and switch it to a compatible implementation (if needed)

5. (hard) Please identify the Integration Test for `MovieRepository`, after that implement each of the non-included CRUD methods

6. (hard) Please write the Repository and Controller for Actor model, after that implement each of the CRUD methods using an Integration Test

7. (hard) This project uses vanilla Java EE for Database Persistence, please integrate Testcontainers with MySQL for testing purposes

8. (nightmare) This source code includes only Java EE APIs, hence it's possible to port it to [Open Liberty](https://openliberty.io/). Do it and don't port Integration Tests 

