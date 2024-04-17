1) Create a folder with dataset
2) open in Git terminal
3)issue git init command on terminal and it will create .git hidden dossier in the project folder
4) git add  . (execute this)
5) then git commit -m 'message'
6) open github, create a new reporistory with same name as your folder
7) open VS code and open new terminal
8) execute these commands on terminal

git remote add origin https://github.com/saadmissen/MLops-NewsClassification.git
PS C:\Users\PMLS\Documents\MLops-NewsClassification> git branch -M main
PS C:\Users\PMLS\Documents\MLops-NewsClassification> git push -u origin main

9) Create the following hierarchy

1) Create a folder with dataset
2) open in Git terminal
3)issue git init command on terminal and it will create .git hidden dossier in the project folder
4) git add  . (execute this)
5) then git commit -m 'message'
6) open github, create a new reporistory with same name as your folder
7) open VS code and open new terminal
8) execute these commands on terminal

git remote add origin https://github.com/saadmissen/MLops-NewsClassification.git
PS C:\Users\PMLS\Documents\MLops-NewsClassification> git branch -M main
PS C:\Users\PMLS\Documents\MLops-NewsClassification> git push -u origin main

9)

Rehmana Younis 11:33 PM
MLOps_News_Classification
├── MANIFEST.in
├── prediction_model
│   ├── config
│   │   ├── config.py
│   │   └── __init__.py
│   ├── datasets
│   │   ├── __init__.py
│   │   ├── test.csv
│   │   ├── train.csv
│   │   ├── business_data.csv
│   │   ├── education_data.csv
│   │   ├── entertainment_data.csv
│   │   ├── sports_data.csv
│   │   └── technology_data.csv
│   ├── __init__.py
│   ├── pipeline.py
│   ├── predict.py
│   ├── processing
│   │   ├── data_handling.py
│   │   ├── __init__.py
│   │   └── preprocessing.py
│   ├── trained_models
│   │   ├── <placeholder for trained model>
│   │   └── __init__.py
│   └── training_pipeline.py
└── VERSION

