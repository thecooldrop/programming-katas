# Introduction

This repository is a collection of exercises for familiarizing yourself with the Spring and Spring Boot ecosystem.
The exercises are designed to familiarize yourself with individual features of Spring and Spring Boot.
Solutions are not provided, because the idea is to have you do it yourself.
I ensure you though, that I have checked that each exercises comes with a solution, which you can learn about from official Spring documentation or tutorials.

# Katas

## 1. Familiarize yourself with Spring Initialzr

Create a new Spring Boot prouject using Spring Initializr.
Inspect what each of the buttons in the Spring Initializr web UI does.
Note there are at least four buttons to play around with.

To complete this exercise load the generated project into IDE of your choice and try to run it.


Note: Depending on selected modules, the application may fail to start. That is okay.

## 2. Create a REST API returning a constant string

Create a new REST controller with single endpoint returning a constant string.
The endpoint should be accessible via HTTP GET request to `/hello` path.
The value returned by endpoint should be `Hello World!`.

To test your code use `curl` or Postman.
Using curl you can test your code by running `curl -X GET http://localhost:8080/hello`.

Learning questions:
- What dependencies did you need to add to add to your Spring application?
- What annotations did you have to use to create a REST controller?
- What annotations did you have to use to create a REST endpoint?
- Did you stumble upon other similar annotations, which were not originally what you were looking for? 
  If so, what were they, and what did they do?
  What is the difference between them and the annotations you used?

