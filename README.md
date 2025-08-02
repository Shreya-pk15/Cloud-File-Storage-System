# Cloud File Storage System

Cloud File Storage System is a simple web application built with Flask and MySQL that allows users to register, log in, and securely upload, download, and manage their files. Each user gets a personal storage space, ensuring privacy and organization. The user interface is designed using HTML, CSS, and Bootstrap for a clean and intuitive experience.

This project uses [Render](https://render.com/) for cloud deployment and storage, allowing you to easily host and access your application online.

## Features
- User registration and authentication
- Secure file upload and download
- Personal storage space for each user
- File management (view, download, delete)
- Responsive and user-friendly interface

## Tech Stack
- Python (Flask)
- MySQL
- HTML, CSS, Bootstrap

## Deploying to Render (Cloud)

You can deploy this application to the cloud using [Render](https://render.com/):

1. Push your project to a GitHub repository.
2. Create a free account at [render.com](https://render.com/).
3. Click "New Web Service" and connect your GitHub repository.
4. Set the build and start commands:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `python app.py`
5. Add environment variables for your MySQL database connection as needed.
6. If using a managed database, set it up via Render and update your `app.py` configuration.
7. Click "Create Web Service". Render will build and deploy your app in the cloud.

### Prerequisites
- Python 3.x
- MySQL
- pip (Python package manager)

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Cloud-based-File-Storage.git
   ```
2. Navigate to the project directory:
   ```
   cd Cloud-based-File-Storage
   ```
3. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```
4. Set up the MySQL database using the provided `schema.sql` file.
5. Update the database configuration in `app.py` as needed.
6. Run the application:
   ```
   python app.py
   ```

### Usage
- Register a new account or log in with existing credentials.
- Upload, download, and manage your files securely.
