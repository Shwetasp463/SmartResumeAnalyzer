Smart Resume Analyser App
forthebadge made-with-python
Python 3.6

The proposed resume analyzer using NLP aims to enhance the existing system by incorporating four key modules. Firstly, the "Resume Score" module evaluates resumes by analyzing various
factors such as skills, experiences, and education, providing a quantitative assessment of candidate suitability for a given job. Secondly, the "Skill Recommendation" module utilizes NLP
techniques to identify gaps in candidates' skill sets based on job requirements and recommends relevant skills for enhancement. Thirdly, the "Resume Writing Tips" module offers personalized feedback and suggestions to candidates, helping them optimize their resumes for improved visibility and effectiveness. Lastly, the "Career Recommendation" module leverages NLPpowered analysis of candidate profiles to suggest potential career paths or job opportunities aligned with their skills, experiences, and aspirations, thereby providing valuable guidance for professional development and advancement. This comprehensive approach not only streamlines the recruitment process but also empowers candidates to enhance their employability and career prospects


Source
Extracting user's information from the Resume, I used PyResparser
Extracting Resume PDF into Text, I used PDFMiner.

Features
User's & Admin Section
Resume Score
Career Recommendations
Resume writing Tips suggestions
Courses Recommendations
Skills Recommendations
Youtube video recommendations

Usage
Clone my repository.
Open CMD in working directory.
Run following command.
pip install -r requirements.txt
App.py is the main Python file of Streamlit Web-Application.
Courses.py is the Python file that contains courses and youtube video links.
Download XAMP or any other control panel, and turn on the Apache & SQL service.
To run app, write following command in CMD. or use any IDE.
streamlit run App.py
Uploaded_Resumes folder is contaning the user's uploaded resumes.
Classifier.py is the main file which is containing a KNN Algorithm.

Admin side credentials is machine_learning and password is mlhub123.
