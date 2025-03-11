# AWS Cloud Control API

**Current documentation**



**Topics:**

- Introduction
- What is a Resource Type?
- How to Create Your Own Resource Type

## Introduction

The AWS Cloud Control API offers centralized control over resources within your AWS account. It provides a consistent, programmatic interface for accessing and provisioning these resources, allowing you to interact directly with various resource types through a uniform API.

## What is a Resource Type?

A resource type represents a provisionable artifact within a web service. Examples include:

- An Amazon Elastic Compute Cloud (Amazon EC2) instance
- An Amazon Relational Database Service (Amazon RDS) database instance
- An AWS Identity and Access Management (IAM) policy
- An entire web application

Each resource type adheres to a standardized syntax, supporting some or all of the following lifecycle events:

- Create
- Read
- Update
- Delete
- List (CRUD-L)

You can invoke these CRUD-L event handlers directly using the Cloud Control API, ensuring a consistent API experience.

- Consult the list of public resource types published by AWS and supported by AWS Cloud Control API [here](insert link here if available).

## How to Create Your Own Resource Type

AWS provides hundreds of resource types representing various AWS web service offerings. Now, third-party publishers can also create and make their own resource types available. Resource types developed using the AWS CloudFormation CLI open-source tool are automatically compatible with the Cloud Control API.
