<!-- llm-ignore:start -->
<p align="right">
  <img src="img/MU_wordmark_2021_red_RGB.png" alt="Murdoch University Logo" width="400"/>
</p>

## Unit Outline              
# ICT291
# Network Design and Implementation

**Teaching Period:** Semester 1, 2026

**Unit Coordinators:**<br>
Dr Joseph Stevens<br>
Mr Terry Koziniec

<p align="right">
  <img src="img/50thLogo_Print_Primary_Seal_Gold.jpg" alt="Murdoch University 50th Gold Seal Logo" width="80"/>
</p>
<!-- llm-ignore:end -->

---

## 1 Unit Details
Welcome to:<br>
Unit Code: ICT291<br>
Unit Name: Network Design and Implementation

### 1.1 Unit Description 
This unit aims to extend a student's introductory data-communications knowledge to include technologies associated with enterprise networks such as redundancy, dynamic routing and access-control-list based security. There is a particular focus on LAN design and Ethernet switching concepts. These are explored at an advanced level.

A consistent theme throughout the unit is "scalability". From design methodology to specific technologies, the unit leverages a student's ability to design a small functional network to enable the development of an enterprise network that is manageable, reliable and secure.

**Prerequisites**

ICT169 Foundations of Data Communication.

If you have an exemption from ICT169 based on prior studies (EG TAFE) it is essential that you:  

•	Are familiar with the OSI model for data communications.  
•	Are familiar with the operation of the Internet Protocol (IP) and Ethernet technologies.  
•	Understand the role of IP addresses, subnet masks and default gateways.  
•	Can perform basic IP version 4 subnetting.  

The greatest challenge for students taking ICT291 without adequate prerequisites will be to catch up on the IP subnetting. If you feel that your prior studies did not adequately cover the requirements, it is strongly recommended that you discuss the matter with the unit coordinator or your Academic Chair. Ideally, you will take the unit ICT169 Introduction to Data Communications before enrolling in ICT291.  

It is also preferable that you have used the Cisco IOS to configure network devices before taking ICT291.  If you haven't, please let the Unit Coordinator know in the first week.  The Unit Coordinator will point you towards some introductory materials and exercises to bring you up to speed.

**Aims of the unit**  
For students enrolled in the Internetworking and Network Security major, ICT291 serves as an intermediate data-communications unit. The goal is to give students sufficient background knowledge and applied skills so that they are prepared to take the advanced third-year units: “Advanced Network Design”, “Network Security”, and “Wireless and Interactive Networks”.  

After completing this unit, students should understand the components and technologies that make up a large-scale network. Students will develop a more advanced understanding of specific routing and switching technologies: Wireless-LANs and network security in later units.  

Introductory networking units tend to focus on generic theory and the configuration of hosts. However, as an intermediate unit, ICT291 is more focused on network infrastructure (routers and switches) and the development of applied skills. The unit emphasises emphasis is Cisco IOS as this will be required in later units. Cisco IOS-like environments are also the most likely to be encountered when working with enterprise or carrier-class routing and switching.  

ICT291 extends ICT169's coverage of the LAN to include more advanced topics and techniques. Upon completing this unit, students can design and implement LANs optimised in terms of performance and reliability rather than merely providing connectivity.  

**Cisco Certified Network Associate (CCNA) Exam preparation**  
This section contains information relating to the externally administered CCNA exam.  None of this information relates to the requirements of this unit but it does explain which parts of the Cisco Curriculum are considered less important by the unit coordinator, as the requirements and emphasis of a University course on data communications and a vendor based certification exam are not always in perfect alignment.  

This unit makes use of two modules of the Cisco Systems Network Academy curriculum which in itself aims to provide a broad coverage of IP based data communications, prepare students to sit the CCNA exam and provide background information on the networking industry and work life and roles within the industry.  This unit emphasises and assesses the IP networking theory and application and tends to ignore the extraneous topics.  

For students wishing to sit the CCNA exam after taking this unit, and I do encourage you to do so, here are some points to take into account in your preparation.  

The unit coordinator will place little emphasis on the Cisco proprietary elements of the curriculum.  Fortunately the communications industry is based on standards and the vast majority of the Cisco content applies to the industry as whole and to other vendor's equipment. Content that relates to the following areas is likely to be covered in little depth and you should revisit these sections prior to sitting for your CCNA exam:  

    • Cisco product hardware and features.  
    • Marketing concepts and terminology. Often this includes methodologies and models that emphasise integration and a single vendor environment.  
    • Navigation of the GUI configuration environments.  
    
