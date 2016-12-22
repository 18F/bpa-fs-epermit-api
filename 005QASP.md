# PERFORMANCE BASED QUALITY ASSURANCE SURVEILLANCE PLAN (QASP)

=============================================================

{{ Forest Service e-permitting Application Protocol Interface}}

## 0.0 INTRODUCTION

------------

This Quality Assurance Surveillance Plan (QASP) has been developed to evaluate contractor actions while implementing the Performance WorkS tatement (PWS). It is designed to provide an effective surveillance method of monitoring contractor performance for each listed objective on the Performance Requirements Matrix in the call order. It also provides a systematic method to evaluate the services the contractor is required to furnish.

## 1.0 STANDARD

--------

The contractor is responsible for management and quality control actions to meet the terms of the call order. The role of the COR/ACOR is quality assurance to ensure call order standards are achieved. The contractor shall perform all work required in a satisfactory manner in accordance with the requirements of the PWS. The COR/ACOR shall notify the CO for appropriate action if it is likely that the contractor will not achieve successful final delivery of the software code in accordance with the performance objectives and acceptable quality levels (AQLs) identified below.

### 1.1 PERFORMANCE REQUIREMENTS MATRIX

-------------------------------

The COR/ACOR will evaluate the performance objectives through surveillance as reflected below by reviews and acceptance of work products and services. As indicated, the COR/ACOR will assess progress towards the final delivered software code. Note that the performance requirements listed below are required for the final deliverable.

However, the sprints and incremental delivery of code will be assessed by the Government to ensure that the contractor is on a path to successful final delivery.

Deliverable or Required Services Performance Standard(s):

**Deliverable or Required Services** | **Performance Standard(s)** | **Acceptable Quality Level (AQL)** | **Method of Surveillance**

----------- | ---------------- | -------------- | ---------------

Tested Code | Code delivered under the order must have substantial test code coverage and a clean code base. | Minimum of 90% test coverage of all relevant code | Combination of manual review and automated testing, using agreed-upon publicly-available SaaS products

Accessible | Client-side rendering must conform with section 508 standards. | 0 errors reported for 508 Standards using an automated scanner and 0 errors reported in manual testing | http://squizlabs.github.io/HTML\_CodeSniffer/ or https://github.com/pa11y/pa11y

Deployed | Code must successfully build and deploy into staging environment. | Successful build with a single command | Combination of manual review and automatic testing

Documented | All dependencies (and licenses for dependencies) are listed and all major functions are documented. | All dependencies are listed and the licenses are documented. Software/source code is documented. System diagram is provided. | Combination of manual review and automatic testing

Available | Code must be stored in a version-controlled open-source repository. | All of the code needed to run the front end of the prototype must be available. | 18F will assess code availability.

User research | Usability testing and other user research methods must be conducted at regular intervals throughout the development process (not just at the beginning or end). | Artifacts from usability testing and/or other research methods with end-users are available at the end of every applicable sprint, in accordance with the vendor’s research plan. | 18F will evaluate the artifacts based on a research plan provided by the vendor at the end of the second sprint.

Secure | Code must be free of medium- and high-level static and dynamic security vulnerabilities | Clean tests from a static testing SaaS, such as Gemnasium, and from OWASP ZAP, and/or documentation explaining any false positives. | https://pages.18f.gov/before-you-ship/

### 1.2 PROCEDURES

----------

The COR/ACOR, along with the 18F Product Lead and the product owner, will inspect all tasks required by the call order to ensure contractor compliance with the call order requirements at the conclusion of each sprint, which shall have a length of two weeks or less. Delivery will occur by pull request from the contractor’s repository to the 18F repository. If inspection results are satisfactory, the pull request will be merged; otherwise, deficiencies will be noted in the pull request or through issues as described below. The COR/ACOR may find the delivery satisfactory even though further work is required, provided that the specific requirements of the sprint are met.

At the conclusion of each sprint, the COR/ACOR, along with the 18F Product Lead and the product owner, will review the completed user stories and related functionality. Incomplete or inadequate code and user stories will be noted in a mutually agreed-upon issue tracker, such as Trello or GitHub Issues, and links to each issue shared with the CO. The contractor may respond in that tracker as appropriate, addressing the accuracy and validity of the defect as well as any planned corrective action (if not already noted). The contractor team will discuss and document actions to prevent recurrence in their sprint retrospectives.

