Here’s a simpler version of the setup steps:

Steps to Set Up Django Project

1. Extract the ZIP File

Right-click → "Extract All" (Windows)

Use unzip project.zip (Mac/Linux)



2. Open Terminal and Navigate to Folder

cd project_folder


3. Create & Activate Virtual Environment

python -m venv venv

Windows: venv\Scripts\activate

Mac/Linux: source venv/bin/activate



4. Install Dependencies

pip install -r requirements.txt


5. Apply Database Migrations

python manage.py migrate


6. Run the Server

python manage.py runserver


7. Open in Browser

Go to http://127.0.0.1:8000/
