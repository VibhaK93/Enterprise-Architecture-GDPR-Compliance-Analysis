# Enterprise-Architecture-GDPR-Compliance-Analysis

The project explores the advancements in technology and the concerns surrounding privacy in the context of data storage systems. It specifically delves into San Francisco based start-up, a software service provider aiding small businesses, focusing on the data architecture for a burger restaurant chain on the U.S. east coast. Despite primarily serving U.S. clients, the analysis shows potential GDPR compliance as start-up expands its services in Europe. The GDPR, effective since May 25, 2018, mandates data protection for EU organizations or those processing data related to EU individuals, aiming to enhance the safeguarding of personal data and its free movement.

###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Stakeholders Analysis
 ![Stakeholders Analysis](https://github.com/VibhaK93/Enterprise-Architecture-GDPR-Compliance-Analysis/assets/146596962/c0427edd-a60e-4e33-a5ea-b389885474cb)


 ###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Context Level Architecture Analysis

This is the Context Level Diagram of Startup's Customer Engagement System, which revolves around business patrons engaging, maintaining, and satisfying them by analyzing their purchasing patterns to develop and execute relevant marketing campaigns.

![Context Level Data Architecture Analysis](https://github.com/VibhaK93/Enterprise-Architecture-GDPR-Compliance-Analysis/assets/146596962/655c3245-ae1a-4e2e-898d-16a009fbf155)


 ###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Customer Engagement System Lifecycle (Level 0)

This Level 0 data flow diagram illustrates the end-to-end Customer Engagement System Lifecycle, starting from order placement by Business Patrons and culminating in the receipt of marketing materials via SMS and email.

![Data Flow Diagram_Level 0](https://github.com/VibhaK93/Enterprise-Architecture-GDPR-Compliance-Analysis/assets/146596962/86abcb95-8e92-4d8a-8c4e-a6eb3c54c449)

 ###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Customer Engagement System Lifecycle (Level 1)

This Level 1 data flow diagram illustrates the Enhanced Customer Engagement process which is an extension of the Level 0 Customer Engagement System Data Flow Diagram mentioned previously.

![Data Flow Diagram_Level 1](https://github.com/VibhaK93/Enterprise-Architecture-GDPR-Compliance-Analysis/assets/146596962/7d4afeaf-5995-43fd-a513-cd7d8d23a9b1)



 ###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GDPR Compliant Data Architecture
Enhance Customer Engagement Process with GDPR compliance (Level 1)

This Level 1 Enhance Customer Engagement Process has been modified to be GDPR compliant.

![GDPR Compliant Data Architecture](https://github.com/VibhaK93/Enterprise-Architecture-GDPR-Compliance-Analysis/assets/146596962/ef7da487-8e23-47b6-a114-da9886991e16)



 ###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Conclusion: 
Key finding reveals GDPR noncompliance in the collection of patrons' personally identifiable data at the POS terminal without their consent, lacking facilities for GDPR maintenance. The Customer Engagement System managed by this startup currently lacks substantial GDPR compliance measures.

 ###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Recommendations:
To achieve GDPR compliance, implement the following changes:

1) Obtain patron consent at the Toast POS terminal during data capture.
2) Inform patrons about the purpose of data collection.
3) Provide facilities for patrons to initiate data protection requests, such as obtaining their data copy, requesting modifications, unsubscribing, or complete deletion.

 ###  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Benefits of Implementation:
Implementing these changes, despite the majority of this startup's customers being in the U.S, offers several advantages:

1) Reduced cost of data management with a common architecture for all customers.
2) Attraction of more customers from Europe through GDPR compliance.
3) Proactive compliance fosters trust, potentially expanding the customer base.
