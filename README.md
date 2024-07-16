This is a sample SlackBot application integrated with WatsonX 

Steps to follow to run the slack bot 

Download the files to local system

1.Go to the directory where the project is downloaded

Set the environment variables

2.export SLACK_TOKEN="xoxb-"

3.export SIGNING_SECRET="obtained from the slack api app page "

4.export API_KEY="API key created for the watsonX from IBM Cloud IAM"

5.export PROJECT_ID="from the sandbox environment"

Run the applicatoion 
6.python3 -m venv path/to/venv

7.source path/to/venv/bin/activate

8.python3 -m pip install -r requirements.txt

9.python3 app.py

open new terminal

ngrok http 8080
