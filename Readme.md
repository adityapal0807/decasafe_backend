# DecaSafe Backend Repository

Welcome to the DecaSafe backend repository! This README provides instructions for setting up and running the DecaSafe project on your local machine.

## Prerequisites
Before you start, make sure you have the following installed on your machine:

- Python (3.9 or higher)
- pip (Python package manager)

## Installation

### Clone the Repository
Clone the DecaSafe repository to your local machine using the following command:

\`\`\`bash
git clone [repository_url] DecaSafe
\`\`\`

### Navigate to Project Directory
Change your working directory to the project folder:

\`\`\`bash
cd DecaSafe
\`\`\`

### Create a Virtual Environment
It's recommended to use a virtual environment to isolate project dependencies. Create a virtual environment with:

\`\`\`bash
python3 -m venv venv
\`\`\`

### Activate Virtual Environment
On Windows:

\`\`\`bash
venv\Scripts\activate
\`\`\`

On macOS and Linux:

\`\`\`bash
source venv/bin/activate
\`\`\`

### Install Dependencies
Install the project dependencies using pip:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

### Configure Environment Variables
Create a `.env` file in the project directory and add the necessary environment variables specific to your project.

## Running the Project

After successfully installing the project and setting up your environment, you can run the Django development server with the following command:

\`\`\`bash
python manage.py runserver
\`\`\`

Once the development server starts, you can access the DecaSafe project at [http://localhost:8000/](http://localhost:8000/).

---

Feel free to reach out for any assistance 
