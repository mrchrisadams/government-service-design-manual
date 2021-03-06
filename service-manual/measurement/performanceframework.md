---
layout: detailed-guidance
title: Performance framework
subtitle: Other metrics your service might measure or track
status: draft
category: measurement
type: guide
audience: 
  primary: service-managers, performance-analysts
  secondary: designers, developers, qa, content-designers
phases:
  - beta
  - live
breadcrumbs:
  -
    title: Home
    url: /service-manual
  -
    title: Measurement
    url: /service-manual/measurement
---
    
This guide aims to empower service managers to design and improve transactional public services. It is based around seven principles, with easy-to-follow checklists to help you get started.

##Understand user needs

In order to improve the performance of a service, you have to analyse and identify the information different audiences will need to assess that performance.

###Checklist

1. Have you identified who your users are?
2. Have you articulated your users’ needs?
3. Have you prioritised services (e.g. by number of users or cost)?

There is typically a hierarchy of interested users, all of whom will have different metrics for success. Technical staff might have operational and optimisation concerns, while senior management and ministers will have more strategic and comparative concerns.These needs will be reflected in the organisation’s business objectives.

##Decide what to measure

Develop simple, actionable and collectable metrics based on your understanding of user needs. Identify where that information will come from and how frequently it will be needed.

###Checklist

1. Have you developed metrics and Key Performance Indicators (KPIs)?
2. Are your metrics simple, actionable and collectable?
3. Have you mapped your metrics to the relevant audience?
4. Have you identified where your metrics will be sourced from?
5. Do you know how frequently performance information is required by your users?

Key Performance Indicators (KPIs) will be few in number - typically around five - and are top-line indicators of how well a service is performing. For almost all transactional services, these are likely to include the volume of transactions, the cost per transaction and success (or conversion) rate - the proportion of users attempting to use a transactional service that successfully complete the task.
There will be many other, more granular metrics that will be useful for different audiences.

It's good practice to record every event generated by the system even if it’s not currently of interest. Don’t obsess over what to measure: measure everything (where it is cost-effective to do so). This maximises the flexibility to come back later and revise the chosen metrics and tailor data visualisations to different audiences. This information could come from a variety of sources, for example Oracle and Excel for CRM and finance databases, Google Analytics for web testing and optimisation tools, or Nagios and Pingdom for system monitoring.

##Install and configure platforms

Install and configure reporting platforms that meet your needs. Where possible, use platforms that enable the data to be piped automatically into other systems. Using APIs (Application Programming Interfaces) will stop you having to input data manually and allows for aggregation across multiple platforms.

###Checklist
1. Have you installed web analytics software?
2. Have you configured your web analytics software with the appropriate conversion funnels?
3. Do you have the capability to run user satisfaction surveys?
4. Do you have the capability to do A/B testing and multivariate testing?
5. Do you have software installed for monitoring service uptime and performance?
6. Can you generate custom performance data based on system-generated events?

There are a number of open source products available as well as paid alternatives. If you are using a third party supplier, ensure that you have access to the raw data behind the measures specified in the contract and make sure data is not thrown away after a short period of time.

##Establish a baseline

Establish a 'baseline' based on current performance trends by channel, against which changes to the service will be judged. This will help you pinpoint the effect of your initiatives, and identify what worked.

###Checklist

1. Have you measured your current performance?
2. Have you compared your performance with similar types of service (e.g. by transaction category)?
3. Do you know who your users are in terms of age, disability, socio-economic group and internet usage?

It is good practice to look at performance trends over time, rather than take a snapshot at a particular point in time. Peaks and dips in performance are then measured relative to this base (or trend) line which helps to identify the effect of communications or design initiatives. It also reveals seasonal variations in performance.
Benchmarking against other services can also provide a useful context for judging performance. By comparing to other similar services (e.g. requesting a license or reporting information) you know whether the service is significantly better or worse than expected. A complete list of the government’s transactional services is available on GOV.UK.
You need to know who your users are to be able to determine whether they are likely to need assisted digital to help them use the digital service. The proportion of users needing assisted digital will vary based on the users of the particular service. For example, a higher proportion of people applying for incapacity benefits are more likely to need assistance with digital services than those needing to pay their road tax.

##Aggregate data

Collect and aggregate performance information from multiple sources and across multiple channels. Make sure you understand what this will mean in terms of system requirements.

###Checklist
1. Have you collected data on costs, usage and performance?
2. Have you collected performance data from digital and non-digital channels?
3. Do you know how many people use the service, by channel?
4. Have you aggregated performance data to enable it to be easily combined?

Combining data often reveals useful insights, for example into service efficiency (eg cost per transaction and total cost to serve) or proportional usage by channel (eg percentage digital uptake vs post, phone etc).

Be aware though that combining data from different data sources can lead to huge storage requirements: large, data-driven organisations now talk about storage in terms of petabytes, the equivalent of one million gigabytes. However, there are cost-effective solutions to this problem already in place. For example, the Hadoop software framework was developed to enable collection, aggregation and querying of such huge data stores, and is based on work done by Google and Yahoo to develop search engines.

##Analyse and visualise data

Communicate performance information to your users through the appropriate dashboards, reports and alerts. For the 4 KPIs set out in the digital strategy this will be done through the performance platform. Highlight specific segments that you know users are interested in, and make sure that your visualisations are simple, actionable and contain minimal amounts of chart junk.

