# Hi there! I'm Ajay Shankar 👋

### Big Data Engineer & Cloud Architect

I’m a passionate Big Data Engineer and Cloud Architect skilled in **Java, Python, SQL, PySpark, Hadoop, Airflow**, and **AWS**. I leverage my expertise to craft scalable data solutions and optimize cloud infrastructures.

### 🎓 Education
- **Master of Science in Information Technology and Management**, The University of Texas at Dallas - Expected May 2025
- **Bachelor of Technology in Computer Science and Engineering**, Aditya College of Engineering and Technology, India - May 2023

### 🚀 Skills & Technologies
- **Programming Languages:** Java, Python, JavaScript, JSON, Pandas, Data Structures & Algorithms
- **Data Engineering:** SQL, PostgreSQL, Apache PySpark, Apache Airflow, Spark Performance Tuning, Hadoop, Hive, Sqoop
- **Cloud Computing:** AWS (S3, RDS, EMR, Glue, Athena, LakeFormation, Lambda, Elastic Beanstalk, EC2, IAM, VPC, CloudFront, EFS, CloudWatch, ELB, ASG) and Azure (Blob Storage, Data Lake Gen2, Data Factory, HDInsight, Databricks, Azure Pipelines)
- **Tools & Platforms:** Linux, Windows, Git, GitHub

### 🏆 Certifications
- AWS Cloud Practitioner
- AWS Solutions Architect - Associate
- AWS Developer - Associate
- Azure Fundamentals

### 🔍 Notable Projects
- **[ArXiv Spark Project](https://github.com/AjaX-05/ArXiv-metadata-Analysis):** Led a Databricks project optimizing the ArXiv metadata dataset in HDFS. Reduced processing time by 36% with advanced data handling and optimization techniques.
- **[GHTorrent Analytics (RDD)](https://github.com/AjaX-05/GitHub-Torrent-Analysis):** Analyzed data from the GHTorrent dataset using Apache Spark's RDD (Resilient Distributed Datasets) API. The analysis includes extracting and processing information about GitHub repositories, transactions, and failed HTTP requests. GHTorrent is an offline mirror of data from the GitHub REST API, capturing most data related to pull requests on GitHub, excluding the actual code.
- **[End-to-End Cloud Data Pipeline for Zillow Data Analytics](https://github.com/AjaX-05/End-to-End-Cloud-Data-Pipeline-for-Zillow-Data-Analytics):** Developed a comprehensive data pipeline using AWS services. The project involved building a pipeline to extract, transform, and load Zillow data using AWS Lambda, orchestrated by Apache Airflow, and visualized with QuickSight. Configured AWS Redshift for data warehousing and integrated security best practices for API keys.

### 📫 Contact Me
- Email: [majaysakthishankar@gmail.com](mailto:majaysakthishankar@gmail.com)
- LinkedIn: [Ajay Sakthi Shankar](https://www.linkedin.com/in/ajay-sakthi-shankar/)
- X: [AjaySakthiShan](https://x.com/AjaySakthiShan)
- LeetCode: [ajaysakthishankar](https://leetcode.com/u/ajaysakthishankar/)

### 💪 Fun Fact
I’m a **Gym Freak**! When I’m not immersed in data or cloud technologies, I’m hitting the gym.

---

## Learnings
Throughout this project, I have gained valuable insights and experience in the following areas:
- **End-to-End Data Pipelines:** Understanding the integration of multiple AWS services to create a seamless data pipeline.
- **AWS Lambda:** Implementing serverless functions for data processing and transformation.
- **Apache Airflow:** Automating and orchestrating complex workflows with DAGs.
- **Data Transformation:** Handling and converting data formats between JSON and CSV using Python.
- **Data Warehousing:** Configuring and managing data in Amazon Redshift.
- **Data Visualization:** Creating impactful visualizations and reports using AWS QuickSight.
- **Security Best Practices:** Managing sensitive information, such as API keys and credentials, securely within the project.

## Mistakes and Resolutions
During the project, I encountered a few challenges:
- **Initial Setup Issues:** I initially created S3 buckets and Lambda functions in different regions, leading to failures in data processing. I resolved this by recreating the resources in the same region.
- **EC2 Instance Region Mismatch:** I created an EC2 instance in a region different from where S3 and Lambda were located, which caused issues with the S3ToRedshift operator. I took a snapshot of the EC2 instance and migrated it to the correct region, which resolved the issue.

These experiences taught me the importance of consistent regional configurations and highlighted the need for thorough testing and validation of cloud resources.