At the conclusion of the period of performance, a similar procedure will be followed to document discrepancies and to assess overall performance.

If any of the services do not conform to the call order requirements, the COR/ACOR may require the contractor to perform the services again in conformity with call order requirements. Any user stories that are not accepted must be completed in the next sprint, unless the product owner and 18F product manager agree to move it to a later sprint. The COR/ACOR shall not certify satisfactory performance for the call order until all defects have been corrected. When the defects in services cannot be corrected by re-performance, the Government may:

1) Require the contractor to take necessary action to ensure that future performance conforms to call order requirements; and,

2) Reduce the call order price to reflect the reduced value of the services performed. The COR/ACOR shall, in addition to providing documentation to the CO, maintain a complete quality assurance file. The file will contain copies of all reports, evaluations, recommendations, and any actions relating to the Government’s performance of the quality assurance function, including originals of all surveillance activity checklists. All such records will be retained for the life of the call order. The COR/ACOR shall forward these records to the CO at completion or termination of the call order.

### 1.3 ACCEPTANCE OF SERVICES

----------------------

Acceptance of services shall be based upon compliance with performance standards described in the PWS and surveillance procedures described in this QASP. Before approving/certifying any contractor invoices, the COR/ACOR will verify that all invoiced services have been performed in compliance with call order requirements. The COR/ACOR shall not certify satisfactory performance for the call order until all defects have been corrected.

## 2.0 KICK-OFF and DAILY ACTIVITIES

----------------------

### 2.1 Post Award Orientation Conference

The Government's team, CO, COR/ACOR, the 18F Product Lead and the Product Owner will hold a Kick-Off Meeting/Post-Award Conference with the the contractor. Ideally, this will be physically located in Washington, DC, but may be done virtually with contractor’s team and other relevant Government staff to review and clarify the project’s objectives, expectations from the Government, and address any questions the contractor may have. Discussion topics shall include, but not be limited to:

-   Introduction of the contractor and Government Staff;

-   Understanding of the workflow;

-   Project management expectations;

-   Agreement on communication methods; and

-   Discussion of any other relevant specific concerns.

The Kick-Off Meeting/Post-Award Conference will take place within 10 calendar days from award. The contractor shall provide any finalized contractor Teaming Arrangements (CTAs)/Subcontractor arrangements at this time.

### 2.2 Daily Operations

Contractor’s Project Manager shall be responsible for daily operations as well as coordinating and communicating with the 18F Product Lead. Daily operations may include:

-   Daily standup via video

-   Chat operations via web-based chat software such as Slack

-   Manage and update user stories + workflow tasks in shared project management system

### 2.3 GSA AAS Business Systems (AASBS) Web Portal

The GSA AASBS (Assisted Acquisition Services Business Systems also known as IT Solutions Shop (ITSS)) web portal will be accessible to the contractor during the performance of the call order and be used in the administration of the call order. This web-based system at <https://portal.fas.gsa.gov/web/guest> shall be used by the contractor to upload status reports, deliverables, invoices, and to respond to inquiries. The contractor shall maintain a current account on this system.

## 3.0 Transition**

----------------------

### 3.1 Transition Plan

The contractor shall:

-   Ensure and agree that all deliverables, products, licenses, designs, data, documentation, tests, user research notes, source code, configuration settings and files, and materials developed throughout this call order will be the property of the U.S. Government and in the public domain.

-   Two weeks prior to call order conclusion, provide a brief Transition Plan for all deliverables, products, and materials in coordination with the 18F Product Owner and COR.

-   Coordinate with the 18F Product Owner and COR, and potentially another vendor, and implement the Transition Plan.

-   Provide any other reasonable assistance to the Government to stand-up the application.

### 3.2 Transition Activities**

During the transition to the Government, or a new contractor, the contractor shall perform all necessary transition activities. Expected transition activities may include, but not be limited to, continuation of full services to 18F and other customers; participation in meetings with the Government or new contractor to effect a smooth transition and provide detailed information on the operation of all deliverables, at COR/ACOR and the 18F Product Lead's discretion; training of new personnel, either Government or new contractor, during transition period; and appropriate close-out of any outstanding technical and related performance elements for this task.

Final report shall include a list of sprint tasks completed, documentation, and link to code repository developed for 18F. Should the contractor be terminated prior to the end of the period of performance, the contractor shall transfer all project materials to the COR/ACOR and the 18F Product Lead within two weeks of the COR/ACOR and the 18F Product Lead’s request.

