# Data As A Product

## Introduction
Data has now overtaken oil as the world’s [most valuable resource](https://www.economist.com/leaders/2017/05/06/the-worlds-most-valuable-resource-is-no-longer-oil-but-data), according to The Economist. And like oil, data needs to be processed to get the most out of it. Data products are what enable users to extract value from this resource. 

For the past few decades, most companies have kept data in an organizational silo; recently like within the past 10-20 years, there has been traction on that side of the business where companies have been working and utilizing better tooling, more diverse roles, and a clearer understanding of data’s full potential, many businesses have come to view the entire ecosystem as a fully formed element of the company tech stack.  

It's time to get value out of that, it's time to treat data as first-class citizen like any other product or service. Data tells stories, which help business and clients in decision-making process for better outcomes.

The most forward-thinking teams are adopting a new paradigm: treating data like a product. This is a hot topic in the data community right now; [Data as a Product](https://martinfowler.com/articles/data-mesh-principles.html#DataAsAProduct) (DaaP) is one of the four Data Mesh principles.

## Some thoughts from industry leaders about DaaP

"There are two schools of thoughts; one focuses on external or internal product or service that generates data, meaning that the data—including the entire pipeline—is part of the product. So it must be subject to the same level of rigor as the application code such as SLA, testing, observability … etc. the second one focuses on the output of any codebase that’s serving a customer as a product."

"There needs to be a data product manager role who focuses on answering questions like
* What data exists?
* Who needs this data?
* Where is this data flowing to/from?
* What purpose does this data serve?
* Is there a way to make it easier to work with/access this data?
* Is this data compliant and/or actionable?
* How can we make data more useful to more people at the company, faster?"

"Data as a Product (DaaP) is the simplest model to understand: the job of the data team is to provide the data that the company needs, for whatever purpose, be it making decisions, building personalized products, or detecting fraud. This might just sound like data engineering, but it’s not: Data Scientists also provide data as a product, just packaged in a different way. Some important characteristics of this model:
* Data has an SLA (figuratively) from the entire data team, not just data engineering
* Data flow is unidirectional, from the data team to the company
* Domain expertise has limited benefits for data team members”

"Data products can be sorted into three categories
1. Data as a service: examples like weather app on your phone, or the real-time stock market ticker running across the bottom of your television screen. 
2. Data-enhanced products: such as converting a car into a self-driving vehicle or smart clothing that can respond to touch or track data from its user
3. Data as insights: refers to products that analyze the data “behind the scenes” in order to improve the performance or another aspect of a product. This could be something like Google Analytics

## Ways to Apply DaaP approach
1. Be intentional when adopting data as a product as it requires a shift in mindset that leads to meaningful outcomes
2. Gain stakeholder alignment early and often especially if your customers are also your stakeholders
3. Apply a product management mindset to how you build, monitor, governance, access control and measure product quality
4. Invest in [self-service tooling](https://martinfowler.com/articles/data-mesh-principles.html#Self-serveDataPlatform), which is another principle of Data Mesh, that allows business users and clients the ability to self-serve and meet their own data needs for better decision-making
5. Prioritize data quality and reliability for the entire ecosystem from ingestion to consumer-facing data deliverables; set clear data SLAs, SLIs and SLOs and adjust as you move forward; invest in automation and scalable data reliability for better data quality
6. Find the right team structure for your data organization; you may structure the data team based on your business needs; however, a "hub and spoke" model is famous for growing companies that need to move fast. In this structure, a centralized data platform team handles infrastructure and data quality, while decentralized, embedded analysts and engineers deal with semantic layers and apply data to the business.
