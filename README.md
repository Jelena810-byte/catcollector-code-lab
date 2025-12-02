# catcollector-code-lab

# 🐾 Django CatCollector

* A simple but feature-rich Django REST API for managing cats, toys, feedings, and user accounts.
* This project demonstrates core Django concepts including models, serializers, authentication, and relationships (One-to-Many & Many-to-Many).


# 🚀 Features

* Django Models for Cats, Toys, Feedings, and User accounts

* Django REST Framework serializers & viewsets

* One-to-Many relationships (e.g., Cat → Feeding)

* Many-to-Many relationships (e.g., Cat ↔ Toy)

* Token-based Authentication for secure API access

* Full CRUD operations across all main resources


# 📦 Tech Stack

* Python 3

* Django

* Django REST Framework

* SQLite (default)


# 🔐 Authentication

* This project uses DRF Token Authentication.


# 📚 API Endpoints (Examples)
* *Resource	*Method	*Endpoint
* Cats	GET / POST	/api/cats/
* Single Cat	GET / PUT / DELETE	/api/cats/<id>/
* Toys	GET / POST	/api/toys/
* Add Toy to Cat	POST	/api/cats/<id>/add_toy/
* Feedings	GET / POST	/api/feedings/


# 🛠 Project Structure
* catcollector/
    ├── catcollector/        # Project settings
    ├── cats/                # Main app
    │    ├── models.py       # Models with 1:M & M:M relationships
    │    ├── serializers.py
    │    ├── views.py
    │    ├── urls.py
    └── users/               # Authentication


# 📄 License

* MIT License — free to use and modify.



