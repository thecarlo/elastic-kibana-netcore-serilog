# Logging with ElasticSearch 7.9.2, Kibana, .NET Core 3.1 and Serilog

Read the full tutorial here: [https://www.humankode.com/asp-net-core/logging-with-elasticsearch-kibana-asp-net-core-and-docker](https://www.humankode.com/asp-net-core/logging-with-elasticsearch-kibana-asp-net-core-and-docker)

## Steps To Run the Solution:
* Spin up Elasticsearch and Kibana in Docker
    * cd src/docker
    * docker-compose up -d
    * Wait a minute or 2 for Elastic and Kibana to start up 

* Using Visual Studio Code
    * be sure to open the `src/Elastic.Serilog.Web` folder in VS Code
    * Hit F5 to build and launch the site
    * A new browser window will open with the url http://localhost:5000

* Using Visual Studio
    * Open the solution file at `src/Elastic.Serilog.Web/Elastic.Serilog.Web.sln`
    * Hit F5 to build and launch the site
    * A new browser window will open with the url http://localhost:5000
    
* View Kibana logs at http://localhost:5601

Full tutorial at https://www.humankode.com/asp-net-core/logging-with-elasticsearch-kibana-asp-net-core-and-docker
