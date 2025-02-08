# 📊 AWS Services Implementation Report

**Date:** April 15, 2024  
**Company:** Abstergo Industries  
**Responsible:** Gabriel Santiago  

---

## 🌟 Introduction

This report outlines the implementation of AWS services at the fictional company **Abstergo Industries**, led by **Gabriel Santiago**. The primary goal of this project was to identify and implement **three key AWS services** to achieve immediate cost optimization and improve operational efficiency.

---

## 🚀 Project Description

The project was divided into **three phases**, each focusing on a specific AWS service. Below, we detail each phase, including the service description, its benefits, and the proposed cost-optimization solution.

---

### **Phase 1: Dynamic EC2 Auto Scaling** ⚖️

- **Service:** EC2 Auto Scaling (Dynamic Scaling)  
- **Description:**  
  EC2 Auto Scaling ensures high availability for your applications by automatically adjusting the number of EC2 instances based on traffic demands. Dynamic scaling responds to real-time changes in workload, ensuring that you have the right amount of compute capacity at all times.  
- **Cost-Optimization Solution:**  
  Implement **dynamic scaling** initially to gather robust metrics on usage patterns. Once sufficient data is collected, transition to **predictive scaling** to further optimize costs. Predictive scaling uses machine learning to forecast traffic and scale resources proactively, reducing the need for over-provisioning and minimizing idle resources.  

---

### **Phase 2: Amazon ElastiCache** 🚀

- **Service:** Amazon ElastiCache  
- **Description:**  
  Amazon ElastiCache is a fully managed in-memory data store and caching service that improves application performance by reducing the load on primary databases. It supports popular engines like **Redis** and **Memcached**, enabling faster data retrieval and reducing latency for frequently accessed data.  
- **Cost-Optimization Solution:**  
  Use **Redis** to cache frequently requested data, reducing the number of repetitive queries to the primary database. This approach not only **lowers database read costs** but also improves response times, leading to a more efficient and cost-effective architecture.  

---

### **Phase 3: AWS Instance Scheduler** ⏰

- **Service:** AWS Instance Scheduler  
- **Description:**  
  The AWS Instance Scheduler automates the start and stop of Amazon EC2 and Amazon RDS instances. By scheduling instances to run only during required hours, this solution significantly reduces operational costs, especially for non-production environments like QA and staging.  
- **Cost-Optimization Solution:**  
  Implement the Instance Scheduler to **automatically stop QA and staging environments** outside working hours (e.g., shutting down at 7 PM and restarting at 8 AM). This ensures that resources are only active when needed, leading to substantial cost savings without impacting productivity.  

---

## 🎯 Conclusion

The implementation of these AWS services at **Abstergo Industries** is expected to deliver **immediate cost reductions** and **improved operational efficiency**. By leveraging dynamic scaling, in-memory caching, and instance scheduling, the company can optimize its cloud infrastructure while maintaining high performance and availability.  

We recommend **continuous monitoring** of these services and exploring additional AWS tools to further enhance cost efficiency and scalability.  

---

## 📝 Attachments

**Signed by:**  
Gabriel Santiago  
Project Lead  
