FROM jupyter/datascience-notebook
RUN pip install influxdb
ENTRYPOINT ["jupyter", "lab", "--ip=0.0.0.0", "--allow-root" , "--NotebookApp.token=YOUR_PASSWORD_HERE"]
