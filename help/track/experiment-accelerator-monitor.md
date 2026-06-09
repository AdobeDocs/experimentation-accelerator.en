---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator monitor
description: Improve your capacity to conduct experiments effectively and generate insights
topic: Content Management
role: User
level: Beginner
keywords: content, experiment, multiple, audience, treatment
TQID: https://experienceleague.adobe.com/IYG2Jag2XtctyPaYmQfhdMm0Ac5tEg7EA7gOw7GzUk4
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
    internal-label: Journey Optimizer
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
    internal-label: Activities
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
    internal-label: Track and monitor
  - id: d556b755-390a-43f0-be32-a08cf6236126
    internal-label: Configuration
  - id: d998adac-2f81-400b-a669-d07bb196e4eb
    internal-label: Journeys
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
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
    internal-label: Experimentation
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
---
# Track your experiments {#monitor}

The **[!UICONTROL Experiments]** tab centralizes the tracking and analysis of tests from Adobe Journey Optimizer and Adobe Target. You can view all experiments, review KPIs, and filter or search to locate specific tests.

## Dashboard {#dashboard}

When accessing the Experiments tab, all available experiments from Journey Optimizer and Adobe Target are listed in a consolidated view. This allows you to quickly review and compare experiments across both platforms in one place. 
The Experiments list includes:

* Journey Optimizer experiments created in either Campaigns or Journeys.

* Adobe Target experiments available in the Journey Optimizer production default sandbox linked to the same IMS organization.

The KPI section provides key metrics, including the total number of experiments created and the number currently in progress, offering a snapshot of overall experimentation activity

Access filters by clicking ![](assets/do-not-localize/Smock_Filter_18_N.svg), which offers context-specific options such as filtering by **[!UICONTROL Type]**, **[!UICONTROL Starred]**, **[!UICONTROL Status]**, or **[!UICONTROL Source]**. For example, you can filter to show only active experiments from Journey Optimizer.

Alternatively, quickly find your experiment by typing its name into the search bar.

![](assets/experiment-monitor-dashboard.png)

## Monitor your experiments {#monitor-page}

To access and monitor your experiments, select your previously configured experiment from your list of experiments from the **[!UICONTROL Experiments]** tab, or use the advanced menu to **[!UICONTROL View details]** or **[!UICONTROL Open in source]**.

![](assets/experiment-accelerator-1.png)

The experiment detail page is split into the following section:

