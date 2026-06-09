---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator metrics
description: Improve your capacity to conduct experiments effectively and generate insights
topic: Content Management
role: User
level: Beginner
keywords: content, experiment, multiple, audience, treatment
TQID: https://experienceleague.adobe.com/OrtdIfQfKMIWODRi9fr-dEuc7g06hISv6-Dq-54qGeY
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
    internal-label: Journey Optimizer
feature_v2:
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
    internal-label: Track and monitor
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
    internal-label: Content management
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
    internal-label: Publish
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
    internal-label: Experimentation
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
---
# Metrics {#experiment-accelerator-metrics}

The **[!UICONTROL Metrics]** page displays success metrics from Journey Optimizer and Target experiments in one place, enabling performance monitoring, comparison, and deeper insights.

## Dashboard {#dashboard}

When accessing the **[!UICONTROL Metrics]** tab, all available success metrics from Journey Optimizer and Adobe Target are listed in a consolidated view to help you track performance across initiatives, compare results, and quickly identify areas that require attention.

Access filters by clicking ![](assets/do-not-localize/Smock_Filter_18_N.svg), which offers context-specific options such as filtering by **[!UICONTROL Source]** or **[!UICONTROL Used in active experiments]**.

Alternatively, quickly find any metric by typing its name into the search bar.

![](assets/experiment-monitor-metrics.png)

## Metric details {#metric-details}

### Incremental over time

![](assets/experiment-monitor-metrics-2.png)

The **[!UICONTROL Incremental over time]** chart provides a visual breakdown of how the selected metric is trending across a chosen time range. Use the drop-down menu to toggle between daily or weekly views to adjust the level of granularity.

Following summary values are available for quick reference:

* **[!UICONTROL Total]**: The cumulative value of the selected metric over the reporting period. 

* **[!UICONTROL Average]**: The typical value of the metric calculated across the selected time range. By balancing out daily or weekly fluctuations, it provides a clearer picture of normal performance and can be used as a baseline for comparison.

* **[!UICONTROL Conversion rate]**: Percentage of profiles who completed the desired action (e.g., purchase, sign-up) after seeing the treatment.

Each value includes a percentage change from the previous period, making it easy to see whether performance is improving, declining, or remaining stable.

### Experiment effect

![](assets/experiment-monitor-metrics-3.png)

This section displays all active experiments within the selected time frame (Last 90 days, Last 30 days, or Last 7 days) and highlights their contribution to the metric.

Following metrics are available:

* **[!UICONTROL Lift]**: Measure of the percentage improvement in conversion rate of a given treatment over the baseline.

* **[!UICONTROL Confidence]**: Evidence that a given treatment is the same as the baseline treatment. [Learn more](http://experienceleague.adobe.com/en/docs/journey-optimizer/using/content-management/content-experiment/technotes/experiment-calculations)

* **[!UICONTROL Contribution]**: The proportion of the overall change in the metric that can be attributed to a specific experiment or treatment, enabling identification of the initiatives exerting the greatest relative impact.
