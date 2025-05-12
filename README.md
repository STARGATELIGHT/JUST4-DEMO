# LAW-WEBSITE

---

# Static Website Hosting Guide

This project contains a simple static website designed to teach entry-level engineers how to host a static site using **Amazon EC2** and **Amazon S3**.

## 🌐 Overview

The included HTML/CSS code is a basic static website that serves as a practical example for beginners learning how to:

* Launch and configure an EC2 instance to serve static content via a web server (e.g., Nginx or Apache).
* Upload and host a static website using Amazon S3 with public access or CloudFront distribution.

## 🚀 Use Cases

* Educational purposes: Learn how to deploy websites using AWS services.
* Practice for AWS certifications (e.g., AWS Cloud Practitioner, Solutions Architect – Associate).
* Testing static web content before production deployment.

## 🗂️ Contents

* `index.html`: The main landing page.
* `style.css`: Basic styling for the page.
* Optional images or assets.

## 📖 Getting Started

1. **EC2 Hosting**

   * Launch an EC2 instance (Amazon Linux or Ubuntu).
   * Install and configure a web server (e.g., Nginx).
   * Copy the website files into the web root directory.
   * Allow HTTP access in the EC2 security group.

2. **S3 Hosting**

   * Create an S3 bucket with public access (or configure with CloudFront for secure access).
   * Upload the static files.
   * Enable static website hosting in the bucket properties.

## 🛠 Prerequisites

* AWS account with access to EC2 and S3.
* Basic understanding of terminal/command line.
* Familiarity with HTML/CSS.

## 📄 License

This project is open-source and free to use for educational and training purposes.

---

