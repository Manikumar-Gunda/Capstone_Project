## Running Instructions

1.  Create a fork of the repo using the `fork` button.
2.  Clone your fork using git clone `https://github.com/Manikumar-Gunda/Capstone_Project.git`
3.  Change to `milestone1` branch.
4.  To setup kafka follow the steps https://github.com/Vedha286/NewsArticlesClassifier/edit/milestone1/data-ingestion-service/setup-steps
5.  On terminal 1 run: `./kafka_2.12-3.0.0/bin/zookeeper-server-start.sh ./kafka_2.12-3.0.0/config/zookeeper.properties`
6.  On terminal 2 run: `./kafka_2.12-3.0.0/bin/kafka-server-start.sh ./kafka_2.12-3.0.0/config/server.properties`
7.  On terminal 3 run: `cd data-ingestion-service`
8.  Install dependencies using: `pip3 install -r requirements.txt`
9.  On terminal 3 run: `python3 consumer.py`
10. On terminal 4 run: `python3 producer.py`
