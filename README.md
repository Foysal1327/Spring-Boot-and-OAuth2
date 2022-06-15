# Spring-Boot-and-OAuth2
This guide shows you how to build a sample app doing various things with "social login" using OAuth 2.0 and Spring Boot.

It starts with a simple, single-provider single-sign on, and works up to a client with a choice of authentication providers: GitHub or Google.
There are several samples building on each other, adding new features at each step:

simple: a very basic static app with just a home page and unconditional login via Spring Boot’s OAuth 2.0 configuration properties (if you visit the home page, you will be automatically redirected to GitHub).

click: adds an explicit link that the user has to click to login.

logout: adds a logout link as well for authenticated users.

two-providers: adds a second login provider so the user can choose on the home page which one to use.

custom-error: adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.
