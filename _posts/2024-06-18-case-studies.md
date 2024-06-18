---
layout: post
title: "Case Studies"
permalink: /case-studies/
gh-badge: [star, fork, follow]
tags: [case-studies,aws,cicd]
comments: true
mathjax: true
author: Carlo Goleta
---

## Case Study 1: Vortex.ph & Tinbo.ph Infrastructure Migration and Automation

<section id="projects" class="py-5 text-center">
  <!-- <h2>My Work</h2>
  <p>Here are some examples of projects I've worked on:</p> -->
  <div class="container d-flex justify-content-between flex-wrap">
    <!-- Include other project cards here -->
    <div class="card mb-4" style="width: calc(50% - 1rem);">
      <img src="/assets/img/vortex.ph_.png" alt="Vortex.ph" width="100%">
      <!-- Include project details here -->
    </div>
    <div class="card mb-4" style="width: calc(50% - 1rem);">
      <img src="/assets/img/tinbo.ph_.png" alt="Tinbo.ph" width="100%">
      <!-- Include project details here -->
    </div>
  </div>
</section>

<!-- ### Project Name -->
Vortex.ph and Tinbo.ph are B2B2C web applications that underwent an infrastructure migration from on-premises to Amazon Web Services (AWS) with the implementation of a Continuous Integration/Continuous Delivery (CI/CD) pipeline using AWS CodePipeline and CloudFormation.

### Role and Responsibilities
As a DevOps Engineer, I was responsible for designing and implementing the infrastructure migration of Vortex.ph and Tinbo.ph from an on-premises setup to Amazon Web Services (AWS). Additionally, I implemented a CI/CD pipeline using AWS CodePipeline and CloudFormation for efficient deployment and cost savings.

### Challenges and Solutions
#### Challenge: Reducing Deployment Time and Decreasing Operational Expenses
- Migrating infrastructure to AWS allowed us to leverage their scalable cloud services such as Elastic Beanstalk, Amazon RDS, and ElastiCache.
- Implementing a CI/CD pipeline using CodePipeline and CloudFormation enabled automated deployments upon code changes, significantly reducing deployment time and eliminating the need for manual intervention.
#### Challenge: Ensuring Improved Security through AWS's Robust Security Features
- By migrating to AWS, we could take advantage of their comprehensive security offerings such as Virtual Private Cloud (VPC), Identity and Access Management (IAM), and Security Groups. These services allowed us to secure our infrastructure by controlling access to resources at the network level and implementing granular permissions for users and roles.

### Tools and Technologies Used
- AWS CodePipeline
- Amazon Lambda
- CloudFormation
- Amazon RDS
- ElastiCache
- VPC
- IAM
- Security Groups

### Outcomes and Results
The successful implementation of the infrastructure migration to AWS and CI/CD pipeline using CodePipeline and CloudFormation allowed for significant improvements in deployment time, cost savings through eliminating on-premises hardware and maintenance costs, and improved security through robust AWS features. This setup enabled efficient deployments upon code changes while reducing potential downtime due to manual intervention.

![Vortex.ph & Tinbo.ph Infrastructure Migration Architecture](/assets/images/vortex_tinbo_architecture.png)

---

## Case Study 2: Monitoring and Auto-Scaling for Microservices Architecture using Amazon CloudWatch

<!-- ### Project Name -->
In this project, I was responsible for designing and implementing a monitoring system using Amazon CloudWatch and enabling auto-scaling for Elastic Container Service (ECS) clusters to ensure optimal performance and cost efficiency. This setup provided real-time visibility into the infrastructure's health and performance while reducing potential downtime due to capacity issues.

### Role and Responsibilities
As a DevOps Engineer, I was responsible for designing and implementing a monitoring system using Amazon CloudWatch and enabling auto-scaling for Elastic Container Service (ECS) clusters.

### Challenges and Solutions
#### Challenge: Ensuring Optimal Performance and Cost Efficiency by Automatically Adjusting Resources Based on Demand
- Implementing a monitoring system using Amazon CloudWatch allowed us to gain real-time visibility into the infrastructure's health and performance metrics such as CPU utilization, network traffic, and container instance statuses.
- Enabling auto-scaling for ECS clusters allowed us to automatically adjust resources based on demand, ensuring optimal performance while reducing potential downtime due to capacity issues.

### Tools and Technologies Used
- Amazon CloudWatch
- Elastic Container Service (ECS)
- Auto Scaling