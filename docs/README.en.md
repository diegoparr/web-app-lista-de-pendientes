How to run the project 🚀
Follow these steps to get the project up and running on your local machine.

1. Clone the repository
Open the terminal and clone the project with the following command:

Bash

git clone https://github.com/diegoparr/web-app-lista-de-pendientes.git
2. Configure the virtual environment
Go to the project folder and create a virtual environment to isolate the dependencies:

Bash

cd web-app-lista-de-pendientes
python -m venv venv
3. Activate the virtual environment
Activate the virtual environment according to your operating system:

On Windows:

Bash

venv\Scripts\activate
On macOS or Linux:

Bash

source venv/bin/activate
4. Install dependencies
Install all the necessary libraries for the project using the requirements.txt file:

Bash

pip install -r requirements.txt
5. Run the database (Django)
Run the migrations to create the database:

Bash

cd src/proyecto
python manage.py makemigrations
python manage.py migrate
6. Start the server
Finally, start the development server to see the application:

Bash

python manage.py runserver
Once the server is active, you can access the application at the following address:

http://127.0.0.1:8000/