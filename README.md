# SmartEd Recommender  
*Cloud-Based Personalized Recommendations for Educators and Students*  

## Overview  
This project, developed for **IMT 589 (Spring 2025)**, proposes a cloud-based recommender system — **SmartEd** — designed to transform the University of Washington’s (UW) fragmented academic planning experience. By integrating systems such as MyPlan, Canvas, and DARS into a unified, intelligent platform, SmartEd delivers **personalized course, career, and content recommendations** to both students and faculty  

---

## Industry Context  
The US higher education sector is experiencing rapid digital transformation. Key trends include:  
- AI-driven personalization in academic planning  
- Hybrid/online learning adoption post-COVID  
- Skills-first education models aligning with employability  
- Rising pressure on institutions to balance affordability with innovation

---

## Problem Statement  
UW’s current environment is challenged by:  
- **Outdated on-premise infrastructure** limiting scalability and automation  
- **Fragmented user experience** with disconnected planning tools (MyPlan, Canvas, DARS)  
- **Lack of personalization** for student academic/career journeys  
- **Limited faculty insights** into student progress and market needs

---

## Our Solution: SmartEd Recommender  
SmartEd is a **cloud-native, AI-driven recommender system** hosted on Microsoft Azure. It provides:  
- **For Students**: Personalized course and career path recommendations  
- **For Faculty**: AI-powered content, assignment, and emerging topic suggestions  
- **For UW-IT**: Scalable, secure infrastructure reducing operational burden

Benefits include:  
- Enhanced student retention and graduation rates  
- Revenue growth via tuition premium and higher-value experiences  
- Attraction of grants and corporate partnerships  
- Operational efficiency through automation
---

## Cloud Strategy  

### Short-Term (0–18 months)  
- Migrate selected MyPlan and DARS components to Azure  
- Deploy SmartEd as a pilot with secure integration  
- Launch faculty dashboards using Power BI  
- Create unified authentication with Azure Active Directory

### Long-Term (18 months–5 years)  
- Complete migration of core academic systems to Azure  
- Expand SmartEd with advanced AI features  
- Establish an institutional analytics framework using Azure Synapse  
- Explore hybrid/multi-cloud strategies for resilience and compliance

---

## Architecture  
SmartEd leverages **Microsoft Azure services** for scalability, security, and intelligence:  
- **Identity & Access**: Azure Active Directory  
- **Hosting**: Azure App Service  
- **Data Storage**: Azure SQL Database, Cosmos DB, Blob Storage  
- **AI/ML**: Azure Machine Learning Studio  
- **Integration**: Azure API Management, Logic Apps, Data Factory  
- **Monitoring & Security**: Azure Monitor, Security Center

---

## Deployment Strategy  
- **Phased migration** over 10–15 weeks using Azure DevOps and ARM templates  
- CI/CD pipelines with automated testing, blue-green deployment, and monitoring  
- Role-based access, encryption, and compliance enforcement for FERPA, HIPAA, and GLBA

---

## Compliance & Regulations  
SmartEd ensures alignment with:  
- **FERPA** (student data protection)  
- **HIPAA** (for student health data)  
- **GLBA** (financial aid security)  
- **ADA Section 508** (accessibility standards)
---

## Limitations & Future Work  
- **User Adoption Risk**: Faculty and students may resist AI-driven workflows  
- **Bias in AI Models**: Requires fairness auditing and iterative training  
- **Integration Complexity**: API-based connections across multiple platforms  
- **Future Extensions**:  
  - Expansion to other institutions  
  - Native mobile application  
  - Advanced analytics dashboards  
  - Faculty tools like AI-powered grading assistants

---

## Mockup & User Flow  
- **Students**: Unified dashboard with academic/career planning, skill progress tracking, and AI recommendations  
- **Faculty**: Dashboards showing student performance, course demand, and dynamic content insights  
- **Support**: Chatbots, virtual assistants, and proactive alerts integrated into the user journey

---

## Conclusion  
SmartEd represents a **strategic leap in cloud-powered academic planning**. By unifying UW’s fragmented systems and leveraging Azure’s scalability, SmartEd enhances personalization, improves retention, and drives operational efficiency — aligning student, faculty, and institutional goals in a single intelligent platform
---
