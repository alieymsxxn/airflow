# Apache Airflow
My practice and reference project for Apache Airflow.


# RUN Airflow

conda activate <your_environment>

export AIRFLOW_HOME = <your airflow workspace>

airflow initdb (only when you are setting up for the first time)

airflow webserver


# RUN SCHEDULER

conda activate <your_environment>

export AIRFLOW_HOME=<your airflow workspace>

airflow scheduler


# OTHER COMMANDS

airflow unpause/pause <dag id>

airflow trigger <dag id>

airflow next_execution <dag id> 

airflow show_dag <dag id>

airflow resetdb 

airflow list_tasks <dag id>