For the most part these are items that candidates memorise prior to a certification exam rather than something that is learned.  There are a number of Cisco authored labs available that emphasise the use of the GUI interface.  These are not used in this unit but for those planning to take the CCNA exam, you are encouraged to complete at least some of these as part of your Certification examination preparation.  

https://www.cisco.com/site/us/en/learn/training-certifications/exams/ccna.html 


### 1.2 Learning Outcomes
This unit enables you to demonstrate your achievement of the following unit learning outcomes.

| Major Learning Outcomes (Internetworking and Network Security)                                                    | Course LO |
|:-------------------------------------------------------------------------------:|
| 1. Demonstrate a broad and coherent knowledge and understanding of the underlying principles and core concepts of Internetworking and Network Security, including:<br>a) Appreciation of the interplay between theory and practice<br>b) Awareness of the broad applicability of computing<br>c) Appreciation of domain-specific knowledge, including:<br>* data communications theory and practice<br>* Network design and troubleshooting<br>* Network security<br>* Wireless network technologies             |
| 2. Demonstrate mastery of the core networking technologies and topologies to create secure and efficient solutions for organisational data communications.  |
| 3. Develop proficiency in the design and administration of a number of data communications networks and environments. |
| 4. Demonstrated capacity to specify, design, implement, secure and manage complex organisational data communications networks. |


| Unit LO (Learning Outcomes)                                                    | Course LO |
|:-------------------------------------------------------------------------------|:---------:|
| 1. Create a network design that is functional, stable and scalable.           | 1    |
| 2. Apply established industry design methodologies and best practices to design and implement a highly available network that delivers the needs of the stakeholders.  | 1    |
| 3. Manage network traffic according to organisational policy using ACLs (Access Control Lists) and demonstrate an understanding of sound security practices. | 1    |
| 4. Detect, troubleshoot and correct common enterprise network implementation issues using common tools and established troubleshooting methodologies. | 1    |
| 5. Design, configure and manage simulated enterprise networks using using EVE network emulation software.| 2    |

