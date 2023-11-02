+++
title = "Architecting for Success: Redefining Technical Growth"
date = 2023-08-08
[taxonomies]
categories=["management"]
tags=["product", "management", "architecture"]
+++
# Architecting for Success: Redefining Technical Growth 

Congratulations, you’ve passed the prototyping stage to find market fit, and you no longer have to keep building custom one-off solutions for your biggest clients.

You now have a clearer vision and it’s time to focus on growth; you need to build your scalable profitable business. For tech startups, this means building the platform and supporting services.

Implementing a growth strategy is a different process for different stakeholders.

For one, your board or investors will want to know how a growth strategy will (positively) affect financial performance of the company.


![A simplified revenue projection graph](https://github.com/tameralamiri/tameralamiri.github.io/blob/main/docs/static/imgs/2023-08-08-Architecting-for-Success-Redefining-Technical-Growth/a-simplified-revenue-projection-graph.png?raw=true)

Meanwhile, a conversation about growth with the product team will have more specificity and focus on considerations such as: 

* What growth strategy should be implemented?
* How do we design an execution plan (a.k.a., the product roadmap)?

Let’s look at one basic growth metric LTV/CAC (lifetime value/ customer acquisition cost).

![LTV/CAC projection graph](https://github.com/tameralamiri/tameralamiri.github.io/blob/main/docs/static/imgs/2023-08-08-Architecting-for-Success-Redefining-Technical-Growth/ltv-cac-projection-graph.png?raw=true)

Some of the questions related to this metric the product team will try to answer include:
* What features can be added to increase customer engagement?
* How to improve the onboarding process to help customers quickly experience/identify/ the product value?
* What bottlenecks in the user journey need to be addressed to reduce customer friction?

Answering these questions will inform the product roadmap design.

Creating a product roadmap in general is a complex process, and creating a product roadmap for startups is even harder given typically limited budgets and small engineering teams. But really, a product roadmap simply lays out a priority order for execution while striking a balance between short-term and long-term goals. A few words of warning:

* Focusing too much on short-term goals (the quick wins and low hanging fruit) might show visible improvement to the end-user, but it doesn’t help the company with its growth goals.
* Focusing too much on long-term goals (building a scalable platform) means the company needs to pivot or freeze until the engineering team completes building the platform, which puts the company at a high risk of running out of money before it can bring in more revenue.

The solution is to put some effort into short-term goals, and also to break the long-term goals into smaller fragments, what I like to call **MVFs (Minimal Viable Fragments)** to keep the company on track with executing its growth vision.

## The ABCs of MVFs:
* **An MVF is the minimal piece of the scalable platform that provides customer value.**
* **An MVF is not a quick and dirty solution to show value to customers (not an MVP). It’s a well-designed piece of the platform that will live for a minimum of 3 years before getting updated, which is very important to communicate with the engineering team.**
* **An MVF is not the full product. It's a small feature or a fraction of a feature of the final product, which is very important to communicate with the product team and other stakeholders outside the R&D to get their buy-in.**
* **A collection of MVFs build up what the product team call a Milestone.**

### Who can design MVFs:
* Someone who understands the product and the business needs. 
* Someone who has strong software architecture skills to envision how the full system should be designed e2e and knows how to slice it into those small **MVFs**. 
* Most importantly, someone who has excellent communication skills, i.e.,:
  * Knows how to influence non-technical stakeholders to get their buy-in.
  * Knows how to motivate and support the technical team to get them excited to execute the MVFs approach.
While the skill sets are similar from one company to another, the title may differ depending on the company size. This person might be a CTO, an Engineering Manager, a Technical Program Manager, or a System Architect.

## An illustrative example by comparison: (this is an over simplified example)
### Without MVFs:
If you have a small engineering team and are trying to build a scalable data platform without MVFs, you might break the system into:
* Service A: Data Acquisition
* Service B: Data Processing
* Service C: Client App

And your execution plan would follow the logical order of building these services:
* Building Service A to completion
* Then building Service B to completion
* Then building Service C to completion
* Finally launch to market
In this example, you will end up not having enough time between the launch of the new platform and the end of the fiscal year, which will result in missing all the customer and revenue growth goals you had planned for at the beginning of the year.

![Without MVFs Planning](https://github.com/tameralamiri/tameralamiri.github.io/blob/main/docs/static/imgs/2023-08-08-Architecting-for-Success-Redefining-Technical-Growth/without-mvfs-planning.png?raw=true)

### With MVFs:
The three services will be broken down into:
* Service A: Data Acquisition
  * MVF A.1: Acquire 1 data type from 1 data source.
  * MVF A.2: Acquire 1 data type from 2 data sources.
  * MVF A.3: Acquire 2 data types from 2 data sources.
  * MVF A.4: Acquire N data types from N data sources.
* Service B: Data Processing
  * MVF B.1: Store acquired data in raw format and provide interfaces for other services to read.
  * MVF B.2: Normalize acquired data from different sources in standardized format and provide interfaces for other services to read.
  * MVF B.3: Aggregate the different types of normalized data to generate a small set of insights and provide interfaces for other services to read.
  * MVF B.4: Expand the data aggregation to generate a bigger set of enhanced insights and provide interfaces for other services to read.
* Service C: Client Facing App
  * MVF C.1: Build a client view to browse and export the raw data.
  * MVF C.2: Build a client view to browse and export the normalized data.
  * MVF C.3: Build a client view to browse and export the aggregated data.
  * MVF C.4: Build a client view to experiment with the different formats of the data on the platform and generate their own insights.

![With MVFs Planning](https://github.com/tameralamiri/tameralamiri.github.io/blob/main/docs/static/imgs/2023-08-08-Architecting-for-Success-Redefining-Technical-Growth/with-mvfs-planning.png?raw=true)


The MVF model stands to benefit the entire organization. Here are for instance: 
* On the R&D team, instead of being overwhelmed by a big platform to build, they can stay focused on a smaller, digestible piece of software to implement.
* If you are scaling R&D, you can easily start tackling multiple MVFs in parallel.
* The exec team can gain more clarity and understanding of what’s happening in R&D and in turn do better reporting to the board/investors.
* The marketing team will have more content to write about regarding the company’s progress, which will bring in more customers.
