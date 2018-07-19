# Jonathan Schoonhoven

*Senior Backend Software Engineer in San Francisco, California.*

*Available for consultation and contracts.*

*jtschoonhoven@gmail.com*

> I design big and small web applications that serve millions of requests per minute. I lead complex, cross functional projects that solve hard problems. I prioritize simplicity, performance, and test coverage (in that order).

### Lyft, Global Team

*November, 2018—Present*

I was asked to join the Global Team to design and build the systems needed to translate Lyft into new languages. I met with dozens of stakeholders and am the sole author of the official tech spec that now details a full year of engineering work that will affect nearly every team at Lyft. the executive team has named this project a priority for 2018.

I am the lead engineer working on the Translation Service and related libraries and tooling. I designed and created these systems from scratch, and also advise the engineering organization on how to use them effectively. I am the author of our developer guide to translation and localization.

### Lyft, Internal Tools Team

*April, 2016—November, 2018*

For two years I was the sole owner of Lyft's Tier-0 geospatial service. The service is responsible for core regional configuration such as where Lyft is available and what rides cost. It was the second highest traffic service at Lyft until I added a cache layer. With the cache, the service/client now easily handles 100 million geospatial queries per minute. I also reduced average P99 response time from 150ms to 5ms.

I designed and implemented the payments infrastructure used to pay bonuses to drivers. The system has now processed tens of millions of dollars. The system uses anomaly detection to automatically flag questionable bonuses and present them for review in an Angular front end.

### Lyft, Data Platform Team

*July, 2015—April, 2016*

The Data Platform team is responsible for Lyft's realtime and batch ETL systems, collecting and structuring terabytes of event data daily.

I designed and implemented the tool used to batch edit and backfill event stream data. By parallelizing the job and using a consumer/producer pattern, it streams data from/to our DB at 10k events per second.

I massively reduced load on Redshift by moving large ETL jobs to Hive and by dynamically shifting slots/resources between analysts and ETL jobs based on current need.

I dramatically increased performance of slow ETL jobs by implementing concurrency/streaming patterns across the ETL system.

### Change.org, Data Team

*June, 2012—May, 2015*

The Data Team is responsible for the realtime and batch ETL systems, experimentation service, and the machine learning services used for relevant content and advertising.

I developed Query Builder, a data exploration tool allowing nontechnical users to build complex SQL from a simple UI, then visualize the results. Used heavily throughout the company to build investor decks, make reports for the board, gather data for media stories, forecast ad revenue, and more.

I designed and built Curious, a metrics dashboard app with Node, Backbone & D3. Allows users to create charts with Query Builder or from raw SQL, select a visualization, and have Curious keep the charts up to date. Used primarily by revenue teams and executives to track ad performance.

I built the front end for Change.org's internal Experiment Service with Node & Backbone. From whiteboard through testing to deployment in under two weeks.

___
**Tags:** python, javascript, search, geospatial, i18n, translation, data, etl, frontend, backend, full stack, flask, react, angular, backbone, aws, dynamodb, elasticsearch, ec2, s3, microservices, networking
