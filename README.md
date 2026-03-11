Software Requirements Specification (SRS)

Automated Recruitment Management System – Resume Scanner

1. Introduction

1.1 Purpose

The purpose of this project is to develop an Automated Recruitment Management System that scans resumes, extracts relevant candidate information, matches it with job descriptions, and ranks candidates based on a compatibility score.

1.2 Scope

The system allows HR or Admin users to upload resumes and job descriptions. It automatically parses resumes, extracts structured data, performs skill matching, and displays ranked candidates on a dashboard.

1.3 Definitions

• Resume Parsing – Extracting structured data from resumes.
• JD – Job Description.
• Matching Score – Percentage indicating resume relevance.

2. Problem Description

In today’s recruitment process, organizations receive hundreds or even thousands of resumes for a single job opening. Manually screening resumes is time-consuming, error-prone, and inefficient. HR professionals must read each resume individually, compare it with job requirements, and shortlist candidates based on skills and experience.
Manual screening leads to:
●	High time consumption

●	Human bias in candidate selection

●	Risk of overlooking qualified candidates

●	Inconsistent evaluation standards

●	Increased workload for HR departments

Therefore, there is a need for an automated system that can efficiently scan resumes, extract relevant information, match them with job descriptions, and rank candidates objectively based on compatibility scores.The proposed system aims to automate and optimize the recruitment screening process using resume parsing and skill-matching algorithms.

3. Functional Requirements

3.1 User Authentication
FR1: The system shall allow user registration.
FR2: The system shall allow login and logout functionality.
3.2 Resume Upload
FR3: The system shall allow PDF/DOC upload.
FR4: The system shall validate file format.
FR5: The system shall store resume in database.
3.3 Resume Parsing
FR6: The system shall extract candidate name.
FR7: The system shall extract skills.
FR8: The system shall extract education.
FR9: The system shall extract experience.
3.4 Job Description Matching
FR10: The system shall allow JD upload.
FR11: The system shall compare resume and JD skills.
FR12: The system shall calculate compatibility score.
FR13: The system shall rank candidates.
3.5 Dashboard
FR14: The system shall display candidate list.
FR15: The system shall allow filtering based on skills.
FR16: The system shall allow download of shortlisted resumes.

4. Non-Functional Requirements

• Performance: Resume processing time should be less than 5 seconds.
• Security: Password encryption and secure file validation.
• Usability: Simple and user-friendly interface.
• Reliability: Proper error handling and system stability.
• Scalability: Ability to handle increasing resume volume.

5. System Requirements

Hardware Requirements: Minimum 4GB RAM, i3 processor or above.
Software Requirements: HTML, CSS, JavaScript, Java/Python backend, MySQL database.

6. Advantages 

●	Saves Time: Automates resume screening, reducing manual effort for HR.
●	Improves Efficiency: Quickly filters and ranks candidates based on job requirements.
●	Organized Data Storage: Stores candidate details systematically for future reference.
●	Handles Large Volume: Can process many resumes in less time.
●	Better Decision Making: Ranking system helps HR shortlist top candidates easily.
●	Reduces Human Bias: Provides objective skill-based evaluation.

7.Disadvantages

●	Parsing Errors: May fail to extract data correctly from poorly formatted resumes.
●	Dependence on Keywords: Good candidates may be missed if keywords are not matched.
●	Initial Development Complexity: Requires proper backend, database, and logic setup.
●	Data Privacy Concerns: Needs secure handling of candidate information.
●	Limited Understanding: Cannot fully evaluate soft skills or personality traits.