## 4.0 TERMS AND CONDITIONS
---------------------------------

----------------------

### 4.1 Type of Contract

This is a time-and-materials (T&M) order under master Agile BPA (aBPA) terms and conditions.

### 4.2 Period of Performance (POP)

The Period of Performance (POP) for this task is \[date of award\] to \[end of task\]. Further, a contingency of up to 6 months may be exercised. The POP is expected to begin within 10 calendar days after award.

### 4.3 Place and Hours of Performance

The primary place of performance will be at the contractor’s facility. 18F is a distributed team and some 18F staff involved in this contract may not be located in Washington, DC. Staff may also be distributed or work at their homes, per agreement with the Product Owner.

Business core hours shall be 0900 to 1800 EST, Monday – Friday on Government scheduled work days. The contractor may set its own work hours except that the contractor shall be available for technical contact by the Government between the hours of 0900 and 1800 local time on Government work days.

### 4.4 Administration Points of Contact

The following Points of Contact (POC) are applicable to this order:
Contracting Officer (CO): Aleseia Saunders, Contracting Officer, Federal Acquisition Service, GSA, aleseia.saunders@gsa.gov

CO’s Representative (COR): Rebecca Refoy-Sidibe, GSA, Technology Transformation Services, rebecca.refoy-sidibe@gsa.gov

### 4.5 Government Furnished Items

The Government will furnish the data and scripts needed at time of award. No other hardware or software will be provided by the Government.

### 4.6 Non-Personal Services

This call order is not being used to procure personal services prohibited by FAR 37.104, Personal services contract.

### 4.7 Privacy Act

Performance of this call order may require that personnel have access to Privacy Information. contractor personnel shall adhere to the Privacy Act, Title 5 of the U.S. Code, Section 552a and any other applicable applicable rules and regulations.

### 4.8 Transparency Policy

Vendors are advised that 18F will publish on a publicly available website documents associated with this requirement, including any Requests for Quotation (including amendments), Question and Answer exchanges with vendors (source-identifying information removed), and other relevant information that is not confidential/proprietary in nature or source selection sensitive information that would otherwise implicate procurement integrity concerns.

Upon award, 18F will publish the total price of the selected proposal and certain non-source-identifying data (e.g., the number of bids, the mean price, median, and standard deviation of price). During the performance of this call order, 18F will similarly publish source code, data related to project management (e.g., user stories, milestones, and performance metrics), and top-line spending data.

### 4.9 Data Rights and Ownership of Deliverables

18F intends that any data or deliverable created as a result of the work performed under the call order be committed to the public domain.

Further, 18F intends to commit the following items, to the public domain, at a minimum:

-   All data, documents, graphics and code created under this call order including but not limited to, plans, reports, schedules, schemas, metadata, architecture designs, and the like;

-   Any and all new open source software created by the contractor and forks or branches of current open source software where the contractor has made a modification; and,

-   Any and all new tooling, scripting configuration management, infrastructure as code, or any other final changes or edits to successfully deploy or operate the software.

The contractor shall use open source technologies wherever possible, in support of the 18F Source Code Policy. All licenses must be expressly listed in the deliverable. Regardless of license(s) used (e.g., MIT, GPL, Creative Commons 0) the license(s) shall be clearly listed in the documentation.

If the contractor needs to use work that does not have an open source license, the contractor is required to request permission from 18F, in writing, before utilizing that work in any way in connection with the order. If approved, all licenses shall be clearly set forth in a conspicuous place when work is delivered to 18F.

If an open source license provides implementation guidance, the contractor shall ensure compliance with that guidance. If implementation guidance is not available, the contractor shall attach or include the license within the work itself. Examples of this include code comments at the beginning of a file or contained in a license file within a software repository.

### 4.10 Section 508 Compliance Requirement

The contractor shall support the Government in its conformance with Section 508 throughout the development and implementation of the work to be performed.

Section 508 of the Rehabilitation Act of 1973, as amended (29 U.S.C. 794d) requires that when Federal agencies develop, procure, maintain, or use electronic information technology, Federal employees with disabilities have access to and use of information and data that is comparable to the access and use by Federal employees who do not have disabilities, unless an undue burden would be imposed on the agency. Section 508 also requires that individuals with disabilities, who are members of the public seeking information or services from a Federal agency, have access to and use of information and data that is comparable to that provided to the public who are not individuals with disabilities, unless an undue burden would be imposed on the agency.

