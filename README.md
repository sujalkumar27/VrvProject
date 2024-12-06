# VrvProject
About the Project:
This is an inventory management system that uses a JavaFX frontend, a Java API, and MySQL for a database. It allows a store's inventory staff to log in securely with a custom role based access control system. Product inventory, customer invoices, and product category are the main features of this project.

Depth of Project:
Authentication:
This project's authentication system involves a java class called Authenticator that verifies the user's credentials with an XML document.

Authorization:
Authorization in this project is handled by a java class called Authorizer, which is an implementation of a custom role-based access control system. Every CRUD action in this application initiates the Authorizer class to verify that the user has proper privileges. The privilege and role information is stored in a JSON file, which is accessed only by the Authorizer class.

