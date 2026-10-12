 Diasease-Management
Disease Management SystemA web-based Disease Management System built using Python and Django to help track, manage, and organize patient data and disease records efficiently.   FeaturesPatient & Disease Tracking: Securely store and manage patient medical records and disease information.Django Admin Integration: Built-in, user-friendly administrative panel for managing database entries.Modular Structure: Organized utilizing Django apps for scalability and maintenance.Project StructurePlaintextDisease management system/
│
├── .venv/                   # Python virtual environment
├── manage.py                # Django's command-line utility for administrative tasks
└── [project_name]/          # Main Django project configuration (settings, urls, wsgi, etc.)
Getting StartedFollow these instructions to set up and run the project locally on your machine.PrerequisitesPython (version 3.10 or higher recommended)pip (Python package manager)Installation & SetupClone the repository (or navigate to your project directory):Bashcd "Disease management system"
Activate the virtual environment:On Windows (Command Prompt / PowerShell):Bash.venv\Scripts\activate
On macOS / Linux:Bashsource .venv/bin/activate
Install dependencies:(If you have a requirements.txt file):Bashpip install -r requirements.txt
Apply database migrations:Bashpython manage.py migrate
Run the development server:Bashpython manage.py runserver
Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view the application.UsageTo access the admin panel, create a superuser account:Bashpython manage.py createsuperuser
Then navigate to [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) and log in with your credentials.