The contractor agrees to promptly respond to, resolve and remediate any complaint regarding accessibility of its products or services in a timely manner and provide an updated version to the Government at no cost. The Government reserves the right to request, from the contractor, a timeline by which accessibility standards will be incorporated into the Programs and the contractor shall provide such a timeline within a commercially reasonable duration of time. The contractor further agrees to indemnify and hold harmless the Government from any claims arising out of its failure to comply with the requirements of this section. Failure to comply with these requirements shall constitute a material breach of this Agreement and shall be grounds for termination of this Agreement by the Government as set forth in Section 4.10.

These warranties will not apply if the Programs are: (i) modified or altered in any way (other than by the contractor or with the specific prior written consent of the contractor); (ii) not updated with the corrections, patches, fixes, updates, improvements or enhancements that the contractor may make available from time to time; (iii) used in any manner or for any purpose not specifically permitted by this Agreement or the documentation.

18F Acquisitions has adopted WCAG 2.0 level AA for web based content and is applicable for compliance according to Section 508 Standards 1194.5. The contractor should review the following websites for additional 508 information:

-   https://www.section508.gov/summary-section508-standards

-   http://www.access-board.gov/508.htm

-   http://www.w3.org/WAI/Resources

### 4.11 Non-Disclosure Agreement

All contractor key personnel, employees, agents, subcontractors and subcontractor personnel who will have access to documents or data during the performance of their duties under the contract shall execute the attached Non-Disclosure Agreement and return it to the CO within 5 calendar days of award and before being given access to such information or documents.

## 5.0 INVOICING/PROCEDURES FOR PAYMENT
---------------------------------------------

----------------------

The period of performance for each invoice shall be for one calendar month. The contractor shall submit only one invoice per month per order/contract.

*The Government reserves the right to audit, thus; the contractor shall keep on file all backup support documentation for travels as applicable.*

### 5.1 Content of Invoice

The contractor’s invoice will be submitted monthly for work performed the prior month. The contractor may invoice only for the hours, travel and unique services used in direct support of the call order. The invoice shall be submitted on official letterhead and shall include the following information at a minimum.

-   Client Order ID Number

-   ACT Number

-   Prompt Payment Discount

-   Remittance Address

-   Period of Performance for Billing Period

-   Point of Contact and Phone Number

-   Invoice Amount

-   Skill Level Name and Associated Skill Level Number (for T&M or Labor Hour)

-   Actual Hours Worked During the Billing Period (for T&M or Labor Hour)

-   Clearly indicate both the current invoice’s monthly “burn rate” and the total average monthly “burn rate” (for T&M or Labor Hour)

-   Travel Itemized by Individual and Trip (if applicable)

-   Supporting documentation for travel including travel approval and receipts (if applicable)

### 5.2 Invoice Submission

All invoicing shall be done electronically. Password and electronic invoice access may be obtained through the AASBS web portal.

The Invoice and the Status Reports for the applicable billing period shall be entered into the AASBS portal within 5 to 10 calendar days after the end of the month. The contractor shall submit invoices electronically by logging into the AASBS portal ([https://portal.fas.gsa.gov](https://portal.fas.gsa.gov/)), navigating to the appropriate order, and creating the invoice for that order and attach a copy of invoice, status reports with all required back-up documentation as applicable.

The contractor shall NOT submit any invoices directly to the GSA Finance Center (neither by mail nor via electronic submission). If the invoices are acceptable, then the Procurement Project Manager and COR/ACOR will approve them for payment and complete the information in the AASBS portal.

### 5.3 Final Invoice

Invoices for final payment must be so identified and submitted within 60 calendar days from task completion and no further charges are to be billed. A copy of the written acceptance of task completion must be attached to final invoices. The contractor shall request for an extension from the COR/ACOR for final invoices that may exceed the 60-day time frame.

The Government reserves the right to require certification by a COR/ACOR before payment is processed, if necessary.

### 5.4 Close-out Procedures**

The contractor shall submit a final invoice within 60 calendar days after the end of the performance period. After the final invoice has been paid the contractor shall furnish a completed and signed Release of Claims (GSA Form 1142) to the CO. This release of claims is due within 15 calendar days of final payment.
