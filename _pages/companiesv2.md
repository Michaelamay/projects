---
layout: page
title: Companies
---
## Companies
<html>
<head>
    <script src="https://kit.fontawesome.com/6cddb4e091.js" crossorigin="anonymous"></script>
    <style>
        main {
                margin: 0 auto;
                max-width: 76rem !important;
        }
        .minor-font {
            font-size: 14px;
            color: gray;
        }
        .display {
            background-color: skyblue;
            border: 1px solid gray;
            width: 49px;
            float: right;
        }
        .flex-container {
            display: flex;
            justify-content: center; /* Centers horizontally */
            align-items: center;     /* Centers vertically */
            height: 100vh;           /* Example: takes up full viewport height */
        }
        h5 {
            font-weight: 500;
        }
    </style>
</head>
<body>
    <hr>
    <h2 id="snorkelai" style="margin: 0;"><strong>Snorkel AI</strong><i class="fa-solid fa-robot" style="margin-left: 6px;"></i></h2>
    <small>Industry: Artificial Intelligence / Programmatic Data Development / Business-Productivity Software</small>
    <p></p>
    Snorkel AI pioneers’ programmatic data development, shifting enterprises away from manual labeling toward production-quality, specialized AI models built on proprietary data. Unlike conventional pipelines optimized for volume, Snorkel targets distributional gaps, benchmark blind spots, and tasks where correctness is difficult to define. Partnering with frontier AI labs, Snorkel builds research-grade datasets and evaluation systems assessed through task-specific rubrics and programmatic checks, utilizing AI evaluation experts to develop complex coding tasks for Terminal-Bench.
    <p></p>
    <span style="font-weight:700;">Accomplishments and Summary</span>
    <p></p>
    Design and develop complex multi-step terminal benchmark tasks for Project Terminus and Terminal Bench, targeting state-of-the-art AI models including GPT-5.2 and Claude Opus 4.6<p></p>
    Author expert Oracle solutions and deterministic Python unit test suites to validate AI agent task completion in containerized environments<p></p>
    Build and configure Docker environments using Docker files and docker-compose for reproducible AI agent evaluation tasks.<p></p>
    Evaluate and iterate on AI agent task difficulty through structured rubric development, targeting specific model accuracy thresholds across 10 agent runs<p></p>
    Ensure submission quality by passing multi-stage programmatic CI checks, LLM-as-Judge evaluations, and manual peer review processes<p></p>
    <span style="font-weight:700;">Technologies and Tools Used:</span>
    <p></p>
    Python, Bash, Scripting, Dev Ops, Command Line Interface, Docker Containers, Visual Studios, Project Terminus, Terminal-Bench, GPT, and Claude Opus.
    <p></p>
    <p></p>
    <h2 id="echo" style="margin: 0;"><strong>Echo Global Logistics</strong><i class="fa-solid fa-truck" style="margin-left: 6px;"></i></h2>
    <small>Industry: Transportation Management System /Logistics - (Rated the #1 Third-Party-Logistic provider 10 Years In a Row!)</small>
    <p></p>
    Echo Global Logistics is a transportation management technology company that connects businesses needing to ship freight with a network of carriers that move goods across the country. Through its digital logistics platform, Echo helps streamline the process of quoting, booking, tracking, and managing shipments. Echo offers three flagship products—<span style="font-weight:525;">EchoDrive, EchoShip, and EchoTrak</span>—each designed to simplify different parts of the shipping and carrier experience.
    <p></p>
    <span style="font-weight:525;">EchoDrive</span> is a web-based portal built for carriers. The platform allows dispatchers, owner-operators, and drivers to search for loads, submit bids, book shipments, manage assignments, track freight, and receive payments—all in one easy-to-use interface. With built-in real-time tracking, EchoDrive reduces the need for manual check-in calls and helps carriers manage loads more efficiently.<span style="font-weight:525;"> EchoShip</span> is a self-service shipping platform designed for businesses that need to move freight. It enables users to quickly generate quotes, compare carriers by cost, transit time, coverage, and service level, book shipments, track deliveries, manage invoices, and oversee their entire shipping process from a single dashboard.<span style="font-weight:525;"> EchoTrak</span> is Echo’s mobile application that provides shippers with logistics visibility and control while on the go. The app allows users to track shipments, manage logistics activity, and access real-time shipment data directly from their mobile devices.
    <p></p>
    <span style="font-weight:700;">Accomplishments and Summary</span>
    <p></p>
    Part of an 8-member team responsible for owning and enhancing 2 microservices within an event-driven, publish-subscribe architecture supporting the full shipment lifecycle, including the Shipment Tracking Service and Notification Service. Leveraged Kafka publisher-subscribe topics such as “Booked,” “In Transit,” “Arrived,” and “Delivered” to enable multiple downstream services to independently process shipment tracking, ETA calculation, and notification events.
    <p></p>
    Supported customer communication and event fan-out by integrating Amazon Simple Notification Service (SNS) into the platform. Enabled Kafka consumers to process shipment events and publish targeted notifications to SNS topics, distributing updates across SQS queues, AWS Lambda functions, and mobile push notification services. Utilized RabbitMQ to support asynchronous processing and background task management; once delivery event were confirmed, messages were queued to trigger downstream workflows and customer notification services.
    <p></p>
    Developed automated unit testing suites using JUnit and Mockito to validate event-processing workflows, business logic, and API behavior prior to deployment. Utilized Docker containers for application deployment and Kubernetes for orchestration, enabling horizontal scaling of microservices during peak shipping periods. Configured Kubernetes to improve resiliency through automatic container restarts and workload balancing across nodes. Managed source control and CI/CD workflows using Git and Jenkins, enabling automated builds, deployments, and rollback strategies across dev and prod environments.
    <p></p>
    Utilized both relational and non-relational databases based on application use cases. Utilized relational databases to store shipment transactions and order records and developed optimized SQL queries, joins, and indexing strategies to improve data retrieval performance. Utilized non-relational database for high-volume tracking events, enabling flexible schema design and rapid scalability. Also integrated Elasticsearch into the platform to enhance search performance by indexing shipment events, tracking logs, and API activity, enabling operations teams and customers to quickly search shipments by tracking number, carrier, location, or status.
    <p></p>
    <span style="font-weight:700;">Other Responsibilities:</span>
    <p></p>
    Developed RESTful APIs used by internal systems, carrier integrations, and customer facing apps like EchoShip and EchoTrak’s mobile app. 
    <p></p>
    Implemented multithreading strategies to process shipment events and ETA calculations concurrently, reducing high latency. 
    <p></p>
    Tested AI-driven libraries to make ETA predication models and analyze historical shipment patterns, traffic conditions, and carrier performance to generate more accurate delivery estimates. 
    <p></p>
    <span style="font-weight:700;">Technologies and Tools Used:</span>
    <p></p>
    Java, C#, Amazon Simple Notification Service (SNS), microservices, Kafka, RabbitMQ, testing suites, Docker, Kubernetes, CI/CD, SQL, relational databases, non-relational databases, APIs, multithreading, AI Libraries, Jenkins, Elasticsearch, publish-subscribe architecture, event-driven systems.
    <p></p>
    <p></p>
    <h2 id="fidelity" style="margin: 0;"><strong>Fidelity Information Services</strong><i class="fa-solid fa-credit-card" style="margin-left: 6px;"></i></h2>     
    <small>Industry: Financial Technology - (FIS works with 95% of the worlds leading banks! In 2019, FIS became the largest payment company in the world.)</small>
    <p></p>
    Fidelity Information Services is a global financial technology company that provides a broad range of solutions supporting the world’s financial ecosystem. Its offerings include <span style="font-weight:525;">Merchant Solutions, Banking Solutions, and Capital Markets Solutions</span>, which help businesses, banks, and financial institutions operate more efficiently. Through its technology platforms, FIS plays a key role in advancing the digital transformation of the financial economy—enhancing how the world pays, banks, and invests.
    <p></p>
    The <span style="font-weight:525;">Capital Markets</span> division focuses on providing technology, software, and services for <span style="font-weight:525;">buy-side</span> and <span style="font-weight:525;">sell-side</span> firms, including <span style="font-weight:525;">trading</span>, <span style="font-weight:525;">risk-management</span>, <span style="font-weight:525;">compliance</span>, and <span style="font-weight:525;">securities</span> processing. It enables automation in asset management, private equity, and wealth management, catering to financial institutions to improve efficiency in trading and investment operations. Top solutions from FIS Capital Market division includes from Trading and Securities:<i> FIS Securities Processing Suite</i>, from Private Equity and Wealth: <i>FIS Private Capital Suite</i>, and from Risk and Compliance: <i>FIS Capital Markets Compliance Suite</i>. Services include: GenAI and robotics to automate processes, target segments for large global banks, asset managers, and hedge funds for increasing efficiency investment operations, modular, cloud-ready, and scalable technology to speed up product development and customer onboarding, and a cleared derivatives solution for prediction markets.
    <p></p>
    Part of the Capital Market division, <span style="font-weight:525;">InvestOne</span> (formerly known as <span style="font-weight:525;">FIS Investment Accounting Manager</span>) is a powerful, real-time investment, comprehensive <span style="font-weight:525;">SaaS-based investment accounting and administration platform</span> providing fully scalable, modular, middle-to-back solution designed for <span style="font-weight:525;">asset managers</span>, <span style="font-weight:525;">fund administrators</span>, <span style="font-weight:525;">custodian banks</span>, and <span style="font-weight:525;">insurance companies</span>. The platform enables organizations to process complex portfolio accounting in real time while serving as a centralized system of record for transaction data. It supports a wide range of investment types and helps automate accounting workflows, improving accuracy, efficiency, and reporting across investment operations. InvestOne supports intricate calculations and data extraction requirements. The <i>Expense Calculator</i> can construct complex formulas to support changing expense requirements for fixed, management and performance fees. It can improve portfolio management and stakeholder relationship with timely access to accurate data.
    <p></p>
    <span style="font-weight:700;">Accomplishments and Summary</span>
    <p></p>
    Worked on a complex legacy Profit and Loss (PnL) calculation system that provided traders and risk managers with accurate, real-time insights into portfolio performance, exposure, and financial risk across multiple asset classes.
    <p></p>
    Utilized Java and Spring to develop microservices that separated the platform into a Trade Ingestion Service, Pricing Service, and PnL Calculation Service. Implemented a hybrid architecture combining traditional RESTful APIs for synchronous request-response communication with asynchronous event-driven workflows for background processing and service decoupling. Utilized Kafka as the event-streaming platform for Trade Events and Market Price Update Events, publishing events to Kafka topics consumed by the PnL Calculation Service to continuously recompute portfolio PnL as new market data arrived. Prevented resource-intensive operations from blocking critical financial calculations by utilizing RabbitMQ for asynchronous processing and queuing downstream tasks for report generation and alert notification services. Stored transactional and historical PnL data within a relational SQL database to support reporting, analytics, and historical portfolio analysis.
    <p></p>
    Utilized Docker to containerized Java microservices and deployed applications into Kubernetes clusters running on AWS EC2 infrastructure to support scalability, workload balancing, and automated recovery of failed services. 
    <p></p>
    Managed AWS cloud infrastructure utilizing EC2 and RDS to support scalable backend processing, and relational database management. Managed source control and collaborative development workflows through Git and integrated CI/CD pipelines using Jenkins to automate builds, unit testing, deployments, and release management.
    <p></p>
    <span style="font-weight:700;">Other Responsibilities:</span>
    <p></p>
    Worked in Angular and Typescript to develope UI components.
    <p></p>
    Developed automated unit testing suites using JUnit and Mockito to validate event-processing workflows prior to deployment, improving application stability and reducing production defects.
    <p></p>
    Incorporated multithreading strategies in Java to parallelize calculations across multiple portfolios simultaneously.
    <p></p>
    <span style="font-weight:700;">Technologies and Tools Used:</span>
    <p></p>
    Java, Spring Boot, microservices, asynchronous event-driven workflows, Kafka, RabbitMQ, relational SQL database, Docker, AWS EC2, AWS RDS, Kubernetes, CI/CD pipelines, unit testing, deployments, Git, multithreading strategies. 
    <p></p>
    <p></p>
    <h2 id="bcbs" style="margin: 0;"><strong>BlueCross BlueShield of IL, MT, NM, OK & TX</strong><i class="fa-solid fa-hospital" style="margin-left: 6px;"></i></h2>
    <small>Industry: Healthcare - (1 in 3 americans are covered by BlueCross BlueShield.)</small>
    <p></p>
    <span style="font-weight:525;">Blue Cross Blue Shield Association</span> is one of the largest health insurance networks in the United States, providing coverage to more than <span style="font-weight:525;">115 million people nationwide.</span> The BCBS system consists of 33 independent, community-based, and locally operated health insurance companies that collectively deliver healthcare coverage across the country.
    <p></p>
    BCBS companies offer a wide range of health insurance plans, including <span style="font-weight:525;">individual and family coverage, employer-sponsored plans, Medicare and Medicaid options, and plans available through the Affordable Care Act marketplace.</span> Through their extensive national network of doctors, hospitals, and healthcare providers, BCBS organizations provide members with broad access to medical care while maintaining a strong focus on local service and community-based support.
    <p></p>
    The BCBS network combines national reach with locally tailored healthcare solutions, helping millions of Americans access affordable and reliable health coverage.
    <p></p>
    <span style="font-weight:700;">Accomplishments and Summary</span>
    <p></p>
    Worked on an Open Enrollment Automation platform designed to streamline member enrollment, eligibility verification, policy updates, and document processing, with the objective of reducing manual operations and supporting millions of healthcare transactions during peak enrollment periods.
    <p></p>
    Utilized C# and Python to develop a microservices-based distributed system supporting healthcare enrollment operations. Used C# to build core enrollment services including member registration and benefits validation workflows. Utilized Python for automation scripting, OCR processing, AI/ML-based document classification, and backend data processing tasks. 
    <p></p>
    Utilized OCR technology to automate healthcare document processing by extracting data from uploaded insurance forms and identification documents. Integrated AI/ML models into enrollment workflows to classify documents, validate enrollment information, and detect incomplete submissions before policy finalization.
    <p></p>
    <span style="font-weight:700;">Other Responsibilities:</span>
    <p></p>
    Utilized an event-driven architecture to process enrollment requests asynchronously through queue-based workflows. Published and consumed enrollment lifecycle events such as “Application Submitted,” “Eligibility Verified,” “Policy Approved,” and “Enrollment Completed,” enabling scalable, decoupled communication.
    <p></p>
    Wrote optimized SQL queries to retrieve member enrollment records, policy information, and benefits data from relational databases. Developed stored procedures and indexing strategies to improve enrollment lookup.
    <p></p>
    Developed RESTful APIs used to communication with third-part provider systems.
    <p></p>
    Utilized Azure for application deployment.
    <p></p>
    <span style="font-weight:700;">Technologies and Tools Used:</span>
    <p></p>
    Python, C#, microservices, distributed systems, automation, OCR, AI/ML, SQL, RESTful APIs.
</body>
</html>