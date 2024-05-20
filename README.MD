#  Smart ATS -  App for Resume Improvement (Clear, concise, and informative)


## Description:

1. Boost your resume's chances of landing an interview with Smart ATS, a user-friendly Streamlit app powered by Google AI.
2. Leverage cutting-edge natural language processing (NLP) to analyze your resume against job descriptions and receive valuable feedback.
3. Identify missing keywords, optimize your profile summary, and gain a percentage match score for enhanced competitiveness.


## Installation:

### Prerequisites:
1. Python 3.x, 
2. Streamlit (pip install streamlit),
3.  Google Generative AI library (pip install google-generativeai),
4.  PyPDF2 (pip install PyPDF2), 
5.  dotenv (pip install python-dotenv).


## Instructions:
- Clone or download the repository.
- Create a virtual environment (recommended): python -m venv venv and activate it (. venv/bin/activate on Windows/macOS or source venv/bin/activate on Linux/Unix).
- Install dependencies: pip install -r requirements.txt (if you have a requirements.txt file).
- Create a .env file in the project's root directory and add the API key: GOOGLE_API_KEY=<your_api_key>.

## Usage:

- Open a terminal or command prompt and navigate to the project directory.
- Run the app: streamlit run app.py (replace app.py with your main script name if different).
####  In the Streamlit interface:
- Paste the job description into the "Job Description" text area.
- Upload your resume in PDF format using the "Upload Your Resume" file uploader.
- Click the "Submit" button.
#### The app will process your resume using Google's NLP API and provide a comprehensive response, including:
- JD Match (%): A percentage score indicating how well your resume aligns with the job description.
- Missing Keywords: A list of keywords identified in the job description that are absent from your resume.
- Profile Summary: Feedback and suggestions on improving your profile summary for better visibility.