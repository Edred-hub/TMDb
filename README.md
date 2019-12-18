LOCAL HOST:
Step 1: Connect to GitHub
a. Create TMDb directory in your localhost
b. Clone / download all files in your localhost (i.e: ubuntu, Mac)

Step 2: Connect to Docker
a. https://hub.docker.com/?overlay=onboarding
b. download and install, run the apps for (Windows or Mac)
c. either create new account or login your docker account

Step 3: Run the Docker
a. [Localhost] $current [TMDb] directory {copied files from Github link)
b. [$TMDb] enter command $docker-compose -up -d

CLOUD INFRASTRUCTURE
Step 4: AIRFLOW AUTOMATION WORKFLOW
a. Open the localhost web browser (ie:chrome, firefox)
b. Enter http://localhost:8080/admin/
How to guide: https://airflow.apache.org/docs/stable/howto/index.html

Step 5: click DAGs (Direct Acyclic Graph)
a. Automated schedule @daily: switch off/on the (i)con
b. Manual: select the Links (triangle icon) Trigger Dag

Central Data Store (*.json datasets)
https://drive.google.com/drive/folders/1D3f85yZgqGDloulMwIxn1iN_mddNLaxr?usp=sharing

Data Science Results:
https://public.tableau.com/profile/edred#!/vizhome/TV-SeriewDec2019/Sheet1?publish=yes

Email notification Data Store 2:
Login to https://mail.google.com/
name: tmbd datastore
email: tmbddastore@gmail.com
Pass: (see dag.py- python code)