### 1.3 Graduate attributes 
This unit will contribute to the development of the following [Graduate Attributes](https://www.murdoch.edu.au/mymurdoch/support-advice/learning-study/graduate-attributes):
- Critical and creative thinking
- In-depth knowledge of a field of study

The Skills Framework for the Information Age (SFIA) Framework enables using a common language to describe the various skills in the information technology realm and the levels at which those skills are exercised. For more details regarding the framework, see http://www.sfia-online.org.
In terms of levels, SFIA identifies seven levels of responsibility. SFIA specifies Level 5, “Ensure, advise” and Level 6 “, Initiate, Influence”, for network professionals. For level 6, SFIA defines the expected complexity and knowledge as follows:

This unit addresses the following SFIA Skills:
Development and Implementation – Systems Development – Network Design (Level 6)
Delivery and operation – Technology Management – Network Support (Level 5)
In terms of levels, SFIA identifies seven levels of responsibility. SFIA specifies Level 5 “Ensure, advise” and Level 6 “Initiate, Influence” for network professionals. For level 6, SFIA defines the expected complexity and knowledge as follows:

### 1.4 Skills Framework for the Information Age (SFIA) 
The Skills Framework for the Information Age (SFIA) Framework enables using a common language to describe the various skills in the information technology realm and the levels at which those skills are exercised. For more details regarding the framework, see http://www.sfia-online.org.
In terms of levels, SFIA identifies seven levels of responsibility. SFIA specifies Level 5, “Ensure, advise” and Level 6 “, Initiate, Influence”, for network professionals. For level 6, SFIA defines the expected complexity and knowledge as follows:

This unit contributes to the following SFIA Skills:
- Development and Implementation > Systems Development > **Network Design** (Level 6)
- Delivery and operation > Technology Management > **Network Support** (Level 5)

SFIA specifies Level 5 “Ensure, advise” and Level 6 “Initiate, Influence” for network professionals. 
For level 6, SFIA defines the expected complexity and knowledge as follows:

**SFIA level 6 - Complexity**
Performs an extensive range and variety of complex technical and/or professional work activities. ***Undertakes work that requires the application of fundamental principles in a wide and often unpredictable range of contexts***. Understands the relationship between own specialism and wider customer/organisational requirements.

**SFIA level 6 - Knowledge**
Is fully familiar with recognised industry bodies of knowledge both generic and specific. Actively seeks out new knowledge for own personal development and the mentoring or coaching of others. Develops a wider breadth of knowledge across the industry or business. Applies knowledge to help to define the standards which others will apply.

I want to draw your attention to the ***highlighted text***. Although we will cover the theory and provide examples, we will not cover every possible scenario. You will need to use your understanding of various technologies and protocols to create solutions to problems that occur in environments (contexts) that you are not familiar with. Rote learning facts is ineffective in developing understanding, and you should not expect that the assessment items will contain many questions you have already seen. The unit itself can not deliver SFIA level 6, this is demontrated through a role performing at that level. But the unit supports the development of knowledge and complexity at that level.

This unit will assist in preparing students for a number of common ICT roles, including:
- Computer Network Systems Engineer
- ICT Security Specialist
- Network Administrator
- ICT Support Engineer
- ICT Consultant
    
### 1.5 Strategic themes
As an institution, the strategic themes of sustainability, equity, diversity & inclusion, and first nations guide and shape much of our activity.

**Sustainability:** The unit promotes structured, scalable, and maintainable network design practices. These approaches contribute to more sustainable information and communication technology infrastructure and help reduce long-term environmental impact.

**Equity, Diversity and Inclusion:** Although not the primary focus of the unit, networking and communication technologies are essential enablers of access to education, public services, and participation in the digital economy. By developing the technical skills required to build and manage network infrastructure, students contribute to the foundations of more inclusive and equitable digital systems.

**First Nations:** The ability to design and implement reliable and scalable network infrastructure is critical to improving digital connectivity in regional and remote areas. The technical competencies developed in this unit directly support the kind of information and communication technology capability needed to improve access to online services, education, and communication for First Nations communities.

### 1.6 General guidance and requirements
#### 1.6.1 Inclusivity Statement
Murdoch University strives to be a place of belonging for all staff and students. We are committed to supporting and celebrating all community members including all abilities, ethnicities or religions, sexual or gender identities. Homophobia, transphobia, racism, and ablism are not tolerated. 
For help and support, please see information and contacts in [Health & wellbeing](https://www.murdoch.edu.au/mymurdoch/support-advice/health-wellbeing) in myMurdoch.
#### 1.6.2 In case of unforeseen disruption to learning and teaching
A university or campus wide disruption may occur due to natural, political, or other human crisis (e.g., COVID-19). Where it impacts our learning, teaching, and assessment plans, then we will communicate changes relevant to this unit via myMurdoch Learning. Also pay attention to student announcements and myMurdoch for university wide information. 
For individual needs, consult with [Access and Inclusion](https://goto.murdoch.edu.au/accessibility-services) to see if an individual Access and Inclusion (MyAccess) plan is appropriate, or for specific assessment item adjustments, see your Unit Coordinator. 
#### 1.6.3 Where to get help for your learning success and wellbeing
Please refer to [Support & Advice](https://www.murdoch.edu.au/mymurdoch/support-advice) via [myMurdoch](https://www.murdoch.edu.au/mymurdoch) for all the information you need for your studies.
This includes:
- [Student admin](https://goto.murdoch.edu.au/StudentAdmin), [Exams](https://goto.murdoch.edu.au/Examinations), [Policies](https://goto.murdoch.edu.au/Policies), [Key dates](https://goto.murdoch.edu.au/DatesDeadlines), [Complaints and appeals](https://goto.murdoch.edu.au/ComplaintsAppeals)
- [Learning and study](https://goto.murdoch.edu.au/learningstudy) support, including information about Academic Integrity and Murdoch Academic Passport
- [Health and wellbeing](https://www.murdoch.edu.au/mymurdoch/support-advice/health-wellbeing) information, including Accessibility services, Medical and counselling services, Aboriginal and Torres Strait Islander support, and Sexuality and gender diversity support
    - Contact [Access and Inclusion](https://goto.murdoch.edu.au/accessibility-services) if you have a disability, Specific Learning Disorder or health condition (including mental health condition), are pregnant or breastfeeding or are caring for a person with a disability, and require support in accessing your studies.
    - [Kulbardi Aboriginal](https://goto.murdoch.edu.au/Kulbardi) Centre provides support for Aboriginal and Torres Strait Islander students.
#### 1.6.4 Key dates and considerations for withdrawing from this unit
If you are considering [withdrawing](https://goto.murdoch.edu.au/Withdrawing) from this unit, see the Withdrawing page for general information and implications. 
See the [Teaching Periods](https://goto.murdoch.edu.au/TeachingPeriodsCensusDates) page for implications of withdrawing at different times of the teaching period, including [Census Date](https://myanswers.custhelp.com/app/answers/detail/a_id/848/~/census-date), and search for the specific dates for your current teaching period. 
#### 1.6.5 Where to find your class
To find any location at Murdoch, use [Murdoch Maps](https://maps.murdoch.edu.au/). 

---

## 2 Contact details
### 2.1 Unit coordinators

Role:
Unit Coordinator
Discipline:
Information Technology
Campus:
South Street, 
Email:
joseph.stevens@murdoch.edu.au
Phone:
618 9360 2798
| <img src="img/uc2-photo.jpg" alt="Joe Stevens photo" width="100" style="border: 1px solid #ccc; padding: 4px;"/> |   |
|---------------|-----------------------------------------| 
| **Name:**     | Joe Stevens                          |
| **Preferred:**| Joe                                   |
| **Pronouns:** | He/Him                                  |
| **School:**   | School of Information Technology        |
| **Campus:**   | South Street, Murdoch, Australia        |
| **Office:**   | Building 245, Room 1.014                |
| **Email:**    | joseph.stevens@murdoch.edu.au               |

| <img src="img/uc1-photo.png" alt="Terry Koziniec photo" width="100" style="border: 1px solid #ccc; padding: 4px;"/> |   |
|---------------|-----------------------------------------| 
| **Name:**     | Terry Koziniec                          |
| **Preferred:**| Terry                                   |
| **Pronouns:** | He/Him                                  |
| **School:**   | School of Information Technology        |
| **Campus:**   | South Street, Murdoch, Australia        |
| **Office:**   | Building 245, Room 1.022                |
| **Email:**    | t.koziniec@murdoch.edu.au               |

### 2.2 Teaching team

|                     |                                          |
|---------------------|------------------------------------------|
| **Name:**           | James McCutcheon                         |
| **Preferred:**      | James                                    |
| **School:**         | School of Information Technology         |
| **Campus:**         | South Street, Murdoch, Australia         |
| **Email:**          | James.McCutcheon@murdoch.edu.au          |
| **Lab Session:**    | Thursday 8:30AM, Building 360 Room 3.010 |

|                     |                                          |
|---------------------|------------------------------------------|
| **Name:**           | Wai Leong Ow                             |
| **Preferred:**      | Wai                                      |
| **Pronouns:**       | He/Him                                   |
| **School:**         | School of Information Technology         |
| **Campus:**         | South Street, Murdoch, Australia         |
| **Email:**          | WaiLeong.Ow@murdoch.edu.au               |
| **Lab Session:**    | Thursday 8:30AM, Building 360 Room 3.010 |

|                     |                                          |
|---------------------|------------------------------------------|
| **Name:**           | Terry Koziniec                           |
| **Preferred:**      | Terry                                    |
| **Pronouns:**       | He/Him                                   |
| **School:**         | School of Information Technology         |
| **Campus:**         | South Street, Murdoch, Australia         |
| **Email:**          | t.koziniec@murdoch.edu.au                |
| **Lecture Session:**| Tuesday 10:30AM, Building 460 Room ECL1  |
| **Lab Sessions:**   | Friday 8:30AM, Building 360 Room 3.010<br>Friday 10:30AM, Building 360 Room 3.010 |

|                     |                                          |
|---------------------|------------------------------------------|
| **Name:**           | Awais.Amin@murdoch.edu.au                |
| **Preferred:**      | Awais                                    |
| **School:**         | School of Information Technology         |
| **Campus:**         | South Street, Murdoch, Australia         |
| **Email:**          | Awais.Amin@murdoch.edu.au                |
| **Lab Session:**    | Friday 10:30AM, Building 360 Room 3.010  |

---

## 3 How to study this unit
### 3.1 Approach to learning
#### 3.1.1 Learning approach underpinning unit
Content delivery in ICT291 is via a 2-hour lecture and readings associated with the Cisco online curriculum. Weekly 2-hour labs focus on applying the theory and using EVE-NG network emulation software. The unit uses a scaffolded learning approach with labs focussing on isolated exploration of the weekly topics and a real-world case study that integrates the topics into an overall design that builds during the semester.

#### 3.1.2 Unit changes in response to student feedback
Previous students have provided us with feedback to improve this unit. Please help us continue this feedback cycle by completing your own unit survey which will open toward the end of teaching. You can find your Myfeedback surveys at http://myfeedback.murdoch.edu.au/. 

### 3.2 Learning activities & requirements
#### 3.2.1 Overall expectations
ICT291 has a prerequisite of ICT169 and assumes the learning objectives of that unit have been achieved. If your performance in ICT169 was marginal, then you will find ICT291 a challenging unit. You must work on the areas you struggled with in ICT169 and build on a solid foundation. The rigorous assessments aim to test your understanding rather than merely your memory.

#### 3.2.2 Learning activities and details
**Lecture:** 2 hours each teaching week, these will be recorded and availble via Echo 360.

**Lab:** 2 hours each teaching week. You may not complete all labs in the allotted time.  The expectation is that you will complete the lab in your own time if necessary.

**Case Study:** This is an active learning exercise designed to build your skills through practical engagement. It is not intended to be difficult or obscure. In many cases, the detailed instructions include testing or verification steps to guide your progress.

If you encounter difficulties, revisit the relevant lab activities to reinforce your understanding of the techniques or technologies involved. Then return to the case study with improved knowledge and confidence. You are expected to complete all parts of the activity and persist through challenges — troubleshooting is a core learning objective in ICT291 and a valuable professional skill.

The case study is structured around five cumulative milestones, with each stage building on the successful completion of previous exer                cises. It is essential to complete the tasks in order and correct any errors before progressing.

This task is not formally assessed, but it is **crucial for your learning and practical exam preparation**. 

---

## 4 Unit Schedule
See [myMurdoch Learning](https://goto.murdoch.edu.au/LMS) for details of all learning activities and assessments. Go to [TeachingTimetables](http://goto.murdoch.edu.au/TeachingTimetables) or [myCalendar](https://goto.murdoch.edu.au/PersonalCalendar) to see your scheduled class times.

Timetable specifics subject to change. You will be notified of changes by the Teaching Team.

| Week | Date commencing | Readings    | Topic                                      | Assessment due date       |
|:----:|:------------:|-------------|--------------------------------------------|---------------------------|
| 1    | 23-Feb-2026  | SRWE 2 & 14 | Introduction & Layer 2/3 revision          |                           |
| 2    | 02-Mar-2026  | ENSA 11     | Scalable Network Design                    | Case study 1, IOS Basics/EVE<br>(Formative - self assessment)|
| 3    | 09-Mar-2026  | SRWE 5       | LAN Redundancy and STP  802.1d  |                           |
| 4    | 16-Mar-2026  | ENSA 13.4-5  | Rapid STP and alternatives to STP and Spine-Leaf model  |
| 5    | 23-Mar-2026  | SRWE 3 (revision) 6 & 4 | Link Aggregation, InterVLAN routing,Routing principles and protocols|Case study 2 STP |
| 6    | 30-Mar-2026  | SRWE 14 (revision) ENSA  1 & 2| Introduction to OSPF |Case study 3 VLAN routing| 
| 7    | 06-Apr-2026  |               | **[  Independent Study Week  ]**  |Friday, 5th September 2026, 2:30PM|
| 8    | 13-Apr-2026  |               | OSPF multi-area and Summarisation |                           |
| 9    | 20-Apr-2026  | ENSA 4 & 5    |Access Control Lists (ACL)         | Case study 4 OSPF/end-to-end |
| 10   | 27-Apr-2026  |               | **[  Independent Study Week  ]**  |                           |
| 11   | 04-May-2026  | ENSA 6        |ACL continued Implementing NAT          |                           |
| 12   | 11-May-2026  | SRWE 9        | First hop redundancy HSRP / VRRP |Case study submission 5 ACL / Internet|
| 13   | 18-May-2026  |              | No Classes this week Study for your practical                              |** TBA PRAC **|
| 14   | 25-May-2026  |            | Review                              |                           |

---

## 5 Assessments
Assessment for this unit is conducted in accordance with the [Assessment Procedure](https://goto.murdoch.edu.au/AssessmentProcedure) and [Student Assessment Support Procedure](https://goto.murdoch.edu.au/StudentAssessmentSupport).

### 5.1 Assessment summary

| # | Assessment Name | Unit Learning Outcomes | Weight % |Individual or Group | Due Date and Time    |
|:-:|-----------------|:----------------------:|:--------:|--------------------|:--------------------:|
| 1 |Midsemester Exam | 1,2,3,4                | 30       |Individual          |Friday, 5th September 2026, 2:30PM    |
| 2 |Practical Exam   | 1,3,4,5                | 30       |Individual          |**TBA**                   |
| 3 |Final Exam       | 1,2,3,4                | 40       |Individual          |University Exam Period|


### 5.2 Assessment information
#### 5.2.1 Assessment 1 - Midsemster Exam
**ASSESSMENT DESCRIPTION**

- 90 minute duration.
- 30% of the unit grade.
- Held during the first Independent Study Week
    - Friday, 5th September 2026
    - 2:30 PM - 4:00 PM
- Closed book, invigilated exam.

The exam will be cover the topics covered in the first five weeks of the unit. This includes: general principles of scalable design; layer 2 concepts, including STP (Spanning Tree Protocol) and general principles of routing.

**HOW TO SUBMIT**

The exam will be held undersupervised conditions in a computer lab. The exam will be conducted using LMS and may feature multiple choice, short answer, calculation and longer answer questions. 

**HOW IT IS ASSESSED** (summary)

You will be assessed on these key criteria:
- Where possible questions are autograde using the LMS quiz tool.
- Where questions are entered as short typed text (for example an IP address), answers graded by LMS as incorrect are manually checked for typos.  Errors that are not related to the validity of the answer, such as white space or uneccessary text that doesn't undermine the answer, may be manually graded.
- Written paragraph answers are graded manually using a marking guide. If there are multiple graders, every effort will be made to have the same person grade all of the instances of a given question to ensure consistency of marking for all students.

**FEEDBACK FOR LEARNING**

- Your results will be visible with in LMS.
- Student's have the right to view their exam to see where they have gone wrong. Arrangements for providing this feedback will be communicated during the semester. Pleae approach the teaching staff if you have not had this opportunity.

**GUIDELINES for SUCCESS**

- Fully engage with the weekly labs and struggle through any problems until they are resolved.
- Complete the case studies aiming for 100% completion.  This means you are actively trying to resolve issues and understanding every week.

A common issue for students answering written question is failing to answer the question that is asked.  It does not matter whether you answer is a correct statement if it does not answer the question being asked.  Read the questions carefully.

**FURTHER DETAILS**

See myMurdoch Learning for further details, such as instructions, communication and a sample exam.

#### 5.2.2 Assessment 2 - Practical exam
**ASSESSMENT DESCRIPTION**

- (TBA) duration.
- 30% of the unit grade.
- Held (TBA)
- Closed book, invigilated exam.
    - No electronic aids
    - No use of computer tools such as “Windows Calculator”
    - No access to sites other than the LMS testing engine page is permitted.
    - No notes are permitted.

**HOW TO SUBMIT**

Students are given an EVE topology file which contains a preconfigured network. The configuration and topology will be similar to a the case-study that students have been working with over the semester, so the scenario will not be unfamiliar.
The assessment will require students to fix errors in the network configuration, make changes to the configuration to reflect business requirements and extract information from the network. 

**HOW IT IS ASSESSED** (summary)

You will be assessed on these key criteria:
- The LMS quiz tool is used to deliver questions relating to a provided EVE simulated topology. Students use EVE to interogate the network and find solutions to problems and implement required changes. The EVE simulation provides a realistic practical environment but the actual answers to exam questions are entered in the LMS quiz.

The assessment includes a moderation process to ensure reliable, just, and fair outcomes. 

Your assessment outcome will be provided to you via the LMS gradebok.

**FEEDBACK FOR LEARNING**

As this assessment is late in the semester and is the only practical assessment, there are limited benefits in merely "knowing the answer".  Also, the simulated network exam artifact and indeed the EVE simulator is likely to be withdrawn shortly after the assessment. The nature of the assessment is such that students have a good idea as to where they went wrong during the exam as the simulated network provides an opportunity to validate their solution.
- Students have the right to see their exam script but this will be allowed only under supervised conditions (you may not take a copy of the exam).  If a number of students wish to do this then the unit coordinator may organise viewing sessions.  Alternatively, a written summary of their result may be provided for individual students.

**GUIDELINES for SUCCESS**

The practical exam is heavily weighted to solving problems.  You will have plenty of practice at this if you:
- Fully engage with the weekly labs and struggle through any problems until they are resolved.
- Complete the case studies aiming for 100%.  This means you are actively trying to resolve every fault.
- Complete the mock practical exam.

**FURTHER DETAILS**

See myMurdoch Learning for further details, such as instructions, communication and a sample exam.

#### 5.2.3 Assessment 3 - Final exam
**ASSESSMENT DESCRIPTION**

- 90 minutes duration.
- 40% of the unit grade.
- Held during the University examinations period. 
- Free navigation, you can return to already answered questions
- Closed book, invigilated exam.
    - No electronic aids
    - No use of computer tools such as “Windows Calculator”
    - No access to sites other than the LMS testing engine page is permitted.
    - No notes are permitted.

This is a comprehensive exam covering the breadth of the topics covered in the unit.The examination may include multiple choice, short answer and written answer questions. Being LMS based, there are no relevant past exam papers held by the library. 

**HOW TO SUBMIT**

The exam will be held undersupervised conditions in a computer lab. The exam will be conducted using LMS quiz tool.


**HOW IT IS ASSESSED (summary)**

You will be assessed on these key criteria:

- Where possible questions are autograde using the LMS quiz tool.
- Where questions are entered as short typed text (for example an IP address), answers graded by LMS as incorrect are manually checked for typos.  Errors that are not related to the validity of the answer, such as white space or uneccessary text that doesn't undermine the answer, may be manually graded.
- Written paragraph answers are graded manually using a marking guide. If there are multiple graders, every effort will be made to have the same person grade all of the instances of a given question to ensure consistency of marking for all students.

**FEEDBACK FOR LEARNING**

- As this is the final assessment there is no feedback for learning, this is purely an assessment.
- Under university policy students have the right to inspect their graded assessment but this is not provided austomatically.  You must, request this, in writting, within two weeks of the final results being published.

**GUIDELINES for SUCCESS**

As this covers the breadth of the unit, you should engage in the learning activities on a contiuos basis.  This includes completing the readings, listening to the lecture, attending (and completing) labs and engaging with the case study.

A common issue for students answering written question is failing to answer the question that is asked.  It does not matter whether you answer is a correct statement if it does not answer the question being asked.  Read the questions carefully.

**FURTHER DETAILS**

See myMurdoch Learning for further details, such as instructions, communication and a sample exam.  Also see the University examination timetable to determin when and where the examinatio will be held.

### 5.3 Academic integrity
Murdoch University expects students and staff to pursue the highest standards of integrity in all academic activity. Academic integrity involves behaving ethically and honestly in scholarship and relies on respect for others’ ideas through proper acknowledgement and referencing of publications. 
Academic misconduct is treated seriously and penalties may apply. 
More information about academic integrity can be found at https://goto.murdoch.edu.au/AcademicIntegrity. To help you learn about academic integrity practices, all students are required to complete the [Murdoch Academic Passport (MAP100)](https://goto.murdoch.edu.au/murdochacademicpassport). Please also note the [library citation guide](http://goto.murdoch.edu.au/referencing).
#### 5.3.1 Use of GenerativeAI
Overall in this unit, you must follow the expectations around the use of Generative Artificial Intelligence (GenAI).
- All use of GenAI must be cited/referenced/acknowledged.
- If no specific expectations are provided, then you must assume GenAI use is not permitted for that assessment. Any suspected unauthorised use will be investigated for misconduct.
See the assessment details above for any specific expectations.
#### 5.3.2 Text matching software (Turnitin)
Murdoch University makes use of content matching software or other forms of comparison to identify unoriginal, incorrectly referenced, or uncited text. Where possible assessments will be submitted to Turnitin.com for the detection of plagiarism and the unauthorised use of artificial intelligence. All submitted assessments will be retained as source documents in the Turnitin.com reference database. You will be required to agree to the Turnitin [End-User License Agreement](https://guides.turnitin.com/hc/en-us/articles/29025093477901-Turnitin-End-User-License-Agreement) when submitting.
Your Unit Coordinator may apply other processes to verify that your submitted assessment is your own work.
#### 5.3.3 This unit
In this unit, we undertake these practices to assure academic integrity (including expectations for use of GenAI):
- All assessments are supervised
- SEB (Safe Exam Browser) is used where possible.
- Where suspicious behaviour is observered, LMS and lab computer logs are requested to ensure closed book conditions are not breached.
- All suspected breaches of exam conditions are repored for investigation as potential academic misconduct.

### 5.4 Extensions and late submissions
This unit follows Murdoch policies and procedures, particularly the [Student Assessment Support Procedure](https://goto.murdoch.edu.au/StudentAssessmentSupport) and [Assessment Procedure](https://goto.murdoch.edu.au/AssessmentProcedure), with regards to assessment submission and extensions, supplementary and deferred assessment, and other expectations.
In this unit, extensions and late submissions follow these requirements:
- Assessments submitted after the due date without approval will not be marked, and you will receive 0% for the assessment.
- You can apply for an assessment extension without penalty. See the [Student Assessment Support Procedure](https://goto.murdoch.edu.au/StudentAssessmentSupport) for all requirements.
Students who feel that their disability, health condition or disability caring responsibilities may impact on their capacity to meet assessment submission are strongly advised to visit [Access and Inclusion](https://goto.murdoch.edu.au/accessibility-services) as early as possible to discuss potential needs and assistance.
### 5.5 Determination of the final grade
Refer to the [Grades Policy](https://goto.murdoch.edu.au/GradesPolicy) for information about marks and grades.

---

## 6 Learning resources 
### 6.1 All learning resources
Your learning resources and any updates are provided through myMurdoch Learning (LMS).
Learning resources within the [myMurdoch Learning](https://goto.murdoch.edu.au/myMurdochLearning) online environment for this unit will be
1. integrated within the sections and learning activities 
and/or
2. through tools such as:
    - [My Unit Readings](http://goto.murdoch.edu.au/MyUnitReadings)
    - Teams
    - Echo360
    - PebblePad

The specific types of learning resources that we use include:

### 6.2 Essential learning resources
These are the learning resources that you should use:  

| Resource details          | Resource type                             | Available                  | 
|---------------------------|-------------------------------------------|----------------------------|
| Unit resources            | Various               | [My Unit Readings](http://goto.murdoch.edu.au/MyUnitReadings) |
| Cisco netacad             |                                           |                            |
| EVE-NG Simulator          |                                           |                            |
|                           |                                           |                            |

Other resources and further recommended resources are in our myMurdoch Learning.

---

## 7 Academic Advice and Student Support
**Need guidance on study related issues?**

**Use this flowchart or seek direct assistance from Student Support Services or MyMurdochAdvice.**

### Contact your *Tutor* if you have:
- Questions about content covered in tutorials or practical sessions. 
- General questions about completing assessments.
- Concerns about another student or your learning needs.
- Positive and constructive feedback.

### Contact your *Unit Coordinator* if you have:
- Questions about unit content, assessments, attendance or tutorial times. 
- Questions on marked assessments. 
- Request a re-mark/review of a marked assessment.
- Academic issues with your learning in this unit.
- Positive and constructive feedback.

### Contact your *Academic Chair* if you have:
- Academic and assessment issues that haven’t been adequately addressed by the Unit Coordinator. 
- Academic issues relating to progression through your degree, withdrawal from a unit or intermission.
- Positive and constructive feedback.

### Contact your *Head of School* if you have:
- Academic, assessment or other issues that haven’t been adequately addressed by your academic chair or you aren’t comfortable discussing with your Academic Chair.
- Formal request for re-mark/review in accordance with policy and procedure, where Unit Coordinator has not undertaken.
- Complaints or appeals relating to your studies that haven’t been adequately addressed. Visit Complaints and Appeals for more advice.
- Positive and constructive feedback.

***To further escalate an appeal or complaint, contact the Associate Dean Learning and Teaching and/or see Complaints and Appeals for formal appeals procedures.***

**STUDENT SUPPORT SERVICES:** https://goto.murdoch.edu.au/supportservices

**LEARNING AND STUDY SUPPORT:** https://goto.murdoch.edu.au/learningstudy 

**MYMURDOCH ADVICE:** https://goto.murdoch.edu.au/mymurdochadvice 

**COMPLAINTS AND APPEALS:** https://goto.murdoch.edu.au/ComplaintsAppeals 