###Checklist
1. Have you done any segmentation (i.e. analysed performance data by segment)?
2. Have you designed the appropriate dashboards, reports and alerts?
3. Are your data visualisations visible to their intended audience?
4. Have you followed best practice design principles for data visualisation?

Typical segments include:
* Channel used to access service: through which channel(s) did the user find out about and attempt to use the service?
* New vs. repeat visitors: are first time users behaving differently to those who have used the service before?
* Geographical region: how popular is the digital service by region and how does that compare with online penetration in general?
* Product type: does the user experience vary depending on the type of product or service?
* Value: is performance dependent on the monetary value of the service being sought?

Dashboards are objective-focused and will help inform decisions, often with the help of real-time data.
Reports provide regular, scheduled snapshots of data and tend to require extra context and time to digest.
Alerts are used to inform the users about a change or an event, often using attention-grabbing delivery mechanisms.

By making your visualisations clearly visible you maximise the likelihood that the information will be acted upon - and services thereby improved.
Best practices include:
* keeping charts plain: don’t use shading, 3D or other distracting effects
* removing clutter: don’t use trend lines, grid lines, unnecessary labelling
* not using pie charts: they require more space and are harder to read than bar charts
* using text where a chart adds nothing.

##Monitor, iterate, and improve

Test a range of performance improvement initiatives and monitor to see which work well. These can be piloted on a subset of your users to minimise risk. Implement the best performing solutions widely and then repeat this process relentlessly: what you measure will change over the course of a product or project's lifetime.

###Checklist
1. Are you monitoring and acting upon user feedback?
2. Have you done any A/B testing or multivariate testing?
3. Have you evaluated the effectiveness of your performance reports?
4. Have you taken an iterative approach to developing your service?

Any service that meets user needs will include an element of user feedback. This should be monitored and acted upon so as to continually improve the service for users.
A range of options are available for improving the overall performance of a service. The following examples are based on the 4 Ps of marketing:
* Price: can the price be changed, for example to attract people to the digital channel?
* Product: can the user experience be improved (eg from user feedback, user testing, A/B testing, multivariate testing)?
* Placement: can the digital service URL be placed on printed materials and voice recordings?
* Promotion: can greater use of email and social media be used to promote repeated use of the digital service?

Taking an iterative approach to service development increases the pace of improvement and minimises the risk of failure. Don’t wait until the end to do this, it should happen continuously throughout the process.

##Further reading

###Understand user needs

The NAO report [Digital Britain One: Shared infrastructure and services for government online] (http://www.nao.org.uk/publications/1012/digital_britain_one.aspx) identified that there was a lack of information on the costs and associated benefits of digital services.

###Decide what to measure

[Occam’s Razor](http://www.kaushik.net/avinash/) is an excellent blog by Avinash Kaushik with loads of useful advice on metrics, KPIs and analytics. See for example [this article on how to set good performance indicators](http://www.kaushik.net/avinash/rules-choosing-web-analytics-key-performance-indicators/).

###Install and configure platforms

The [Google Analytics Help Centre](http://support.google.com/analytics/?hl=en) is a useful resource if you use that particular platform, see for example this guide to setting up goals and funnels.

Blog article by Morgan Brown with a [good discussion on user flows and conversion funnels](http://uxdesign.smashingmagazine.com/2012/01/04/stop-designing-pages-start-designing-flows/).

###Establish a baseline

[This article](http://www.guardian.co.uk/money/2010/dec/22/amazon-top-consumer-satisfaction) in The Guardian shows online customer satisfaction scores for retailers. These scores are based on the Customer Satisfaction Index.
###Aggregate data
[Great article](http://radar.oreilly.com/2010/06/what-is-data-science.html) by Mike Loukides on the role of the data scientist.

[These webinars](http://www.cloudera.com/blog/2011/01/2010-cloudera-apache-hadoop-webinars/) by Cloudera provide a useful introduction to Hadoop.

Total Cost to Serve is a [method (PDF, 79k)](http://www.hmrc.gov.uk/research/cost-of-time.pdf) for calculating the cost of a transaction for both the service provider and the user. HMRC have developed a method for calculating the cost of users time when interacting with government. This is important because some channels may be quicker to use than others.

###Analyse and visualise data

[Designing with Data](http://www.fivesimplesteps.com/products/a-practical-guide-to-designing-with-data) is an excellent book by Brian Suda which helps you to design beautiful and powerful data visualisations.

[Juice Analytics](http://www.juiceanalytics.com/) is a great website with loads of useful resources on how to design and develop useful data visualisations and dashboards.

Edward Tufte’s [The Visual Display of Quantitative Information](http://www.edwardtufte.com/tufte/books_vdqi) is a seminal work on data visualisation and introduces the concept of chartjunk.

The [Flowing Data](http://flowingdata.com/) blog by Nathan Yau is a useful source of data visualisation news.

The [D3 Gallery](https://github.com/mbostock/d3/wiki/Gallery) is a stunning collection of data visualisations.

[Nicely presented overview](http://selection.datavisualization.ch/) of some of the tools available for data visualisation.

###Monitor, iterate and improve

This [article in Wired](http://www.wired.com/business/2012/04/ff_abtesting/all/1) shows how A/B testing was used to good effect in Obama’s election campaign.

This [article in eConsultancy](http://econsultancy.com/uk/blog/2454-q-a-lovefilm-s-craig-sullivan-on-a-b-and-multi-variate-testing) shows how multivariate testing was used to improve conversion rates at Lovefilm.
