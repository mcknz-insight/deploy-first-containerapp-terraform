# Update application source code with Application Insights Key

We want to view application insights data from within the application. In this lab, we will add the relevant key to the source code.

## Update source code with Application Insights Key

1. The source code for the sample application is [here](https://github.com/mcknz-insight/deploy-first-containerapp-terraform/tree/main/aspnet-core-dotnet-core)

2. Update [appsettings.json](https://github.com/mcknz-insight/deploy-first-containerapp-terraform/tree/main/aspnet-core-dotnet-core/appsettings.json#LL8-L10C4) with Instrumentation key, found by selecting your application insights resource within Azure portal ->  configure -> properties
