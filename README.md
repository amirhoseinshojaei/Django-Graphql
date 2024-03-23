# Django GraphQL Schema Visualization

  This project is a Django web application aimed at providing tools for managing and visualizing database schemas, with a specific focus on GraphQL schemas. It utilizes various Django built-in apps along with a custom third-party app called "schema_graph" to achieve this functionality.

# Features

  Database Schema Management: Leverages Django's built-in apps for managing data, authentication, sessions, and more.

  GraphQL Schema Visualization: Utilizes the "schema_graph" third-party app to generate and visualize GraphQL schemas.

  User-friendly Interface: Incorporates Django's admin interface for easy data management.

  Custom URL Endpoint: Access the GraphQL schema visualization functionality via the /schema/ URL endpoint.

# Setup Instructions

  To set up this project locally, follow these steps:

  ### Clone the repository:

      git clone https://github.com/amirhoseinshojaei/Django-Graphql.git
  
  ### Install dependencies:
      
      cd Django-Graphql
      pip install -r requirements.txt

  ### Run migrations:
      
      python manage.py migrate

  ### Create a superuser (for accessing the admin interface):
      
      python manage.py createsuperuser

  ### Create a superuser (for accessing the admin interface):
      
      python manage.py runserver

Access the admin interface by navigating to http://localhost:8000/admin/ in your web browser and log in using the superuser credentials created in step 4.

To visualize the GraphQL schema, navigate to http://localhost:8000/schema/ in your web browser.


# Development

If you use this package and you like it, please encourage us by giving us a star. Of course, it is not evening in any of these cases.

Be happy and smile

# License

This project is licensed under the GPL license 

Thank you for using Django GraphQL Schema Visualization! 🚀