# aws-s3-security-project
Securing AWS S3 Buckets Lab

## 📌 Objective

Secure data in Amazon S3 buckets by implementing cloud security best practices. The project includes creating S3 buckets, enabling server-side encryption, applying IAM-based bucket policies, enabling versioning, and configuring server access logging.

## 🧠 Skills Gained

Configuring Amazon S3 buckets with public access blocked

Enforcing server-side encryption using AWS KMS to protect sensitive data

Implementing IAM roles and bucket policies for least-privilege access

Enabling versioning to maintain file history and recover deleted objects

Configuring server access logging to monitor and audit S3 bucket activity

Using AWS CLI and Management Console to automate and verify security settings

## 🛠️ Tools & Technologies Used

AWS Management Console (S3, IAM, KMS)

AWS CLI for automation

JSON for bucket policy configuration

Screenshots for demonstration

## 🖥️ S3 Bucket Configuration Overview

Component	Details
Bucket Name	my-secure-bucket
Public Access	Block all public access enabled
Encryption	Server-side encryption with AWS KMS
Versioning	Enabled to track and recover object versions
Access Control	IAM-based bucket policies for least-privilege access
Monitoring	Server access logging enabled, logs sent to my-log-bucket

## 🔍 Bucket Policies and Access Control

IAM Roles: Create IAM users with programmatic access for CLI or console usage

Bucket Policies: JSON policies applied to grant read/write permissions to specific users only

Least-Privilege Principle: Users only get permissions required for their task; no blanket access

## 🔒 Encryption, Versioning, and Logging

Server-Side Encryption (SSE-KMS): Protects data at rest using AWS-managed or customer-managed KMS keys

Versioning: Allows object recovery and historical tracking of changes

Server Access Logging: Tracks requests for auditing and monitoring, with logs stored in a separate S3 bucket

## 🖼️ Screenshots

<img width="1358" height="649" alt="Bucket-Creation" src="https://github.com/user-attachments/assets/a1905856-e47d-4680-8987-71072d9698f3" />


📄 Executive Summary

This lab demonstrates securing cloud storage using AWS S3, combining encryption, access control, versioning, and monitoring. By applying IAM policies, KMS encryption, and server access logging, the project simulates real-world practices to protect sensitive data and ensure compliance. Using AWS CLI and Management Console reinforces automation and verification skills in cloud security and DevSecOps practices.
