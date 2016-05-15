# System Designer

## What is System Designer ?

No matter the frameworks you use and the code you write, the most important is the model that you define to create your application. System Designer helps you to design this model and to generate the classes and components to build your application.

#### Design your application with UML

If you look at the different JavaScript frameworks on the market, you will notice that they all have their own way to define a model, generally only with code.

System Designer uses [UML](http://www.uml.org), a standard, to define your model. So you probably already know how to create a model in System Designer even if you have never run it.

The definition of the model is stored on a JSON format called [MSON](https://system-runtime.readme.io/docs/design-your-model#section-mson). With [MSON](https://system-runtime.readme.io/docs/design-your-model#section-mson) you can define types, classes, one to one / one to many relationships and multi inheritance between classes.

#### Code the behavior of your model

Once you have created your model, System Designer generates the skeletons of all your methods. You only have then to add your code to implement them.

System Designer provides you helpers to manage your components. You can easily navigate threw components to create your application.

#### Create components graphically

There is no need to code to instantiate a component. Create a component in System Designer is like creating a document in a NoSQL Database.

In fact, System Designer acts as an ODM (Object-Document Mapper) to manage your components as NoSQL Documents.

#### Run your application

You can run your application directly from System Designer and then export it to HTML, JSON or a Node.js module.

Because you have defined a model for your application, a [Dynamic Type Check](https://en.wikipedia.org/wiki/Type_system#DYNAMIC) is done on every action of your application. All warnings are send and shown in System Designer.

## Documentation

* [Installation](https://system-designer.readme.io/docs/install-system-designer)
* [Build](https://system-designer.readme.io/docs/build-system-designer)
* [Quick Start](https://system-designer.readme.io/docs/quick-start)
* [Documentation](https://system-designer.readme.io/)

## Licence

Copyright © 2016 Erwan Carriou

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License. 