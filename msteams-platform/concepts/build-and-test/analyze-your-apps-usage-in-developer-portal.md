---
title: Analyze your app's usage in Developer Portal
description: In this module, learn how to analyze your app's usage in Developer Portal
ms.localizationpriority: medium
ms.topic: overview
ms.author: v-sdhakshina
---

# Analyze your app's usage in Developer Portal

In the Developer Portal for Teams, on the **Overview** page, you can see the total number of active users for your app.

> [!NOTE]
> Usage analytics are currently available only for new custom apps published to your org through **Developer Portal** for Teams or imported into **Developer Portal** for Teams after April 2022. Usage analytics for all the apps published to the Teams store is available in **Partner Center**, for more information [Teams apps usage report](/office/dev/store/teams-apps-usage).

| Metric | Definition |
| :-----------------------| :------------------------------------------------------------------------------------------------------|
| *Monthly R30* | The default usage metric. It shows the count of unique active users who used your app within that rolling 30 day window in UTC. |
| *Daily* | It shows you the count of unique active users who used your app in a given day in UTC. |

The app usage for a given day is reflected within 24 to 48 hours, and usage data for new apps can take up to three to five days to reflect in the charts.

You can view your app's usage and other insights from the **Analytics** page. To access the page:

1. Go to **[Developer Portal for Teams](https://dev.teams.microsoft.com)**.
1. Select **Apps** from the left pane.
1. Select the required app from the **Apps** page.
1. Select **Analytics** under the **Overview** or select **View details** under the **Active Users (Preview)** card.

 :::image type="content" source="../../assets/images/tdp/dev-app-portal.PNG" alt-text="dev-Portal-analytics"lightbox="../../assets/images/tdp/dev-app-portal.PNG":::

As you explore individual metrics on this page, you can use the **Filter** button to analyze your app's usage from the following filter options:

* Aggregation type: This filter allows you to group the following metrics by a count of distinct users or a count of distinct tenants or customers.
* Platform
* Operating system
* Area

 :::image type="content" source="../../assets/images/tdp/dev-analytics-filter.PNG" alt-text="Filter":::

After you have selected your desired filters, you can explore the following individual widgets:

* [Usage by time period](#usage-by-time-period)
* [Usage by platform and OS](#usage-by-platform-and-os)
* [Usage by retention state](#usage-by-retention-state)
* [Usage intensity](#usage-intensity)

## Usage by time period

The **Usage by time period** chart shows you the number of active users or tenants who opened and used your app across different time periods.

 :::image type="content" source="../../assets/images/tdp/usage-by-time-period.png" alt-text="Period":::

| Metric | Definition |
| :-----------------------| :------------------------------------------------------------------------------------------------------|
| Monthly R30 | Each data point represents a given R30 (Rolling 30 day) period. |
| Monthly R28 | Each data point represents a given R28 (Rolling 28 day) period. |
| Weekly R7| Each data point represents a given R7 (Rolling 7 day) period. |
| Daily | Each data point represents a given R1 (Rolling 1 day) period. |

## Usage by platform and OS

The **Usage by platform and OS** chart shows your app's active usage across various endpoints, such as **Windows**, **Mac**, **iOS**, **Android**, and **Web**. The same user or tenant can use an app on multiple endpoints. Each data point represents a given R30 (Rolling 30 day) period.

 :::image type="content" source="../../assets/images/tdp/usage-by-platform-OS.png" alt-text="Platform":::

## Usage by retention state

The **Usage by retention state** chart lets you track four key retention or churn metrics for your app over time.

:::image type="content" source="../../assets/images/tdp/usage-by-retention-state.png" alt-text="Retention":::

| Metric | Definition |
| :-----------------------| :------------------------------------------------------------------------------------------------------|
| New users or tenants | Active users or tenants who are new new and have not used your app. |
| Returning users or tenants | Active users or tenants who used your app during a given R30 (Rolling 30 day) time period and the immediately preceding R30 time period. |
| Resurrected users or tenants | Active users or tenants who used your app one or more times before but not in the immediately preceding R30 time period. |
| Lapsed users or tenants | Active users or tenants who were not seen during a given R30 time period but were seen during the immediately preceding R30 time period. |

## Usage intensity

The **Usage intensity** chart shows you key usage intensity metrics for your app.

 :::image type="content" source="../../assets/images/tdp/usage-intensity.png" alt-text="Intensity":::

| Metric | Definition |
| :-----------------------| :------------------------------------------------------------------------------------------------------|
| Median days used per month | The median numbers of days in which your app was opened in the last R30 (Rolling 30 day) time period. |
| % of 5+ Days usage | The % of Active Users who opened or used the app more than five days in the last R30 time period. |
| DAU/MAU | The ratio of the average number of unique users or tenants who used your app on each day divided by the Monthly Active Users for the selected R30 time period. |

## App dashboard

The **My App dashboard** table shows you the latest R30 (Rolling 30 day) data for each of the metrics under the previous four categories, and the Month over Month change. Use the time picker on the upper left and select the desired date, you can see daily R30 data for the last 75 days and end of month R30 data for up to 12 months.

You can select each of these **Metric name** to see trends over time.

 :::image type="content" source="../../assets/images/tdp/app-dashboard.png" alt-text="app":::

## See also

[Include a SaaS offer with your Microsoft Teams app](~/concepts/deploy-and-publish/appsource/prepare/include-saas-offer.md)