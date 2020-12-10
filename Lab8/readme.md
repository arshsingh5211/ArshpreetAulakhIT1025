## Executive Summary ##

In the last unit of the course, we are looking at various database models and working with SQL to practice queries. I did work with SQL briefly about two years ago, but I am not very familiar with it at this moment so I am excited to delve back into databases and how to best work with them. Finally, this unit will cover key ethical and legal implications of information systems and how advancement in technology and computing has led to many legal and ethical ramifications.

### Data, Information, and Knowledge ###

Data are the raw facts and may be devoid of context or intent, and it can be quantitative (numeric) or qualitative (descriptive). Information is processed data that possesses context, relevance, and purpose, and it typically involves manipulation of raw data to obtain an indication of magnitude, trends, in patterns in the data for a purpose. Finally, knowledge in a certain area is human beliefs or perceptions about relationships among facts or concepts relevant to that area.

The primary key in the customers and orders table would be a customerID and orderID unique identifiers. The tables are related by having a field in common with each other, such as the customerID being a foreign key in the order table. This is a one-to-many relationship as each customer can theoretically have more than one order but each order is held by only one customer.

We must properly define the data type of a field because it tells the database what functions can be performed with the data, and also so the proper amount of storage space is allocated for the data.

#### Big Data ####

The four V's of big data are volume, velocity, variety, and varacity. Volume represents the amount of data and refers to the mass quantity of data that organizations have been trying to harness to improve decision making across the enterprise. Velocity represents the motion of tha data as enterprises have invested a lot to develop Big Data solutions in almost real time in order to incorporate it into business processes and decision making. Variety defines different types of data and resources, as the world has moved beyond structured data and new categories have been added to data types. Finally, veracity is the trustworthiness of the data or the level of reliability associated with certain types of data. Technology involved with banking, logistics, retail, e-commerce, and social media have all adopted Big Data practices and driven the need for it.

### Structured Query Language ###

RDBMS stands for Relational Database Management System and it is the basis for SQL and for all modern database systems. The purpose of SQL is to access and manipulate databases, and RDBMS uses tables to show how they are related.

I looked at the Products and Categories table from the diagram above. Products table's foreign key is CategoryID and its primary key is ProductID, and the categories table's primary key is CategoryID. It is a many-to-one relationship as there can be many categories for each product.

#### SQL Injections ####

SQL injections are a code injection technique that could destroy a database, and it is one of the most common web hacking techniques. It is the placement of malicious code in SQL statements via web page input. They are a huge security threat because they usually ask a user for input such as a username/userID, but instead of giving those, the user gives an SQL statement that will run on your database **unknowingly**. Therefore, a hacker could get access to all the usernames and passwords in a database, by simply inserting 105 OR 1=1 into the input field. The best way to protect a website from SQL injection is to use SQL parameters, which are values that are added to a query at execution time in a controlled manner. The SQL engine will then check each parameter to ensure that it is correct for its column and are treated literally and not as part of the SQL to be executed.

### Ethical and Legal Ramifications ###

#### Code of Ethics ####

The purpose of a code of ethics is to outline a set of acceptable behaviors for a professional or social group that is generally agreed to by all members of the group. This document details different actions that are considered appropriate and inappropriate. The ACM created a code for the computing discipline because they needed more specific admonitions that relate directly to IT, such as that no one should enter or use another person's computer system, software, or files without permission/approval, or that one should not design or implement systems that demean individuals or groups (either intentionally or unintentionally). If people refuse to adhere to the ACM's code of ethics, their membership to the group will be terminated.

An acceptable use policy is something that most organizations that provide technology have, and it must be agreed to before services can be accessed. While both AUP and a code of ethics outline what is and what is not allowed while someone is using the organization's services, an AUP must be agreed to before access to a specific technology such as public wifi, while a code of ethics is a requirement to join certain organizations.

I looked at Cleveland Clinic's AUP and was interested in looking at how technology in health organizations are different than other sites. The specific policy I looked at was there social media policy and how employees cannot post any content from the intranet that we see while we are at work. Doing so or even worse, posting any protected health information on Cleveland Clinic's social media sites will be a violation of their acceptable use policy and will lead to consequences up to and including termination. In addition, as a non-employed guest, one cannot post anything illegal, hateful, or misrepresentative and doing so would be a violation as well.

*https://my.clevelandclinic.org/about/website/social-media*

#### Intellectual Property ####

WIPO is the global forum for intellectual property services, policy, information, and cooperation, and their mission is to lead the development of a balanced and effective international IP system that enables innovation and creativity for the benefit of all. They are important because they help governments, businesses and society realize the benefits of IP by providing a policy forum to shape balanced international IP rules for a changing world and global services to protect IP across borders and to resolve disputes.

A copyright is obtained by the simple act of creating the original work in the US, meaning they own the work as soon as they create it. However, for a work that will be used commerically, it is advisable to register with the US Copyright Office, as it is needed to bring legal action against someone using work without permission. So if I wanted to make sure nobody claimed credit for the SVG image I created, I would copyright it so I could sue anyone who used it without my permission. If the svg image became an item that identifies a source of goods or services, a trademark would defend against infringement and protect the consumer by making sure other people cannot use that image to sell their own products.

COPPA requires websites collecting information from children under the age of thirteen to make a good-faith effort to determine the age of their users and obtain parental consent if under 13. FERPA protects the privacy of student education records and specifies that parents have a right to their child's educational infomation until the child is either 18 or begins to attend secondary school, at which point control of that information goes to the child. Finally, HIPAA specifically singles out records related to health care and gives patients specific rights to control their medical records, requires health care providers and others who maintain this information to get specific permission in order to share it.

## Conclusion ##

This last unit was a great way to end the semester, as it examined both things that I had learned before while furthering my understanding of it as well. I have used SQL and databases often but this chapter helped me understand the thinking behind many of the processes. Finally, we looked at ethical and legal implications of technology and looked at some specific laws and agreements. I truly enjoyed all the units in this course and look forward to using what I have learned during this semester to understand more advanced IT concepts in the future.
