# ESSENCE - A Fashion Brand Website 🛍️

A dynamic, multi-page website built with Django for a conceptual fashion brand named "ESSENCE." The site serves as a digital storefront, featuring a modern homepage, service information, and a functional contact form for user inquiries.

---

🚀 About The Project

"ESSENCE" is a project that demonstrates the use of the Django web framework to build a robust and scalable website. The site is designed to be the online presence for a fashion company, complete with a visually appealing homepage, static content pages, and a backend system to handle user interactions.

The key feature is a "Contact Us" form that captures user data (name, email, query) and saves it to a backend SQLite database, providing a confirmation message to the user upon successful submission using Django's messaging framework.

---

✨ Key Features

* **Dynamic Multi-Page Layout:** A complete website structure with Home, About, Services, and Contact pages.
* **Backend Data Handling:** A functional contact form that securely saves user inquiries to a database.
* **User Feedback System:** Utilizes Django's messaging framework to show success alerts to users (e.g., "Your message has been sent!").
* **Responsive Frontend:** Built with Bootstrap 4, ensuring the site looks great on both desktop and mobile devices.
* **Modular Template Design:** Uses Django's templating engine with a `base.html` for a consistent look and feel across all pages.

---

🛠️ Built With

* **Backend:** **Django**
* **Database:** **SQLite** (default Django DB)
* **Frontend:** **HTML**, **CSS**, **Bootstrap 4**, **JavaScript** (for Bootstrap components)

---

⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

**Prerequisites**

Ensure you have Python 3.x and pip installed on your system.

**Installation**

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/tanish-israni/website-essence.git]
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your_project_name
    ```
3.  **Create and activate a virtual environment:**
    ```sh
    # On Windows
    python -m venv venv
    .\venv\Scripts\activate

    # On macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```
4.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
5.  **Apply database migrations:**
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```
6.  **Run the development server:**
    ```sh
    python manage.py runserver
    ```
    Open your browser and navigate to `http://127.0.0.1:8000`.
