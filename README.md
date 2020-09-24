# graphql-demo
A graphql demo application


TEST TASK:
------------------------------
we use node.js, graphQL, Apollo Server and Typescript.
Use these technologies to create an application that has two lists:

fruit
vegetables

For each of the lists, endpoints must be created to allow:

displaying the list
displaying a single list item
addition
editing
component removal

An authorization and authentication mechanism must also be created, including three roles:

Admin - can do anything
FruitJohn - can do anything in the list of fruits, while vegetables can only display a list and add new ones
VegetarianMary - on the list of vegetables can do anything, while fruits can only display the list and add new ones

In case of authentication errors, endpoint should return an error message and the corresponding http status code (e.g. 403)

List data can be saved in any place - database, file, online system, ect.
Also prepare a tool to test your solution, it can be a simple Front (we won't take into account the quality of its code), or instructions on how to do a test in Apollo playground.
