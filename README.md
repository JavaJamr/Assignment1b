# Assignment 1b DevPulse Cloud Telemetry Landing & Responsive Pricing Dashboard

## Description

Assignment 1b is a webpage designed to follow **Von Neumann principles** and the website formatting techniques that we have learned thus far in class.

The project also incorporates **User Stories** to help plan and determine the design and functionality of the webpage, similar to how a real-world application would be developed.

## How to Use It

You can navigate the page and select the different buttons and links to move to different parts of the webpage.

### User Interaction Flow

- **Starting State:** Initial viewport upon visiting the site.
- **Action 1:** First user interaction, such as clicking a landmark anchor link.
- **Action 2:** Second user interaction, such as navigating to and selecting an intended tier card.
- **Action 3:** Third user interaction, such as inputting data into constrained form elements.
- **Action 4:** Final user interaction that dispatches the request.
- **Terminal State:** Visual feedback or confirmation received by the user.

## User Stories

The following User Stories were used to determine what should be designed and included in the webpage.

### Story 1 | Value Proposition & Sticky Navigation

> As an infrastructure engineer landing on DevPulse, I want to review core value metrics, access landmark navigation links, and see a high-contrast "Deploy Free Cluster" CTA above the fold.

### Story 2 | Infrastructure Feature Grid

> As a DevOps lead, I want to scan key platform capabilities (Latency Tracking, Log Aggregation, Auto-Remediation) in a structured content layout.

### Story 3 | Compute Tier Comparison

> As an engineering manager, I want to compare three cluster hosting tiers ("Developer", "Pro Cluster", "Enterprise Dedicated") with an elevated visual badge on the most popular plan.

### Story 4 | Workload Estimation Form

> As a systems architect, I want to enter our node count and log throughput requirements into a form with numeric bounds to verify tier compatibility.

### Story 5 | API Provisioning Lead Capture

> As a developer, I want to submit a pre-registration form with required fields to receive API sandbox provisioning details.

## Updated and Complete Component Tree
### Component Tree

```text
<html>
│
├── <head>
│   ├── <meta charset>
│   ├── <meta name>
│   ├── <title>
│   └── <link>
│
├── <header>
│   │
│   ├── <a> Brand Logo
│   │   └── <span> Logo Icon
│   │
│   └── <nav>
│       ├── <a> Compare Prices
│       ├── <a> Simulation
│       └── <a> Deploy Free Cluster
│
├── <main>
│   │
│   ├── <section> Hero
│   │   │
│   │   ├── <h1> Core Value Metrics
│   │   │
│   │   ├── <section> Hero Information
│   │   │   │
│   │   │   ├── <div> Hero Text
│   │   │   │   ├── <h2> Latency Tracking
│   │   │   │   └── <p> Latency Tracking Description
│   │   │   │
│   │   │   ├── <div> Hero Text
│   │   │   │   ├── <h2> Log Aggregation
│   │   │   │   └── <p> Log Aggregation Description
│   │   │   │
│   │   │   └── <div> Hero Text
│   │   │       ├── <h2> Auto-Remediation
│   │   │       └── <p> Auto-Remediation Description
│   │   │
│   │   └── <a> Start Your Free Trial Now
│   │
│   ├── <section> Compare Prices
│   │   │
│   │   ├── <article> Developer
│   │   │   ├── <h3> Developer
│   │   │   ├── <p> $399 USD/month
│   │   │   ├── <ul> Tier Features
│   │   │   │   ├── <li> Free 1 Month Trial Version
│   │   │   │   ├── <li> Latency Tracking
│   │   │   │   ├── <li> Log Aggregation
│   │   │   │   ├── <li> Auto-Remediation
│   │   │   │   ├── <li> 10 nodes
│   │   │   │   └── <li> 200 megabyte split throughput
│   │   │   │
│   │   │   └── <a> Try Now
│   │   │
│   │   ├── <article> Pro Cluster
│   │   │   ├── <div> Most Popular
│   │   │   ├── <h3> Pro Cluster
│   │   │   ├── <p> $1,999 USD/month
│   │   │   ├── <ul> Tier Features
│   │   │   │   ├── <li> Latency Tracking
│   │   │   │   ├── <li> Log Aggregation
│   │   │   │   ├── <li> Auto-Remediation
│   │   │   │   ├── <li> 100 nodes
│   │   │   │   ├── <li> 1 gb dedicated throughput per node
│   │   │   │   └── <li> Advanced optimization tools
│   │   │   │
│   │   │   └── <a> Buy Now
│   │   │
│   │   └── <article> Enterprise Dedicated
│   │       ├── <h3> Enterprise Dedicated
│   │       ├── <p> $4,999 USD/Month
│   │       ├── <ul> Tier Features
│   │       │   ├── <li> Latency Tracking
│   │       │   ├── <li> Log Aggregation
│   │       │   ├── <li> Auto-Remediation
│   │       │   ├── <li> Unlimited Nodes
│   │       │   ├── <li> Best In Service Priority Throughput
│   │       │   ├── <li> Advanced Optimization Tools
│   │       │   └── <li> Dedicated Service Agent
│   │       │
│   │       └── <a> Invest Now
│   │
│   └── <section> Buy Button / Simulation
│       │
│       └── <form>
│           ├── <h3> Your Server Requirements
│           │
│           ├── <div> Question Answer
│           │   ├── <label> Number Of Nodes
│           │   └── <input>
│           │
│           ├── <span> Input Hint
│           │
│           ├── <div> Question Answer
│           │   ├── <label> Throughput in kbit/s
│           │   └── <input>
│           │
│           ├── <span> Input Hint
│           │
│           ├── <div> Question Answer
│           │   ├── <label> Target Tier Selection
│           │   └── <select>
│           │       ├── <option> Free Trial
│           │       ├── <option> Developer
│           │       ├── <option> Pro Cluster
│           │       └── <option> Enterprise Dedicated
│           │
│           └── <div> Form Buttons
│               ├── <button> Simulate
│               └── <button> Buy Now
│
└── <footer>
    │
    ├── <a> Brand Logo
    │   └── <span> Logo Icon
    │
    └── <nav>
        ├── <a> Back To Top
        ├── <a> Compare Prices
        ├── <a> Simulation
        └── <a> Start Your Trial Today
