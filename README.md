# music_shop_study_project
:books: Just a study project from "Django by Example" book to learn different features and technologies

Albeit this is a pretty standart shop-project to learn Django, this is my favorite one because it involves a lot of django features and 
third-party modules/applications to significantly extend shops functionality.

### Here is a list of technologies used:

+ Django`s **session framework** to keep information about customers carts
+ **Context processors** to display a cart at every page
+ **Celery and RabbitMQ** to perform asynchronous tasks
+ **Flower** to monitor asynchronous tasks and its statistics
+ **Braintree** to create a **payment gateway**
+ **WeasyPrint** to render PDF-invoices from HTML-pages
+ **Internalization framework** to translate a site to different languages using **gettext**,  **Rosetta**, **django-parler**
+ **Localization** and **django-localflavor** to display/validate locale-specific formats of dates/distances/currency etc.
+ **redis** to build a recommendation engine
