# School Fees Tracker

School Fees Tracker is a web application built with HTML, CSS, JavaScript, and Django. This app is designed to keep a record of student fees, allowing administrators to efficiently manage and track payments. Note that this application is intended for use by administrators only and is not accessible to students.

## Features

- **Admin Panel**: Secure login for administrators to manage the fee records.
- **Student Fee Records**: Track and update fees for individual students.
- **User-friendly Interface**: Simple and intuitive interface for ease of use.
- **Search Functionality**: Quickly find student fee records.
- **Responsive Design**: Works on both desktop and mobile devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django

## Installation

To run this project locally, follow these steps:

1. **Clone the repository and change the present working directory:**
   ```bash
   git clone https://github.com/TechExplorer03/School-Fees-Tracker.git
   cd School-Fees-Tracker
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the application:**
   Open your browser and go to `http://127.0.0.1:8000/admin` to log in to the admin panel.

## Usage

1. **Log in to the admin panel** using the superuser credentials created during installation.
2. **Add student records** and manage their fee information.
3. **Update and track fees** for individual students as needed.
4. **Use the search functionality** to find specific student records quickly.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your branch.
4. Open a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact me at [sreemoyee2003@gmail.com].

---

Thank you for using School Fees Tracker! We hope this tool makes managing student fees easier and more efficient.

