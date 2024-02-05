# Django Bulletin Board

## Overview
This code is a Bulletin Board made of Django Famework, a simple web app where users can create and delete posts on the board.

## Features
- Create and delete posts with ease.

## Setup
1. **Clone the Repository:**
    ```
    git clone https://github.com/LABYRINTH3/Django-bulletin-board.git
    ```

2. **Navigate to the Project Directory:**
    ```
    cd Django-bulletin-board
    ```

3. **Create a Virtual Environment:**
    ```
    python3 -m venv venv
    ```

4. **Activate the Virtual Environment:**
    - macOS/Linux:
        ```
        source venv/bin/activate
        ```
    - Windows (cmd.exe):
        ```
        venv\Scripts\activate.bat
        ```
    - Windows (PowerShell):
        ```
        .\venv\Scripts\Activate.ps1
        ```

5. **Install Dependencies:**
    ```
    pip install -r requirements.txt
    ```

6. **Apply Migrations:**
    ```
    python manage.py migrate
    ```

7. **Run the Development Server:**
    ```
    python manage.py runserver
    ```

8. **Access the Application:**
    Open your web browser and go to `http://localhost:8000` or your port.

## Usage
1. **Create a Post:**
    - Click on "New Post" to create a new post.
2. **Delete Posts:**
    - Navigate to a post and click on the delete button to remove it.

## Known Issues
- CSRF protection is disabled for development convenience. Enable it in production.

## Credits
This project is inspired and referenced by [생활코딩](https://www.opentutorials.org/course/1) and developed by LABYRINTH3.