* [Experiment Outcome](#experiment-outcome)
* [Primary metric](#change-primary-metric)
* [Hypothesis](#hypothesis)
* [Details](#details)
* [Opportunities](#opportunities)
* [Results](#results)
* [Experimentation insights](#insights)

### Experiment outcome {#experiment-outcome}

![](assets/experiment-monitor-outcome.png)

The **[!UICONTROL Experiment outcome]** gives you a quick view of the winning variation in your experiment.

### Change the primary metric {#change-primary-metric}

>[!AVAILABILITY]
>
>Only users with the **[!UICONTROL Manage Experiment Metadata]** permission can change the primary metric.

Changing the primary metric applies to teams that use **[!DNL Customer Journey Analytics]** or **[!DNL Adobe Analytics]** as the reporting source for experiments created in **[!DNL Adobe Target]** or **[!DNL Adobe Journey Optimizer]**.

Keep the following in mind when you set or change the primary metric:

* You import one metric at a time. Your choice is stored as the primary metric for that experiment.

* Updates apply only in Journey Optimizer Experimentation Accelerator. They are not written back to Adobe Target or Adobe Journey Optimizer.

* If your organization uses only Adobe Target as the reporting source, you cannot change the primary metric after the test is published.

To change the primary metric for an existing experiment, follow these steps:

1. From your experiment, click **[!UICONTROL Select Primary Metric]** if none has been assigned or **[!UICONTROL Edit]** if you want to change it.

   ![](assets/primary-metric-1.png)

1. Select a metric that matches the reporting source set when this experiment was created in **[!DNL Adobe Target]** or **[!DNL Adobe Journey Optimizer]**.

   The metrics available to you are determined by the data source configured in **[!DNL Adobe Target]** or **[!DNL Adobe Journey Optimizer]**. For example, if **[!DNL Customer Journey Analytics]** (CJA) was selected as the reporting source in Target, only CJA metrics are available to import. You cannot switch to a metric from a different data source, and you cannot change the primary metric to a native **[!DNL Adobe Target]** metric.

1. Use search to find a metric by name, or use the filter to view metrics already used in active experiments.

   ![](assets/primary-metric-1.png)

1. Save your selection.

When you change the primary metric, previously generated insights and opportunities are cleared and regenerated. During regeneration, the following message is displayed:

`Opportunities are being regenerated based on the selected metric. Updates will appear soon.`

### Set up {#set-up}

The **[!UICONTROL Hypothesis]** captures the planned changes to be tested and documents the expected impact on the primary metric. Defining a clear **[!UICONTROL Hypothesis]** ensures that each experiment has a measurable objective, making it easier to evaluate results and determine whether the changes lead to meaningful improvements.

Note that for [Experiment insights](#insights) to be generated, you need to confirm hypothesis and treatment details and statistical significance to be reached.

1. Click **[!UICONTROL Add]** to create a **[!UICONTROL Hypothesis]** for your experiment. 

   ![](assets/experiment-monitor-setup-1.png)

1. Type-in your **[!UICONTROL Hypothesis]** by detailing changes that was made and how they will impact the primary metric. 

   Click **[!UICONTROL Save]**.

1. Click **[!UICONTROL Review]** to add or replace the image for each Treatment.

   ![](assets/experiment-monitor-setup-2.png)

1. Treatment images are generated automatically, but if needed, you can select **[!UICONTROL Add image]** or **[!UICONTROL Replace image]** to upload a preferred screenshot from your local files for your **[!UICONTROL Treatments]**.

   Note that the screenshot should capture the entire page. 

1. Click ![](assets/do-not-localize/Smock_Edit_18_N.svg) icon to update your **[!UICONTROL Hypothesis]** if needed.

Once you finished configuring your **[!UICONTROL Hypothesis]**, you will to get valuable [Insights](#insights) and [Opportunities](#opportunities). 

### Details {#details}

![](assets/experiment-monitor-details.png)

The **[!UICONTROL Experiment Effect]** widget provides a detailed view of how your experiment influenced the targeted audience segments. It presents key performance indicators that help you assess engagement and behavior, including:

* **[!UICONTROL Success metric]** from Journey Optimizer or the **[!UICONTROL Primary metric]** from Adobe Target depending on what was configured during the experiment creation.

* **[!UICONTROL Visitors]**: The total number of unique visitors exposed to the experiment.

You can also view a real-time snapshot of how the leading treatment is performing through the following metrics:

* **[!UICONTROL Current Leader]**: identifies the treatment currently delivering the best performance.

* **[!UICONTROL Lift Over Baseline]**: measures the percentage improvement of the leading treatment compared to the control or baseline.

* **[!UICONTROL Success metric]** from Journey Optimizer or the **[!UICONTROL Primary metric]** from Adobe Target depending on what was configured during the experiment creation.

At the bottom of the widget, you can find a concise summary of your experiment configuration, including:

* **[!UICONTROL Success metric]** from Journey Optimizer or the **[!UICONTROL Primary metric]** from Adobe Target depending on what was configured during the experiment creation.

* **[!UICONTROL Number of Treatments]**: The total number of variations tested.

* **[!UICONTROL Audience]**: The defined user segment(s) targeted during the experiment.

### Opportunities {#opportunities}

>[!AVAILABILITY]
>
>Opportunities feature is limited to experiments with text-based changes.

The **[!UICONTROL Opportunities]** panel displays AI-generated recommendations designed to enhance test performance and align with broader business objectives and KPIs.

Note that for Experiment opportunities to be generated, you first need to [confirm hypothesis and treatment details](#set-up).

1. Browse through the suggested opportunity and click **[!UICONTROL View Opportunity]**.

   ![](assets/experiment-monitor-opportunities.png)

1. Selecting an opportunity opens the **Opportunity Details** window, which outlines a specific treatment or variation suggested by the Journey Optimizer Experimentation Accelerator. This view includes:

   * **[!UICONTROL Hypothesis]**: An AI-generated hypothesis that explains the expected outcome of the suggested treatment.

   * **[!UICONTROL Rationale]**: An explanation of why the Journey Optimizer Experimentation Accelerator suggested this opportunity. 

   * **[!UICONTROL Opportunity evaluation]**: A dual assessment of the recommendation based on:

      * **[!UICONTROL Learning potential]**: An estimate of how much new insight the opportunity could provide, based on how different it is from what has been tested before.

      * **[!UICONTROL Conversion potential]**: An estimate of how likely the opportunity is to outperform current treatments, based on similarities to strategies that have historically worked well.
   <!--
   * **[!UICONTROL New text treatment example]**: Words or phrases that demonstrate the style the AI recommends using.
   -->

   ![](assets/experiment-monitor-opportunities-2.png)

1. You can then add it directly to your experiment by selecting **[!UICONTROL Open Experiment]**.

1. If the original experiment was created and managed in Adobe Journey Optimizer, this action will open the **[!UICONTROL Content Experimentation Panel]** within that campaign.

   For experiments originating from **[!DNL Adobe Target]**, the suggested changes will instead be loaded into **[!DNL Adobe Target]**'s experimentation workflow. 
   
   ➡️ [Learn more in Adobe Target documentation](https://experienceleague.adobe.com/en/docs/target/using/activities/abtest/test-ab)

1. Within the experiment view, the same AI **[!UICONTROL Experimentation Opportunities]** surfaced by the Journey Optimizer Experimentation Accelerator are accessible. 

   Select **[!UICONTROL View]** to open the opportunity details.

1. To apply the suggested changes, selecting **[!UICONTROL Modify Experiment]** enables direct editing of the existing experiment.

### Results {#results}

![](assets/experiment-monitor-results.png)

The **[!UICONTROL Results]** table provides a detailed performance breakdown of each treatment within an experiment. These indicators help evaluate effectiveness, user engagement, and overall impact on key business outcomes:

* **[!UICONTROL Place]**: Ranking position of the treatment based on performance indicating how it compares to other treatments.

* **[!UICONTROL Success metric]** from Journey Optimizer or the **[!UICONTROL Primary metric]** from Adobe Target depending on what was configured during the experiment creation.

* **[!UICONTROL People]**: Number of user profiles who qualify as target profiles for your messages.

* **[!UICONTROL Lift]**: Measure of the percentage improvement in conversion rate of a given treatment over the baseline.

* **[!UICONTROL Confidence]**: Evidence that a given treatment is the same as the baseline treatment. [Learn more](http://experienceleague.adobe.com/en/docs/journey-optimizer/using/content-management/content-experiment/technotes/experiment-calculations)

* **[!UICONTROL Conversion rate]**: Percentage of profiles who completed the desired action (e.g., purchase, sign-up) after seeing the treatment.

### Experiment insights {#insights}

>[!AVAILABILITY]
>
>Experimentation Insights feature is limited to experiments with text-based changes.

**[!UICONTROL Experiment Insights]** are AI-generated learnings derived from this experiment. These insights become available once the experiment reaches statistical significance and provide contextual understanding of what contributed to its success. They highlight the key attributes present in the winning treatment, distinct from the control, that likely influenced the outcome.

Note that for Experiment insights to be generated, you first need to [confirm hypothesis and treatment details](#set-up) and statistical significance to be reached.

Click **[!UICONTROL View details]** to learn more on each insights.

</br>

![](assets/experiment-monitor-insights.png)
