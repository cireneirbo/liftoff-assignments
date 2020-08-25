# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview

A web service that sends emails/tweets/other to users when their specified alert settings are met. Uses CoinMarketCap's API to detect percentage changes in cryptocurrencies over a specified time-frame. (e.g. "Bitcoin has had a +4% change since 4p.m. EST, today! New value is ${x}.") May add metals, stocks, and other financials to alert options as well. Uses Auth0 to set up accounts/login, and then a database to store users' settings. 

Advantage to using the service will be that a crypto hodler will be notified of any drastic changes in their cryptocurrencies of choice. Typically, hodlers are known for checking the price of assets frequently, and this will limit the need for such frequent sanity checks.

### Features

<ol>
  <li>User login system with Auth0. User has a home page with their selected assets returning live data for them.</li>
  <li>User can add preference customizations which save to a database. Will be a separate page.</li>
  <li>User can delete preference customizations which are removed from a database. Will be a separate page.</li>
</ol>


### Technologies

* Java
* Spring Boot
* MySQL
* Hibernate
* Thymeleaf templates
* JavaScript
* Express/Angular
* (Likely need) PHP
* Twitter API
* CoinMarketCap API
* Auth0

### What I'll Have to Learn

* PHP/sending emails
* protecting secret keys
* how to utilize Auth0

### Project Tracker

https://trello.com/dreamofelectricsheep
