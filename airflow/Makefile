
airflow_init:
	airflow initdb

airflow_up:
	echo $(AIRFLOW_HOME)
	airflow scheduler &
	airflow webserver

airflow_down:
	 (pgrep -f airflow | xargs kill -9) &
	 sleep 1
	 jobs
