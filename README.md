<font size="8">**Welcome**!</font><br>
<br>
</font>
<font size="4">Thank you for taking the time to visit my personal GitHub Space. <br>
<br>
I'm a full stack data scientist.  I enjoy developing end to end ML solutions using TensorFlow, Keras and Google Cloud Platform. <br>
<br>
I'm very passionate about helping people and democratizing AI to anyone who is interested in bringing it into their work.<br><br>  I'm going to systematically add production recipes here over time and always look to improve existing projects.  With that said, please monitor any repo of interest as you can exepct consistent updates. <br>

## Full Stack Data Science Projects

### NYC Subway Arrival Time Prediction

| Project  | Description| Domain| Key Technologies | 
|:--------:|:----------:|:--------:|:----------:| 
|Data Tier - ELT for Historic Subway Data | Extracts files from archive, loads them into BigQuery (data warehouse) and applies first level transformations - Orchestrated with Apache Airflow and Cloud Run | Data Engineering | Python, SQL, BigQuery, Cloud Composer (Apache Airflow), Cloud Run, Cloud Scheduler |
|ML Tier - ML Pipelines on Vertex AI | Extracts data from BigQuery, Preprocesses data for ML Training, Executes Training for two ML Models, Deploys ML models to production endpoints, Monitors ML performance for drift, initiates retraining cycles, keeps a metadata store for experiment tracking| Data Science, Timeseries Forecasting, Deep Learning,MLOps| Python, Docker, Kubeflow, TensorFlow, NeuralForecast, Jupyter, Makefile, Bash|
Event Stream Tier - Stream Ingestion and Prediction Service| Deploys VM for ingestion, Ingests event feed from MTA, applies in flight transformations for data enrichment, calls prediction service, writes prediction outputs to nosql database to feed mobile app tier | MLOPs, Data Engineering | Python, Bash, TensorFlow, NeuralForecast, Makefile, Google Compute Engine, PubSub, Apache Beam, Dataflow, FastAPI, Firestore |
Web/Moble App Tier - Consumer Application to Serve Predictions | Currently Being Built | Front End Development | Dart, Flutter, Firebase, Firestore |
