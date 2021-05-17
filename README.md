# Apache Airflow
My practice and reference project for Apache Airflow.


# RUN Airflow

conda activate <your_environment>

export AIRFLOW_HOME = <your_airflow_workspace>

airflow initdb (only when you are setting up for the first time)

airflow webserver


# RUN SCHEDULER

conda activate <your_environment>

export AIRFLOW_HOME = <your_airflow_workspace>

airflow scheduler


# OTHER COMMANDS

airflow unpause/pause <dag_id>

airflow trigger <dag_id>

airflow next_execution <dag_id> 

airflow show_dag <dag_id>

airflow resetdb 

airflow list_tasks <dag_id>
