# Blog App

This is a simple blog application built with Flask. It allows users to create, read, update, and delete blog posts. Additionally, it includes a contact form that sends messages via email.

## Features

- **Create, Edit, and Delete Blog Posts**: Users can create new blog posts, edit existing ones, and delete posts they no longer want.
- **View Blog Posts**: Visitors can view all the published blog posts.
- **Rich Text Editing**: Blog posts are created and edited using a rich text editor powered by CKEditor.
- **Contact Form**: Visitors can send messages through a contact form, which will be emailed to the site owner.
- **Responsive Design**: The application is designed to work well on both desktop and mobile devices.

## Feature-Usage

- **Home Page**: Displays all blog posts.
- **Create/Edit Post**: Add a new blog post or edit an existing one using the rich text editor.
- **Delete Post**: Remove a blog post.
- **Contact**: Send a message to the site owner via the contact form.
- **About**: Learn more about the blog.

## Technologies Used

- **[Flask](https://flask.palletsprojects.com/)**
- **[SQLAlchemy](https://www.sqlalchemy.org/)**
- **[WTForms](https://wtforms.readthedocs.io/)**
- **[CKEditor](https://ckeditor.com/ckeditor-4/)**
- **[Bootstrap](https://getbootstrap.com/)**
- **SMTP (Simple Mail Transfer Protocol)**

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Fariha223/blog-app.git
    cd blog-app
    ```

2. Set up a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the database:
    ```bash
    flask db upgrade
    ```

5. Set up environment variables for your email credentials:
    - Replace `EMAIL` and `PASSWORD` in the `send_email` function in `app.py` with your actual email credentials.

6. Run the application:
    ```bash
    flask run
    ```

7. Open your browser and navigate to:
    ```
    http://127.0.0.1:5000/
    ```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any changes.

## Contact

For any inquiries or feedback, feel free to reach out to me via [GitHub](https://github.com/Fariha223).
