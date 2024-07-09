# Website README

## Overview

Welcome to StudyBud! This platform allows users to create virtual rooms where they can discuss various topics with other people. The website is built using Django, HTML, and CSS.

## Features

- **User Authentication**: Register, log in, and log out.
- **Room Creation**: Create rooms to discuss specific topics.
- **Join Rooms**: Join existing rooms to participate in discussions.
- **Real-Time Chat**: Engage in real-time discussions with other room participants.

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS

## Installation

### Prerequisites

- Python 3.x
- Django
- Pip

### Steps

1. **Clone the Repository**
   ```sh
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Create a Virtual Environment**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Apply Migrations**
   ```sh
   python manage.py migrate
   ```

5. **Run the Server**
   ```sh
   python manage.py runserver
   ```

6. **Open the Website**
   Open your web browser and go to `http://127.0.0.1:8000/`.

## Usage

1. **Register an Account**: Create a new account to access the platform.
2. **Log In**: Use your credentials to log in.
3. **Create a Room**: Navigate to the "Create Room" page, enter the topic, and create your room.
4. **Join a Room**: Browse the list of existing rooms and join any room to participate in the discussion.
5. **Chat**: Once inside a room, use the chat interface to communicate with other participants in real-time.

## Project Structure

```
.
├── manage.py
├── requirements.txt
├── venv/
├── base/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   └── ...
│   └── static/
│       └── ...
└── studybud/
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Contact

For any questions or feedback, please contact [shashhankt@gmail.com].

---

Thank you for using the Room Discussion Website! Enjoy your discussions!
