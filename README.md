# Recipe-App-API
Recipe-API Project
![image](https://github.com/Abenezerjr/Recipe-App-API/assets/106702572/98820ba0-4ce5-40f9-b3d8-4ef44c4ec6e8)
Swagger UI

# Food Recipe API
This is a robust Food Recipe API built using Python, Django, Django Rest Framework, Swagger, DRF, and Docker.
## Overview
The Food Recipe API provides endpoints for managing food recipes, including creating, updating, deleting, and retrieving recipes and tag and image.
Users can perform various actions such as create account,update account, register,verified using Token  and also adding new recipes, updating existing ones, 
and browsing through a collection of diverse recipes.

## Features

- **Adbvanced api concept:** Create, Retrieve, Update, Delete (CRUD) operations for recipes
-**Authentication:** and authorization mechanisms using Token Create , delete register User using Token Drf python module
-**Swagger:** documentation for API reference.
-**Containerized:** with Docker for easy deployment and management
-**TAG:** add tag for recipe
-**Ingredients:** add ingreadient for food recipe
-**images :** add food image
-**compatibilty :** it work all plateform website and  mobile aplications
-** it is fully functional but note host**  
-**And MORE...** 
## Installation

1. Clone the repository:

    ```bash
    git clone [https://github.com/Abenezerjr/Recipe-App-API.git]
    cd Recipe-App-API /
    ```

2. Create a virtual environment:

    ```bash
    python3 -m venv env
    source env/bin/activate  # Activate the virtual environment
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. install Docker:

    ```bash
    https://docs.docker.com/desktop/install/windows-install/ 
    ```

5. Start the development server:

    ```bash
    docker compose up
  
    ```
6. in order to use docker:

    ```bash
    docker-compose run --rm app sh -c "python manage.py test" # for test the code
    docker-compose run --rm app sh -c "flake8" # correctly indented
    
    ```    

6. Access the application in your browser at `http://localhost:8000/api/docs`.

## Usage

1. Create a superuser to access the admin panel:

    ```bash
    docker-compose run --rm app sh -c "python manage.py createsuperuser"
    ```

2. Visit `http://localhost:8000/admin` and log in using the credentials created in the previous step.
   
3. Start managing recipe and tag and image through the admin interface.

## Contributions

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](Abenezerjb).

## Acknowledgements

Special thanks to [Django](https://www.djangoproject.com/) and [python](https://www.python.org/) ,[swagger](https://swagger.io/), [Django rest api](https://www.django-rest-framework.org/) for their fantastic frameworks.

---

Feel free to modify and expand upon this README to better reflect the features

