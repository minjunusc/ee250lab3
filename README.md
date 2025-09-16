# Lab 3

## Team Members
Minjun Kim - githib: minjunusc

## Lab Question Answers

Question 1: Why are RESTful APIs scalable?
Because there are features that support scalability without causing communication bottlenecks that reduce performance such as statelessness (removing server load) and caching (eliminating client-server interactions).

Question 2: According to the definition of "resources" provided in the AWS article above, What are the resources the mail server is providing to clients?
Resources can be any type of data that different applications provide to their clients so in the case of mail server, the mail is the resource it is providing to clients.

Question 3: What is one common REST Method not used in our mail server? How could we extend our mail server to use this method?


Question 4: Why are API keys used for many RESTful APIs? What purpose do they serve? Make sure to cite any online resources you use to answer this question!
API keys are used for many RESTful APIs because it provides project identification and authorization. It can block anonymous traffick, control the number of calls made, and filter logs. Source: https://cloud.google.com/endpoints/docs/openapi/when-why-api-key