# Varsity Tutors & CMU METALS Capstone
Repository for the backend model and code for Capston Team Sky-Jem.


## Structure
final_code: Latest python code for session quality analysis
  - Process audio.mp3 files to generate analysis results in json format to update frontend dashboard, https://github.com/kevin666iiiii/Final-dashboard.
  - Run in order of 1, 2, 3, 4
  - Python environment requirement listed in requirement.txt
  - Need AssemblyAI api for audio transcribing and openai api for analysis. 
    
Data
  - da_schema.csv : Dialogue act classification schema used for MVP1
  - general_rubric.csv : General rubric for session quality assessment for MVP1
  - 500 Sample Supplementary Data (Laste edit_ Mar 21) - mar20 base tutoring session data.csv : Session inforamtion
    
MVP1: Run each in order 
  - Speaker Diarization.ipynb : Generate speaker seperated transcript from audio .wav
  - Entire rubric.ipynb : Overall evaluation for transcript based on rubric
  - DA_prompting.ipynb : Generate dialogue act lables from transcript
  - DA_Visualization.ipynb : Generate insights from da labeled transcript

MVP2: Run this after MVP1 
  - sessionMeasurement_Json .ipynb : Generate Json files for frontend dashboard, https://github.com/kevin666iiiii/Capstone-Web.github.io/tree/main.

MVP3: MVP3 notes

Model: Trained model .pth files for MVP2
    
Notebook: Random notebooks during exploration and development 

