# ResumeIQ

An ATS (Applicant Tracking System) checking app built with Streamlit, Google Gemini Pro Vision API, and various Python libraries to analyze resumes against job descriptions.

Features
Upload PDF Resumes: Upload a resume in PDF format.
Job Description Analysis: Paste a job description for the role you are hiring for.
Resume Assessment: Get a comprehensive assessment of the resume against the job description.
Percentage Match: Determine the percentage match between the resume and the job description.
Highlight Missing Keywords: Identify keywords or skills missing from the resume.
Technologies Used
Streamlit: Web application framework for creating the app interface.
pdf2image: Library for converting PDF documents to images.
Pillow: Python Imaging Library for image processing.
Google Generative AI (Gemini Pro Vision API): For generating content and analyzing the resume.
Base64: Encoding binary data for API requests.
dotenv: Loading environment variables from a .env file.
Installation
Clone the repository:

git clone https://github.com/R0obin/End-To-End-Resume-Application-Tracking-System-ATS-Using-Google-Gemini-Pro-Vision-LIM-Model.git
Navigate to the project directory:

cd End-To-End-Resume-Application-Tracking-System-ATS-Using-Google-Gemini-Pro-Vision-LIM-Model
Create a virtual environment:

python -m venv atsenv
Activate the virtual environment:

On Windows:
atsenv\Scripts\activate
On macOS/Linux:
source atsenv/bin/activate
Install the dependencies:

pip install -r requirements.txt
Install Poppler:

On Windows: Download Poppler from Poppler for Windows and add the bin folder to your PATH environment variable.
Create a .env file and add your Google API key:

GOOGLE_API_KEY=your_google_api_key_here
Usage
Run the Streamlit app:

streamlit run app.py
Open your web browser and navigate to http://localhost:8501.

Upload a resume PDF and paste the job description in the provided text area.

Click on the buttons to get a detailed assessment or percentage match.

Contributing
Fork the repository.
Create a new branch:
git checkout -b my-feature-branch
Make your changes and commit them:
git commit -m "Add some feature"
Push to the branch:
git push origin my-feature-branch
Create a Pull Request.
