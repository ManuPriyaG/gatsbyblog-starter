---
title: Features of .NET Core
description : 
date: '2019-05-17'
---


Routing:

Conventional routing - allows better SEo optimisation without working on Web server side to arrange your pages

Attribute based routing - allows us to place attributes at Controllers to define specifi roputes and actions 

Model Binding:

Client request data like form values, query string data, HTTP headers etc is tranformed to objects hence having action methods for controller defined already so as to avoid figuring out what data it has to process.

Model Validation:

.NET Core uses data annotation attributes for validating client request data mentioned above which helps client request data to be validated before posted to the server, also on server side before calling respective controller

Dependency Injection:

Allows controller classes to use services(These services need to be registered in a built-in service container called IServicesProvider explicitly) through creating constructors , also views can use DI through @inject directive



   


