# Django Face Attendance System

A Django-based face recognition attendance system that captures student images, recognizes faces using MTCNN and InceptionResnetV1, and records attendance.

## Features

- Student registration with image capture
- Face recognition using MTCNN and InceptionResnetV1
- Attendance tracking (check-in/check-out)
- Admin panel for student management and camera configuration
- Real-time face recognition with multiple camera support

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
   cd REPO-NAME
   ```

2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```sh
   python manage.py migrate
   ```

5. Start the development server:
   ```sh
   python manage.py runserver
   ```

## Usage

- Register students via the admin panel or the capture page.
- Configure cameras in the admin panel.
- Start face recognition to track attendance.

## License

MIT
