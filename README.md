# AWS Well-Architected Security Pillar Implementation

## Project Overview

This project demonstrates the implementation of the AWS Well-Architected Framework Security Pillar through hands-on AWS labs. The objective was to design and secure a multi-account AWS environment using AWS security best practices, centralized identity management, governance controls, and secure access mechanisms.

## Architecture Goal

Design a secure AWS environment that provides:

* Identity and Access Management
* Least Privilege Access
* Temporary Credentials
* Cross-Account Access
* Centralized Authentication
* Resource Protection
* Governance and Compliance

## AWS Services Used

* AWS IAM
* IAM Roles
* AWS STS
* Amazon EC2
* Amazon S3
* AWS Organizations
* Service Control Policies (SCP)
* AWS IAM Identity Center (SSO)

## Security Concepts Implemented

* Multi-Factor Authentication (MFA)
* Least Privilege Principle
* Temporary Security Credentials
* Cross-Account Access
* Resource-Based Policies
* Organizational Governance
* Single Sign-On (SSO)

## Architecture Diagram

Architecture diagram available in:

architecture-diagram/architecture.png

## Lab Breakdown

### Lab 01 – Secure IAM User Setup

Implemented IAM users, groups, and MFA for secure account access.

### Lab 02 – Least Privilege Policies

Created custom IAM policies to grant only required permissions.

### Lab 03 – EC2 to S3 Access Using IAM Roles

Configured EC2 instance roles to securely access S3 without access keys.

### Lab 04 – Cross Account Access

Implemented secure role assumption using AWS STS and trust policies.

### Lab 05 – AWS Organizations and SCP

Created organizational units and enforced governance using SCPs.

### Lab 06 – IAM Identity Center (SSO)

Configured centralized workforce authentication using AWS SSO.

### Lab 07 – S3 Bucket Policies

Secured S3 resources using resource-based access controls.

## Project Outcome

Successfully implemented a secure AWS environment aligned with the AWS Well-Architected Security Pillar, demonstrating enterprise-grade identity management, governance, access control, and resource security.

## Future Enhancements

* AWS CloudTrail
* AWS Config
* AWS KMS
* Amazon GuardDuty
* AWS Secrets Manager
* VPC Security Controls
