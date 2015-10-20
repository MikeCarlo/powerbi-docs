<properties 
   pageTitle="Power BI Pro content - what is it?"
   description="Power BI Pro content - what is it?"
   services="powerbi" 
   documentationCenter="" 
   authors="jastru" 
   manager="mblythe" 
   editor=""
   tags=""/>
 
<tags
   ms.service="powerbi"
   ms.devlang="NA"
   ms.topic="article"
   ms.tgt_pltfrm="NA"
   ms.workload="powerbi"
   ms.date="10/16/2015"
   ms.author="jastru"/>

# Power BI Pro content - what is it?  
[← Getting started](https://support.powerbi.com/knowledgebase/topics/63037-getting-started)

Power BI free and Pro licenses are different based on the kind of content users can consume.  **Power BI Pro content** is a dashboard, report, or dataset that uses a connection or other functionality (such as hourly refresh) that is only available to consume with a Power BI Pro license.

If your content contains any of the following items, it's Power BI Pro content:

-   Data from a direct query dataset, such as [SQL Server Analysis Services](https://support.powerbi.com/knowledgebase/articles/471633) tabular data, [Azure SQL Database](https://support.powerbi.com/knowledgebase/articles/581421), [Azure SQL Data Warehouse](https://support.powerbi.com/knowledgebase/articles/636088), or Apache [Spark for HDInsight](https://support.powerbi.com/knowledgebase/articles/654094).

-   Data from a [dataset that refreshes more frequently than daily](https://support.powerbi.com/knowledgebase/articles/474669).

-   Data from a dataset that connects to on-premises data using the Power BI [Personal Gateway](https://support.powerbi.com/knowledgebase/articles/649846) or Power BI [Data Management Gateway](https://support.powerbi.com/knowledgebase/articles/497354).

-   A dashboard or report that's installed from an [organizational content pack](https://support.powerbi.com/knowledgebase/articles/651040).

-   A dashboard, report, or dataset that's contained in a [group workspace](https://support.powerbi.com/knowledgebase/articles/654247).

-   A dashboard that contains data streamed at a rate above 10k rows/hour.

Conversely, if your content contains only the following items it will be consumable by both Power BI free and Pro users:

-   A dashboard or report connected to content packs for services (e.g. Dynamics CRM, Salesforce, and Google Analytics).

-   A dashboard or report with data imported from files such as Excel spreadsheets, Power BI Desktop, and CSV.

For example, if you create a manufacturing dashboard that updates progress multiple times during the day, anyone *consuming* that dashboard would need a Power BI Pro license. Or, if you create a report using the Power BI AS Connector, then another that uses Personal Gateway, anyone *consuming or interacting* with either of those reports would need a Power BI Pro license.

If you want to share your Power BI Pro content with users, they can sign up for a [free trial of Power BI Pro](https://support.powerbi.com/knowledgebase/articles/664495), and gain access to your content during the trial period.

For a list of Power BI Pro features (and how those features compare to a free Power BI license), take a look at [Power BI Pricing](https://powerbi.microsoft.com/pricing).