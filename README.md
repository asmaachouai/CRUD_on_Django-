Django Models and Database Operations 
Introduction
This README provides instructions and examples for creating Django models with various types of relationships, querying model objects with filters, and performing delete and update operations.

Concepts Covered
Django Models:

Django models represent database tables and define the structure of data stored in them. Models are Python classes that inherit from Django's models.Model class.
Relationships:

Django supports different types of relationships between models:
One-to-One (1:1): Each record in one model is associated with exactly one record in another model.
One-to-Many (1:N): Each record in one model can be associated with multiple records in another model.
Many-to-Many (N:M): Records in one model can be associated with multiple records in another model, and vice versa.
Querying Model Objects with Filters:

Django's QuerySet API allows filtering model objects based on specific criteria. Filters are applied using methods like filter(), exclude(), and get().
Delete and Update Operations:

Django provides methods for deleting and updating model objects. This includes delete() for deleting objects and update() for updating multiple objects simultaneously.
