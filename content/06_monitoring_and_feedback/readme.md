![Banner](../../resources/WelcomeBanner.png)

- [Introduction](/../../)
- [Challenge 1: Visualise Work](../../content/01_visualise_work)
- [Challenge 2: Development Practices](../../content/02_development_practices)
- [Challenge 3: Continuous Integration](../../content/03_continuous_integration)
- [Challenge 4: Security & Test Automation](../../content/04_security_and_test_automation)
- [Challenge 5: Automated Deployment & Continuous Delivery](../../content/05_automated_deployment)
- Challenge 6: Monitoring & Feedback

# Challenge 06: Monitoring & Feedback  
_Duration: XX minutes_  

The DevOps process should continue into production and provide monitoring and feedback to understand usage and issues. In this challenge we'll add telemetry to the deployed web app and look at closing the loop by integrating the telemetry into GitHub to create issues. 

## Task 1: Add Application Insights to the deployed web app

- Familiarise yourselves with [Application Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) which is an Application Performance Management service for developers and DevOps professionals and a feature of Azure Monitor that we'll use in this challenge.
- In the Azure Portal, navigate to your App Service and add Application Insights to the app from the Application Insights blade. For reference see how to [Instrument web apps at runtime with Application Insights Codeless Attach](https://docs.microsoft.com/en-us/azure/azure-monitor/app/monitor-performance-live-website-now) 
- Once configured check that you can see telemetry by accesing your app and checking in the Application Insights overview blade to see server request graphs and more. Note that there can be a short delay (perhaps a couple of minutes) in the telemetry being displayed. 

## Task 2: Integrate GitHub with Application Insights

- In the Azure Portal you can [link Application Insights to GitHub](https://azure.microsoft.com/en-gb/blog/application-insights-work-item-integration-with-github/) so that you can create Issues based on Application Insights events and logs. You'll find the settings under the Work Items blade in Application Insights.
- Link the Application Insights instance you've added to your GitHub repo and test creating an issue from some telemetry.

## Task 3: Add custom telemetry to your app

- You can add custom telemetry to your application to send any metrics you want to Application Insights.
- Take a look at the [TelemetryClient API](https://docs.microsoft.com/en-us/azure/azure-monitor/app/nodejs#telemetryclient-api) and track whatever events, exceptions, metrics, traces, dependencies and requests you'd like. 

## Resources

- [What is monitoring in the DevOps process](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-monitoring)
- [Application Insights Overview](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)
- [Application Insights Dashboard](https://docs.microsoft.com/en-us/azure/azure-monitor/app/overview-dashboard)
- [Application Insights API for custom events and metrics](https://docs.microsoft.com/en-us/azure/azure-monitor/app/api-custom-events-metrics)