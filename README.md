# Disaster Response Pipeline Project
## Author = Ayemobola Tolulope

## Motivation for the Project

In this project, I apply skills I learned in Data Engineering Section to analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages.


### Instructions: (Run run.py directly if DisasterResponse.db and classifier.pkl already exist.)
1. Run the following commands in the project's root directory to set up your database and model.

    - Use the following command to run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - Use the following command to run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Finally, Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

![ScreenShot](imgage.png)

## Example
Type in: We have a lot of problem at Delma 75 Avenue Albert Jode, those people need water and food.

![Example](SampleImage.png)