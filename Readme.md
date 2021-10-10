Requirment:
To create UI which can segregate sports and politics news and publish the respective article

Approach:
Desigining a model which can train by NLP and predict the topic of news, this model requires Data ingestion & cleaning, Model building & training , UI which can predict the new topic
Historical Data has been collected from REST API using python loaded in Mongo DB,the data spooling and storing has done in python as of now, later kafka will be implemented which helps in spooling data between Source and target
The acquired data will be having contain junk data,special characters, un wanted data ect.., this all kind of data will be cleaned using python functions and basic data cleaning.
Model will be trained either supervised or un-supervised based on the data gathered, prediction model is yet to be finalized.
UI will be designed by the help of Flask and Python

Note: This project is in developing phase and you may be seeing changes
