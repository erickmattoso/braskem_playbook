The Data Engineer need to Implement:
Produce Clean and high-quality data enviroment, So DS can model.
Develop pipelines and architecture solution.
Set up a data pipeline

The Ingest Data is crucial, it inicialize in to move the data from the source to the target location (inside Azure - Data Factory) where you can code the solution.

Link for more information:
The https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/move-sql-azure-adf 
Article gives an example of how to set up a pipeline with Data Factory environment.

The data available belong to Braskem domain or belong to a third party?
Braskem Domain:
Which system? (SAP? Excel Files? Pins?)
Who is the owner of this data??
Who has the knowledge about this Data? Who can be consulted in case of doubts?
Third Party:
What is the contract we have made with third parties?
What is the (contractual) latency of this data?
Which are the restrictions about the contract?
Are this databases automated or manual?
How often we will need to retrieve it (frequency). Streaming, batch or hybrid?
How are we connecting to the data source?
What is the schema and format of the data?
What is the best cloud (Draft) solution for this pipeline?
Can we deliver a online (web) solution? Or on-premisses solution?


Build a Document that will contain all these informations.