# Jonathan Schoonhoven

San Francisco, CA

> I make big and small web applications with Python and Javascript that serve millions of requests per minute. I lead complex, cross functional projects that solve big problems. I prioritize simplicity, performance, and test coverage (in that order).

### Lyft, Internal Tools Team, SWE

*April, 2016—Present*

The Internal Tools team builds services for operational tasks like activating, deactivating and paying drivers. They also own Lyft's regional configuration services.

I am the primary owner of Lyft's geospatial service, the second highest traffic service at Lyft. Reduced geospatial average >P99 response time from 150ms to 5ms by improving how we use rtrees and solved timeout issues across Lyft. Responsible for making sure it scales to meet peak demand.

I designed and implemented the tool used to pay bonuses to loyal drivers, which is now processing hundreds of thousands of dollars per week. The service automatically flags questionable bonuses and presents them for review in the front end.

### Lyft, Data Platform Team, SWE

*July, 2015—April, 2016*

The Data Platform team is responsible for Lyft's realtime and batch ETL systems, collecting and structuring hundreds of gigabytes of event data daily.

I designed and implemented the tool used to batch edit and backfill event stream data. By parallelizing the job and using a consumer/producer model, it streams data from/to our DB at 10k events per second.

I massively reduced load on Redshift by moving large ETL jobs to Hive and by dynamically shifting slots/resources between analysts and ETL jobs based on current need.

I dramatically increased performance of slow ETL jobs by implementing concurrency/streaming patterns across the ETL system.

### Change.org, Data Team, SWE

*June, 2012—May, 2015*

The Data Team is responsible for the realtime and batch ETL systems, experimentation service, and the machine learning services used for relevant content and advertising.

I developed Query Builder, a data exploration tool allowing nontechnical users to build complex SQL from a simple UI, then visualize the results. Used heavily throughout the company to build investor decks, make reports for the board, gather data for media stories, forecast ad revenue, and more.

I designed and built Curious, a metrics dashboard app with Node, Backbone & D3. Allows users to create charts with Query Builder or from raw SQL, select a visualization, and have Curious keep the charts up to date. Used primarily by revenue teams and executives to track ad performance.

I built the front end for Change.org's internal Experiment Service with Node & Backbone. From whiteboard through testing to deployment in under two weeks.
