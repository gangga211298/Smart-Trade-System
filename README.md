# Smart Trade System

## Background
Astrido Toyota Kebon Jeruk achieved only **9%** of its **10% trade-in sales target**. Internal evaluations highlighted two main challenges:
- Salespeople lacked organization in the trade-in process, with each relying on their own methods and external partners.
- No digital tools were available to monitor database utilization and trade-in activities, resulting in suboptimal prospect management.

To overcome these issues, the **Smart-Trade System** was developed as an integrated digital platform.  
The system consolidates database utilization, enables real-time monitoring of sales activities, and provides transparency in managing both trade-in prospects and new car sales.  
With Smart-Trade, every opportunity can be tracked and followed up more effectively, supporting the achievement of trade-in targets and improving overall sales performance.

---

## Objectives
- Provide an **integrated digital platform** that enables salespeople to easily access, update, and manage prospects.
- **Monitor database utilization in real time**, ensuring every stage from follow-up to deal closing is clearly tracked.
- Enhance **transparency and accountability** at both the individual and team levels.
- Support the achievement of **trade-in and new car sales targets** by ensuring every prospect is followed up effectively and efficiently.

---

## Tools & Technology
- **AppSheet** → Main application for data cleansing, follow-up activities, and customer prospecting.
- **Google Sheets** → Centralized database for storing all input from the sales team.
- **Looker Studio** → Interactive monitoring dashboards for reporting and supporting the PDCA cycle.

---

## Flow of Use
The Smart-Trade System involves the sales team at Astrido Toyota Kebon Jeruk, including **Salesmen, Sales Supervisors (SPV), and Branch Managers (BM).**

<img width="1280" height="720" alt="Slide1" src="https://github.com/user-attachments/assets/37ba9c7e-d42c-4285-97de-c733b2f49312" />

### Flow Process:
1. **Lead Generation**  
   - Data sourced from Astrido Toyota Kebon Jeruk sales.  
   - Combined with non-Astrido Toyota sales data from vehicles serviced at Astrido Toyota Kebon Jeruk.  

2. **Lead Distribution**  
   - Data distributed to salespeople according to their focus on specific vehicle models and types.  

3. **Data Cleansing**  
   - Salespeople classify the database into **Active** and **Passive**.  

4. **Passive Database Handling**  
   - If number inactive → process ends.  
   - If the car has been sold → transferred as leads for **GR & BP service** (if customer owns another car).  

5. **Active Database Handling (Prospecting)**  
   - Active customers proceed to prospecting.  
   - Results categorized into **Hot, Medium, Low prospects**.  

6. **Prospect Categorization**  
   - **Low** → directed as leads for GR & BP service.  
   - **Medium** → remains as trade-in leads but requires further approach.  
   - **Hot** → immediately processed as priority trade-in candidates.  

7. **Closing & PDCA**  
   - **SPK** → process completed (closing).  
   - **Pending** → evaluation & PDCA required.  
   - **Lost** → evaluation & PDCA required.  

---

## Monitoring & Dashboard
The entire Smart-Trade System workflow is fully integrated and can be monitored in **real-time** through an **interactive dashboard**.  
This dashboard presents key insights such as:  
- Database cleansing status  
- Prospect distribution (**Hot, Medium, Low**)  
- Follow-up activities  
- Closing results  

With this visibility, **Management, Supervisors, and Sales** are empowered to make faster, more accurate, and data-driven decisions to maximize both trade-in and new car sales potential.

- **Application Demo**: [AppSheet Link](https://www.appsheet.com/start/abb7cda7-cfe2-40b3-83f7-487dd56b1f55)  
  (Username: *Gangga* | Password: *Gangga*)  

<img width="1280" height="720" alt="Slide2" src="https://github.com/user-attachments/assets/e6e14a6a-65de-41bb-b721-3ed32742f8cd" />
<img width="1280" height="720" alt="Slide3" src="https://github.com/user-attachments/assets/08d7b11e-a0c8-44f0-838e-6a6ecf4089d5" />


- **Dashboard**: [Looker Studio Link](https://lookerstudio.google.com/reporting/59b9cd81-03d6-4802-869b-33f7b8a4e249)  
![pdf_page-0001](https://github.com/user-attachments/assets/e19d835f-42e2-40ce-95e1-d23814762b9e)

---

## Results & Insights
The implementation of the **Smart-Trade System** has successfully streamlined database distribution, prospecting, and monitoring processes that were previously managed manually using Excel.

With this system:
- Salespeople can easily perform cleansing, prospecting, and follow-ups directly through the application.  
- Supervisors can monitor the progress of each salesperson in real-time, identify obstacles, and execute **PDCA** more effectively.  
- Branch Managers have access to an interactive dashboard that displays:  
  - Database cleansing status (**Active vs. Inactive**)  
  - Prospect distribution (**Hot, Medium, Low**)  
  - Follow-up & customer engagement activities  
  - Conversion rates to closing status (**SPK, Pending, Lost**)  
  - **PDCA summary** for pending & lost customers  

<img width="1280" height="720" alt="Slide5" src="https://github.com/user-attachments/assets/0b9dc82c-e4b2-41a7-9b36-4be95fb77958" />


👉 With this system, processes that were previously **manual, fragmented, and difficult to monitor** are now **automated, integrated, and transparent.**

---

## Project Achievements
The **Smart Trade System** is a key component of the **Trade-Cycle Management (TCM)** project at Astrido Toyota Kebon Jeruk, serving as a **Pilot Project**.  

Achievements include:
- Direct review (**genba**) by the **BOD of Astrido and TAM**  
- **1st Place Winner** at the 2023 **Regional Kaizen Innovation Marathon (RKIM)**  
- **Replicated (Yokoten)** to 17 other Astrido Toyota branches  
- Became the **benchmark for TCM implementation** across all Toyota dealers in Indonesia

<img width="1280" height="720" alt="Slide4" src="https://github.com/user-attachments/assets/6a4c2613-4855-4d45-b0a0-7c0e119d6a7f" />

---

## Key Learnings
From this project, I gained several key insights:
- **Digitalization drives efficiency** – Transitioning from manual processes to digital systems accelerates data distribution, improves accuracy, and enables real-time monitoring.  
- **Structured database utilization is crucial** – Segmenting by model and type makes the database more organized, ensuring prospects are more targeted.  
- **Visibility improves decision-making** – Interactive dashboards allow SPVs and Branch Managers to quickly identify bottlenecks and implement more effective PDCA cycles.  
- **Sales engagement is maximized through prioritization** – Monitoring Hot, Medium, and Low prospects enables more personalized and strategic follow-up.  
- **Integration ensures alignment** – With **AppSheet, Google Sheets, and Looker Studio** seamlessly connected, all stakeholders share a single, consistent source of data.  
