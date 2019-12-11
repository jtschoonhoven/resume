# Jonathan Schoonhoven

*Freelance Senior Software Engineer and Experience Designer in San Francisco, California.*

*Available to work part-time and project-based.*

*jtschoonhoven@gmail.com*

> I design big and small web applications that serve millions of requests per minute. I lead complex, cross functional projects that solve hard problems. I design interactive experiences on and offline. I prioritize simplicity, performance, and test coverage (in that order).

### Magnopus, Experience Designer, Narrative Team

*August, 2019—October, 2019 (3 month contract)*

Magnopus is an agency specializing in interactive experience design, VR/AR in particular. They have worked with Disney and NASA, including the virtual production of 2019's Lion King.

My role was split between narrative design and technical API design. Our project was a nonlinear, site-specific adventure game that could be experienced across VR, AR, and RR (real reality). I wrote stories and designed quests that took advantage of this blend of technologies and the particular history of the site. I wrote scripts for interactive characters with widely-branching dialogue trees. I designed the API for these nonlinear quests and worked with the engineering team to implement these.

### Culdesac, Principal SWE, Engineering

*January, 2019—August, 2019*

Culdesac is building the first new neighborhood in the US designed to be entirely car-free. Rather than privately own cars, residents will rely on our platform of payment, delivery and transportation services (integrating Lyft, Uber Eats, Stripe, etc).

I was the first senior hire (2nd overall) to the engineering team. I was tasked with designing this platform from a technical perspective, and I was integral in setting the product direction. I led the product through to beta testing, where it was actively used by tens of real residents to pay rent and fund transportation costs.

### Lyft, Senior SWE, Global Team

*November, 2018—December, 2018*

I was asked to join the Global Team to design and build the systems needed to translate Lyft into new languages. I met with dozens of stakeholders and am the sole author of the official tech spec that now details a full year of engineering work that will affect nearly every team at Lyft. the executive team has named this project a priority for 2018.

I was the lead engineer working on the Translation Service and related libraries and tooling. I designed and created these systems from scratch, and also advised the engineering organization on how to use them effectively. I am the author of our developer guide to translation and localization.

### Lyft, Senior SWE, Internal Tools Team

*April, 2016—November, 2018*

For two years I was the sole owner of Lyft's Tier-0 geospatial service. The service is responsible for core regional configuration such as where Lyft is available and what rides cost. It was the second highest traffic service at Lyft until I added a cache layer. With the cache, the service/client now easily handles 100 million geospatial queries per minute. I also reduced average P99 response time from 150ms to 5ms.

I designed and implemented the payments infrastructure used to pay bonuses to drivers. The system has now processed tens of millions of dollars. The system uses anomaly detection to automatically flag questionable bonuses and present them for review in an Angular front end.

### Lyft, SWE, Data Platform Team

*July, 2015—April, 2016*

The Data Platform team is responsible for Lyft's realtime and batch ETL systems, collecting and structuring terabytes of event data daily.

I designed and implemented the tool used to batch edit and backfill event stream data. By parallelizing the job and using a consumer/producer pattern, it streams data from/to our DB at 10k events per second.

I massively reduced load on Redshift by moving large ETL jobs to Hive and by dynamically shifting slots/resources between analysts and ETL jobs based on current need.

I dramatically increased performance of slow ETL jobs by implementing concurrency/streaming patterns across the ETL system.

### Change.org, SWE, Data Team

*June, 2012—May, 2015*

The Data Team is responsible for the realtime and batch ETL systems, experimentation service, and the machine learning services used for relevant content and advertising.

I developed Query Builder, a data exploration tool allowing nontechnical users to build complex SQL from a simple UI, then visualize the results. Used heavily throughout the company to build investor decks, make reports for the board, gather data for media stories, forecast ad revenue, and more.

I designed and built Curious, a metrics dashboard app with Node, Backbone & D3. Allows users to create charts with Query Builder or from raw SQL, select a visualization, and have Curious keep the charts up to date. Used primarily by revenue teams and executives to track ad performance.

I built the front end for Change.org's internal Experiment Service with Node & Backbone. From whiteboard through testing to deployment in under two weeks.

___
**Tags:** python, javascript, search, geospatial, i18n, translation, data, etl, frontend, backend, full stack, flask, react, angular, backbone, aws, dynamodb, elasticsearch, ec2, s3, microservices, networking
