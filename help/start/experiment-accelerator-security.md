---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Data usage in AI with Journey Optimizer Experimentation Accelerator
topic: Content Management
role: User
level: Beginner
keywords: content, experiment, multiple, audience, treatment
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
    internal-label: Journey Optimizer
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
    internal-label: Activities
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
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
    internal-label: Metadata
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
    internal-label: Experimentation
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: eb30f47f-d87a-400f-8f78-63ce7979ff56
    internal-label: Machine learning
---
# Data usage in AI with Journey Optimizer Experimentation Accelerator{#experiment-accelerator-security}

**Adobe Journey Optimizer Journey Optimizer Experimentation Accelerator** allows you to automatically discover insights and recommend opportunities to improve your experiments and experimentation program. The solution leverages AI and Machine Learning to provide these recommendations. This statement clarifies how your customers' data is used in **Journey Optimizer Experimentation Accelerator**.

## What data does Journey Optimizer Experimentation Accelerator use?

Currently there are three types of data used by **Journey Optimizer Experimentation Accelerator**:

* **Experiment Metadata**: experiment name, the definition of the audience used in the experiment and the treatments in the experiment, e.g. name, split percentages, location or surface the experiment is served into.

* **Performance of the treatments**: number of people, mean of the success metric and standard deviation for each treatment.

* **Content of the treatment**: the rendered HTML and screenshot of the treatment as it would appear to a user on your website.

## What does Journey Optimizer Experimentation Accelerator do with this data?

**Journey Optimizer Experimentation Accelerator** takes the content for each treatment and creates an embedding, i.e. a mathematical representation of the content, then correlates those embeddings with the performance of the treatments. This process allows extraction of the content attributes that have performed best for future use. Those attributes are then fed into an Adobe hosted large language model, which converts them into human readable statements used to generate insights and suggest opportunities.

## What restrictions does Journey Optimizer Experimentation Accelerator have on the data used?

Each customer is assigned to a specific organization and sandbox. A dedicated model is trained for every sandbox. When a sandbox is deleted, all related data, signals, and models are permanently removed.

* We only use customer data to train or fine-tune the model from that customer.

* We never mix customers to train or fine-tune a model.

## Will Adobe models or AI change a brand's user experience automatically?

No. **Journey Optimizer Experimentation Accelerator** only makes recommendations of what could be changed and how it could be changed. Only users who have permissions to change the experience using Journey Optimizer or Target will be able to act on these recommendations. All recommendations can be reviewed and edited before being pushed out.

## Is there any risk to their data or system stability?

**Journey Optimizer Experimentation Accelerator** only ingests and analyzes data, producing insights and recommendations for future testing. It does not have access to modify any test settings. All suggestions generated within the tool are sent to Target and Journey Optimizer for implementation, ensuring no impact on a customer's current activities.
