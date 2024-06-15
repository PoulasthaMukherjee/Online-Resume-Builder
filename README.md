# Online Resume Builder using Django

Welcome to the Online Resume Builder using Django project! This web application allows users to easily create professional resumes by filling out a form with their personal information, educational background, skills, work experience, and more. The generated resume can be downloaded as a PDF, ensuring high-quality output for job applications or personal use.

## Tech stack

<div style="dispaly:flex;">
<img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg" alt="Python" width="40" height="40"/> 

<img src="https://static.djangoproject.com/img/logos/django-logo-negative.svg" alt="Django" width="40" height="40"/> 

<img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML" width="40" height="40"/> 

<img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" alt="CSS" width="40" height="40"/> 

<img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" alt="JS" width="40" height="40"/>

<img src="https://www.pythonanywhere.com/static/anywhere/images/PA-logo-snake-only.svg" alt="PA" width="40" height="40"/>

</div>

## Demo

[Live Demo](https://poulasthamukherjee.pythonanywhere.com/)

## Features

- **User-Friendly Interface**: The web app provides a structured form for inputting personal information, skills, education, projects, work experience, and achievements, making it easy for users to create comprehensive resumes.
  
- **PDF Generation**: The app utilizes HTML to PDF conversion to generate resumes in PDF format, ensuring compatibility and professionalism in the final output.

- **Customizable Templates**: Users can customize their resumes by filling out the form with relevant information, allowing for flexibility in resume design and content.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/PoulasthaMukherjee/Online-Resume-Builder
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```


3. Apply migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```


4. Run the development server:

```bash
python manage.py runserver
```


## Usage

1. Access the web application through your browser.
2. Fill out the form with your personal information, educational background, skills, work experience, projects, and achievements.
3. Click the "Submit" button to generate your resume.
4. Review and download your resume in PDF format.
