# tokyo-olympic-data-engineering-project
Their I used a azure storage, azure data factory, azure databricks, and azure app(app registration for client id, tenant id and secretkey)
In azure storage we have to create tokyoolympic container and in container we have to create 2 directories raw-data and transformed data.
in data factory we map raw-data of stroage into tranformed-data by using copy-data activity in pipline through source and sink.
