# Python Django CRM Web Application  

## Overview  
This is a Customer Relationship Management (CRM) web application built using **Django** (Python) and **MySQL** as the database. The frontend styling is done using **Bootstrap** for a responsive and clean UI.  

## Features  
- ✅ User authentication and role-based access  
- ✅ Customer management (add, update, delete, and search customers)    
- ✅ Responsive design with Bootstrap  

## Technologies Used  
- 🖥 **Backend**: Python, Django  
- 🗄 **Database**: MySQL  
- 🎨 **Frontend**: HTML, CSS, Bootstrap  
- 🔗 **Others**: Django ORM, Django Authentication  

## Installation  

### Prerequisites  
- 🐍 Python (>=3.0)  
- 🛢 MySQL  
- 📦 pip (Python package manager)  

### Setup  
1. **Clone the repository**  
   ```sh  
   git clone https://github.com/hishamthajudheen/django-crm.git  
   cd your-crm-repo  
   ```  

2. **Create and activate a virtual environment**  
   ```sh  
   python -m venv venv  
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`  
   ```  

3. **Install dependencies**  
   ```sh  
   pip install -r requirements.txt  
   ```  

4. **Configure MySQL database in `settings.py`**  
   ```python  
   DATABASES = {  
       'default': {  
           'ENGINE': 'django.db.backends.mysql',  
           'NAME': 'your_db_name',  
           'USER': 'your_db_user',  
           'PASSWORD': 'your_db_password',  
           'HOST': 'localhost',  
           'PORT': '3306',  
       }  
   }  
   ```  

5. **Apply database migrations**  
   ```sh  
   python manage.py migrate  
   ```  

6. **Create a superuser (admin access)**  
   ```sh  
   python manage.py createsuperuser  
   ```  

7. **Run the server**  
   ```sh  
   python manage.py runserver  
   ```  

8. **Access the application**  
   ```
   http://127.0.0.1:8000/  
   ```  

## Usage  
- 🔑 Log in with admin credentials (`/admin` for Django admin panel)  
- 👥 Add and manage customers, leads, and sales pipelines  
- 📅 Track tasks and activities  
- 📊 View analytics on the dashboard  

## Contributing  
💡 Feel free to **fork** this repository, create a new **branch**, and submit a **pull request** with improvements!  

## License  
📜 This project is licensed under the **MIT License**.  

---
