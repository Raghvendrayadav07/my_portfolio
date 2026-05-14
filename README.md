# AWS Portfolio Website using Flask & Elastic Beanstalk

A personal portfolio website built with Python Flask and deployed on AWS Elastic Beanstalk.

---

## Project Overview

This project is a cloud-deployed portfolio website designed to showcase personal projects, skills, and contact information. The application is built using Flask and hosted using AWS Elastic Beanstalk with Gunicorn and Nginx.

---

## Technologies Used

- Python
- Flask
- HTML5
- CSS3
- AWS Elastic Beanstalk
- Amazon EC2
- Amazon S3
- Gunicorn
- Nginx

---

##  Project Structure

```bash
.
├── application.py
├── requirements.txt
├── Procfile
├── templates/
│   └── index.html
└── .ebextensions/
    └── python.config
```


## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python application.py
```


# AWS Deployment

This application is deployed using AWS Elastic Beanstalk.

Services used during deployment:

- Elastic Beanstalk
- EC2 Instance
- S3 Bucket
- Security Groups
- Auto Scaling

---

# Output

Please look in the attached files.


# Live Application

http://myportfolio-env.eba-xmx3qjjy.eu-central-1.elasticbeanstalk.com/

# Author

Raghvendra Yadav



# License

This project is licensed under the MIT License.
