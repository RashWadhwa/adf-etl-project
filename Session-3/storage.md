# End-to-end ETL pipeline created in Azure Data Factory.
This document will show you step-by-step information how I created an end-to-end ETL pipeline in Azure Data Factory. The pipeline will extract data from a source, transform it, and load it into a destination.

## First, created an account in data factories to access the Azure Data Factory Studio and launched it.
![alt text](images/studioLaunch.png)

### Dashboard view in ADF.
![alt text](images/dataFactory.png)

### Showing the concept behind the requirements and connection to create datasets, linked services, copy activity to create a pipeline.
![alt text](images/diagram.png)

### Created a linked services and tested connection.

![alt text](images/linkedService.png)

![alt text](images/serverDetail.png)

![alt text](images/connectionTested.png)

![alt text](images/lsConfirmed.png)

![alt text](images/lsTestedForADLS.png)

### Confirmed that both linked services for DB and ADLS appeared up after creation.
![alt text](images/bothLsDone.png)

### Sample database connected and dataset previewed, and checked in landing container.
![alt text](images/sampleDatasetConnected.png)

![alt text](images/sourceCsvAdded.png)

![alt text](images/queued.png)

### Created a copy activity and connected the source and destination.
![alt text](images/succeeded.png)

![alt text](images/confirmedInLanding.png)

![alt text](images/csvData.png)

### Ran the pipeline and checked the details.
![alt text](images/pipelineDetail.png)

### Finally click on 'Publish all' as it won't save automatically.
