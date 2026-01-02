# NLP_EXAM
For NLP project


## Running the job
For this i would highly recommend uc1-l4-6 or something better, as it is going to be quite power intensive the work that will go into this.

## Requirements
A requirements.txt is situated inside of the Exam folder. Change directory into the exam folder.
In terminal:
''cd Exam/''

Then run the requirements.txt file
''pip install -r requirements.txt''

## The order of scripts to run
1. Start off by running the Persona_Prompting.ipynb for the persona-based prompting data -> Creates Persona_Data.csv 
2. Proceed to run the Steering_Vectors.ipynb for the steering vector-based data -> Creates Steering_Vector_Data.csv
3. Finally run data_analysis.ipynb

The raw data sits in data -> MFQ30. There will be 4 files in total:
1. mfq_part1_questions.json
2. mfq_part2_questions.json
The format json files which are the questions answered by the persona prompting and steering vector

3. Persona_Data.csv 
4. Steering_Vector_Data.csv
The two datasets with their rating and answers regarding the questionnaire.

