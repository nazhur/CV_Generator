# CV Generator

CV Generator is a Django web application that allows users to generate CVs (resumes) by filling out a form with their personal details, education history, work experience, and skills. It also provides a list view to display all the generated CV profiles.

## Project Structure

The project consists of the following files and directories:

- **pdf**: Django application directory containing the main functionality of the project.
  - **models.py**: Defines the database models for the CV profiles.
  - **views.py**: Contains view functions for rendering HTML templates and handling form submissions.
  - **urls.py**: Defines URL patterns for routing requests to appropriate views.
  - **templates**: Directory containing HTML templates for rendering web pages.
    - **accept.html**: Template for the form page where users can input their CV details.
    - **resume.html**: Template for rendering individual CV profiles.
    - **list.html**: Template for displaying a list of all CV profiles.
- **README.md**: This README file provides an overview of the project and its components.

## Installation and Setup

To run the project locally, follow these steps:

1. Clone the repository to your local machine:

git clone https://github.com/nazhur/CV_Generator/

2. Install Python and Django if you haven't already.

3. Navigate to the project directory:

cd CV-Generator

4. Install project dependencies:

pip install -r requirements.txt

5. Apply migrations to create the database schema:

python manage.py migrate

6. Run the development server:

python manage.py runserver

7. Access the application in your web browser at `http://localhost:8000/`.

## Usage

- **Fill out Details**: Navigate to the homepage and fill out the form with your personal details, education, work experience, and skills.
- **Download CV**: After submitting the form, your CV will be generated, and you can download it as a PDF file.
- **View List of Profiles**: Visit the list page to see all the generated CV profiles.

## Technologies Used

- Python
- Django
- HTML
- Bootstrap
- PDFKit (for generating PDFs)

## Screeshots

![Homepage](https://github.com/nazhur/CV_Generator/blob/main/ss1.JPG?raw=true)

![CV Download](https://github.com/nazhur/CV_Generator/blob/main/ss2.JPG?raw=true)


