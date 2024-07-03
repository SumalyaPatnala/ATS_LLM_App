Smart ATS
Hey there! Welcome to Smart ATS, your go-to app for supercharging your resume for those tough job applications. Let’s get started on making your resume stand out!

What's This?
Smart ATS is an app that helps you improve your resume by matching it with a job description. Think of it as your personal resume coach, making sure you're hitting all the right notes in a competitive job market.

What Do You Need?
Python: Gotta have this for running the app.
Streamlit: Our cool framework for building the app.
google-generativeai: For some smart AI magic.
PyPDF2: To handle PDF resumes.
dotenv: For keeping your API keys safe and sound.
Setting It Up
Clone this repo: Get the code on your machine.

bash
Copy code
git clone <your-repo-url>
cd smart-ats
Install the goodies: Grab all the necessary packages.

bash
Copy code
pip install -r requirements.txt
Set up your environment variables: You'll need a .env file with your Google API key.

makefile
Copy code
GOOGLE_API_KEY=your-google-api-key
Run the app: Let's get this show on the road!

bash
Copy code
streamlit run app.py
How to Use
Paste the Job Description: Drop the job description in the text area.
Upload Your Resume: Hit that upload button and load your resume (PDF only).
Submit: Click the submit button and let the magic happen!
What Happens Next?
The app reads your resume, checks it against the job description, and gives you a detailed breakdown:

JD Match: How well your resume matches the job description.
Missing Keywords: Important keywords you might have missed.
Profile Summary: A summary to help you improve.
That’s It!
You’re all set to make your resume shine. Give it a go, and best of luck with your job hunt!
