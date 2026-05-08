---
layout: page
title: Companies
---
## Companies
<html>
<head>
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
    <h2><strong>Echo Global Logistics</strong></h2>
    <small><i>Industry: Transportation Management System /Logistics</i></small>
    <p></p>
    <small>(Rated the #1 Third-Party-Logistic provider 10 Years In a Row!)</small>
    <p></p>
    Echo Global Logistics is a transportation management technology company that connects businesses needing to ship freight with a network of carriers that move goods across the country. Through its digital logistics platform, Echo helps streamline the process of quoting, booking, tracking, and managing shipments. Echo offers three flagship products—<b>EchoDrive, EchoShip, and EchoTrak</b>—each designed to simplify different parts of the shipping and carrier experience.
    <p></p>
    <b>EchoDrive</b> is a web-based portal built for carriers. The platform allows dispatchers, owner-operators, and drivers to search for loads, submit bids, book shipments, manage assignments, track freight, and receive payments—all in one easy-to-use interface. With built-in real-time tracking, EchoDrive reduces the need for manual check-in calls and helps carriers manage loads more efficiently.
    <p></p>
    <b>EchoShip</b> is a self-service shipping platform designed for businesses that need to move freight. It enables users to quickly generate quotes, compare carriers by cost, transit time, coverage, and service level, book shipments, track deliveries, manage invoices, and oversee their entire shipping process from a single dashboard.
    <p></p>
    <b>EchoTrak</b> is Echo’s mobile application that provides shippers with logistics visibility and control while on the go. The app allows users to track shipments, manage logistics activity, and access real-time shipment data directly from their mobile devices.
    <p></p>
    Together, these platforms create a connected logistics ecosystem that improves transparency, efficiency, and collaboration between shippers and carriers.
    <p></p>
    <h5>Accomplishments and Summary</h5>
    <p></p>
    Part of an 8-member team responsible for owning and enhancing 2 microservices within an event-driven, publish-subscribe architecture supporting the full shipment lifecycle, including the Shipment Tracking Service and Notification Service. Leveraged Kafka publisher-subscribe topics such as “Booked,” “In Transit,” “Arrived,” and “Delivered” to enable multiple downstream services to independently process shipment tracking, ETA calculation, and notification events.
    <p></p>
    Supported customer communication and event fan-out by integrating Amazon Simple Notification Service (SNS) into the platform. Enabled Kafka consumers to process shipment events and publish targeted notifications to SNS topics, distributing updates across SQS queues, AWS Lambda functions, and mobile push notification services. Utilized RabbitMQ to support asynchronous processing and background task management; once delivery event were confirmed, messages were queued to trigger downstream workflows and customer notification services.
    <p></p>
    Developed automated unit testing suites using JUnit and Mockito to validate event-processing workflows, business logic, and API behavior prior to deployment. Utilized Docker containers for application deployment and Kubernetes for orchestration, enabling horizontal scaling of microservices during peak shipping periods. Configured Kubernetes to improve resiliency through automatic container restarts and workload balancing across nodes. Managed source control and CI/CD workflows using Git and Jenkins, enabling automated builds, deployments, and rollback strategies across dev and prod environments.
    <p></p>
    Utilized both relational and non-relational databases based on application use cases. Utilized relational databases to store shipment transactions and order records and developed optimized SQL queries, joins, and indexing strategies to improve data retrieval performance. Utilized non-relational database for high-volume tracking events, enabling flexible schema design and rapid scalability. Also integrated Elasticsearch into the platform to enhance search performance by indexing shipment events, tracking logs, and API activity, enabling operations teams and customers to quickly search shipments by tracking number, carrier, location, or status.
    <p></p>
    <small>Other Responsibilities:</small>
    <p></p>
    Develop RESTful APIs used by internal systems, carrier integrations, and customer facing apps like EchoShip and EchoTrak’s mobile app. 
    <p></p>
    Implemented multithreading strategies to process shipment events and ETA calculations concurrently, reducing high latency. 
    <p></p>
    Tested AI-driven libraries to make ETA predication models and analyze historical shipment patterns, traffic conditions, and carrier performance to generate more accurate delivery estimates. 
    <p></p>
    <p></p>
    <h2><strong>Fidelity Information Services</strong></h2>
    <small><i>Industry: Financial Technology</i></small>
    <p></p>
    <small>(FIS works with 95% of the worlds leading banks! In 2019, FIS became the largest payment company in the world. )</small>
    <p></p>
    <b>Fidelity Information Services</b> is a global financial technology company that provides a broad range of solutions supporting the world’s financial ecosystem. Its offerings include <b>Merchant Solutions, Banking Solutions, and Capital Markets Solutions</b>, which help businesses, banks, and financial institutions operate more efficiently. Through its technology platforms, FIS plays a key role in advancing the digital transformation of the financial economy—enhancing how the world pays, banks, and invests.
    <p></p>
    The <b>Capital Markets</b> division focuses on providing technology, software, and services for <b>buy-side</b> and <b>sell-side</b> firms, including <b>trading</b>, <b>risk-management</b>, <b>compliance</b>, and <b>securities</b> processing. It enables automation in asset management, private equity, and wealth management, catering to financial institutions to improve efficiency in trading and investment operations. Top solutions from FIS Capital Market division includes from Trading and Securities:<i> FIS Securities Processing Suite</i>, from Private Equity and Wealth: <i>FIS Private Capital Suite</i>, and from Risk and Compliance: <i>FIS Capital Markets Compliance Suite</i>. Services include: GenAI and robotics to automate processes, target segments for large global banks, asset managers, and hedge funds for increasing efficiency investment operations, modular, cloud-ready, and scalable technology to speed up product development and customer onboarding, and a cleared derivatives solution for prediction markets.
    <p></p>
    Part of the Capital Market division, <b>InvestOne</b> (formerly known as <b>FIS Investment Accounting Manager</b>) is a powerful, real-time investment, comprehensive <b>SaaS-based investment accounting and administration platform</b> providing fully scalable, modular, middle-to-back solution designed for <b>asset managers</b>, <b>fund administrators</b>, <b>custodian banks</b>, and <b>insurance companies</b>. The platform enables organizations to process complex portfolio accounting in real time while serving as a centralized system of record for transaction data. It supports a wide range of investment types and helps automate accounting workflows, improving accuracy, efficiency, and reporting across investment operations. InvestOne supports intricate calculations and data extraction requirements. The <i>Expense Calculator</i> can construct complex formulas to support changing expense requirements for fixed, management and performance fees. It can improve portfolio management and stakeholder relationship with timely access to accurate data.
    <p></p>
    <p></p>
    <h2><strong>BlueCross BlueShield of Illinois</strong></h2>
    <small><i>Industry: Healthcare</i></small>
    <p></p>
    <small>(1 in 3 americans are covered by BlueCross BlueShield.)</small>
    <p></p>
    <b>Blue Cross Blue Shield Association</b> is one of the largest health insurance networks in the United States, providing coverage to more than <b>115 million people nationwide.</b> The BCBS system consists of 33 independent, community-based, and locally operated health insurance companies that collectively deliver healthcare coverage across the country.
    <p></p>
    BCBS companies offer a wide range of health insurance plans, including <b>individual and family coverage, employer-sponsored plans, Medicare and Medicaid options, and plans available through the Affordable Care Act marketplace.</b> Through their extensive national network of doctors, hospitals, and healthcare providers, BCBS organizations provide members with broad access to medical care while maintaining a strong focus on local service and community-based support.
    <p></p>
    Together, the BCBS network combines national reach with locally tailored healthcare solutions, helping millions of Americans access affordable and reliable health coverage.
</body>
</html>