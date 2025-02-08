# IG - Social Media Application

This is a simple social media application built with Django. Users can sign up, log in, create posts, like posts, follow other users, and explore posts.


## Features

- User authentication (sign up, log in, log out)
- Create, view, and delete posts
- Like and unlike posts
- Follow and unfollow users
- Explore posts from all users
- Search for users and posts
- Edit user profile

## Installation

1. Clone the repository:

```sh
git clone https://github.com/yourusername/ig.git
cd ig
```

2. Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install the dependencies:
pip install -r requirements.txt

4. Apply the migrations:
python manage.py migrate

5. Create a superuser:
python manage.py createsuperuser

7. Run the development server:
python manage.py runserver

Open your browser and go to http://127.0.0.1:8000/ to see the application.

Usage
Sign up for a new account or log in with an existing account.
Create new posts by clicking the "Create Post" button.
Like and unlike posts by clicking the "Like" button.
Follow and unfollow users by visiting their profile and clicking the "Follow" or "Unfollow" button.
Explore posts from all users by clicking the "Explore" link.
Search for users and posts using the search bar.
Edit your profile by clicking the "Edit Profile" button on your profile page.
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License.




