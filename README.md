1. Application script


The application script makes use of the open-source machine learning and data science app framework __streamlit__. 

You must replace the Open AI API key in the "constants.py" file in order to run it after downloading the folder and "pip install requirements.txt" file.Once you've followed the steps, you'll need to execute the programme using ```streamlit run app.py``` and follow the procedure that the app will ask you. The app will provide you with a ```cv_template.txt``` file. Download it, fill it up with all your details. You can add __Experiences__, update the __summary__, delete __experiences__. 

The programme will describe everything that is occurring, print out a summary and a proposal for a work experience, and present the results as a downloaded file that you can quickly download by pressing a button. 


2. main.py script

The application script uses the streamlit, that is an open-source app framework for Machine Learning and Data Science. 
In order to run it, once you download the folder and the ```pip install requirements.txt``` file, you have to change the ```constants.py``` file and change it with the Open AI API key.
Once that you have followed the procedure, what you'd have to do is to run the app using ```python main.py```

In this file, change the 'cv_example.txt' file with the file that you want to be analyzed. Look for this line:```uploaded_file = open('cv_example.txt','r')```

This script is quite effective despite being less "user friendly". Although it doesn't print anything, a "cv_reviewed.txt" file containing the proposed change to the summary and work experiences is output. 


3. Examples

This is an example using the script on my CV.

__Input SUMMARY:__ 

I'm a physicist who has honed my data science and deep learning talents.Physics of Complex Systems and Big Data Master's Degree (grade: 110/110 cum laude).

Currently earning a PhD at the University of Cincinnati and working as a research assistant in the department of aerospace engineering and engineering mechanics. 

My research seeks to use machine learning and data science to improve engineering trials.Technical contributor at Towards Data Science (60k+ monthly views) on popular machine learning applications and methods for solving practical issues. 

__AI Improved SUMMARY:__

I am a highly skilled physicist with a strong foundation in data science and deep learning. In my Master's programme in physics of complex systems and big data, I received the exceptional grade of 110/110 cum laude. I am presently working as a research assistant at the University of Cincinnati's Aerospace Engineering and Engineering Mechanics Department, where I am optimising engineering trials using data science and machine learning methods. I also work as a technical writer for Towards Data Science, which receives over 60k visits each month.


__Input EXPERIENCE:__ 


Developing deep learning classification methods for solar flares using magnetograms


__AI Improved EXPERIENCE:__


I recently finished my Bachelor's thesis, which examined how a Deep Neural Network might be used to forecast the next solar cycle. My research centred on the creation of a model that could predict solar activity with accuracy and offer perception into solar behaviour in the future. To develop a model that attained a high level of accuracy, I used a number of techniques, including data mining, statistical analysis, and machine learning. My discoveries could considerably advance our knowledge of solar activity and offer useful data for forecasting future solar cycles.






