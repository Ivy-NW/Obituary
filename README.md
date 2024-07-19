Features
Submit obituaries with details such as name, date of birth, date of death, content, and author.
View a list of submitted obituaries.
Automatically generate unique slugs for each obituary to prevent duplication.
Styled with a serene background image and aesthetic form/table design.
SEO and Social Media Optimization features.

Technologies Used
Python
Django
HTML/CSS
SQLite (default database)
JavaScript (for form validation)

Setup
1. Clone the Repository
git clone https://github.com/Ivy-NW/obituary.git

cd obituary_management_platform

2. Create a Virtual Environment
python -m venv venv

3. Activate the Virtual Environment
On Windows:
venv\Scripts\activate

On macOS/Linux:
source venv/bin/activate

4. Install Dependencies
pip install django

pip freeze > requirements.txt

5. Run Migrations
python manage.py makemigrations python manage.py migrate

6. Create a Superuser
python manage.py createsuperuser

7. Start the Development Server
python manage.py runserver


Submit obituaries with details such as name, date of birth, date of death, content, and author.
View a list of submitted obituaries.
