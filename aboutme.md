---
layout: page
title: About me
subtitle: "Carlo Goleta | DevOps Engineer"
permalink: /
description: "Welcome! I'm Carlo, a passionate and experienced DevOps Engineer with a strong background in designing and implementing scalable cloud infrastructure using AWS services. With expertise in CI/CD pipelines, containerization, monitoring, and automation tools, I help organizations streamline their development processes and improve overall system performance."
---

<header class="masthead text-center">
  <div class="container">
    <h1>Carlo Goleta</h1>
    <p class="text-muted">DevOps Engineer | AWS Certified Solutions Architect - Associate</p>
  </div>
</header>

<section id="about" class="bg-light py-5">
  <div class="container text-center">
    <h2>About Me</h2>
    <p>I'm a dedicated and experienced DevOps Engineer with a strong background in designing, implementing, and managing cloud infrastructure using Amazon Web Services (AWS). My expertise includes:</p>
    <ul class="list-inline">
      <li><i class="fas fa-code mr-2"></i> Continuous Integration/Continuous Delivery pipelines</li>
      <li><i class="fab fa-docker mr-2"></i> Containerization using Docker and Amazon Elastic Container Service (ECS)</li>
      <li><i class="fas fa-chart-line mr-2"></i> Monitoring and logging with tools like CloudWatch, ELK Stack, and Grafana</li>
      <li><i class="fab fa-jenkins mr-2"></i> Automation using Jenkins, Ansible, Terraform, and AWS CDK</li>
    </ul>
  </div>
</section>

<section id="projects" class="py-5">
  <h2 class="text-center mb-4">Case Studies</h2>
  {% for post in site.posts %}
    {% if post.categories contains 'case-study' %}
      <!-- Include the case study markdown file here -->
      {{ post.content | from_liquid }}
    {% endif %}
  {% endfor %}
</section>
