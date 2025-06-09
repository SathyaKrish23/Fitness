# Fitness

# ⚙️ Installation & Setup

Follow these steps to download and run the project:

1. **Download the Project**
   - Go to the repository page
   - Click the green **“Code”** button → **“Download ZIP”**

2. **Extract the ZIP File**
   - Unzip it to your preferred location

3. **Navigate to the Project Folder**
   > cd fitness_api

4. ** Run the project
  > python manage.py runserver

5. List of APIs in the project

GET: /classes/ – list of classes
POST: /book/ – with JSON body (class_id, client_name, client_email)
GET: /bookings/?email=... – get bookings by email as query param
