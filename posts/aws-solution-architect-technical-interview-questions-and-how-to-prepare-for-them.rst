.. title: AWS solutions architect technical interview questions and how to prepare for them
.. slug: aws-solution-architect-technical-interview-questions-and-how-to-prepare-for-them
.. date: 2018-07-13 16:36:57 UTC-04:00
.. tags: aws, job, interview, workplace, engineer
.. category: work
.. description: A presentation of the kind of questions you will be asked in the 90 minutes technical interview for an AWS solutions architect position
.. author: Jonathan Pelletier

.. figure:: /images/AWS_phone_interview.png
   :target: /images/AWS_phone_interview.png
   :class: thumbnail
   :alt: AWS asking a job candidate a web development question

Recently, I was given the chance to interview with Amazon Web Services for a solutions architect position in Montreal. I decided it would be interesting 
to share my experience of *the 90 minutes technical phone interview* that is part of their hiring process. In this post, I want to talk about:

1. The general interview process for SA at AWS.
2. The format of their 90 minutes technical phone interview.
3. The way I prepared for the interview.
4. Specific techical questions asked.

By sharing this experience, I hope I can shed some light on what's expected of IT professionnals at companies like AWS. I also want to help you prepare 
in case you are waiting for your phone technical interview for a similar role at AWS or even elsewhere. Let's get started !

**NOTE**: If you are only interested in the list of the actual questions I was asked during the interview to help you prepare, please find it 
in `this section <Specific interview questions_>`_

The Software Architect hiring proces
------------------------------------
The role I applied for is officially named: AWS Bilingual Solutions Architect. After applying online, I was contacted by an AWS staff member describing the 
hiring process. Here is my sligthly humourous, but still pretty accurate take on how their hiring process work:

.. figure:: /images/aws_hiring_flowchart.png
   :target: /images/aws_hiring_flowchart.png
   :class: thumbnail
   :alt: AWS SA hiring process

   Solutions Architect hiring *pipeline* 

There are two main events that are part the interview process:

1. The 90 minutes phone technical interview (a technical phone screening).
2. The 5-8 hours onsite interview (an in person behavioral assessment).

During the whole interview process, you will talk to AWS staff members in a non-interview context about 3 to 4 times for 15 to 30 minutes each. They talk to you so 
that they can help you *prepare* for your interviews. These conversation are simply a review of what's to come and what the person conducting the interview will 
expect to hear during this particular phase of the process. It's also your chances to ask any questions you might have. Make sure to ask the same questions to
everyone you speak to in order to make sure that the answers you get are reliable. Sometimes they are not. For example, when I asked a staff member what was the 
success rate of the onsite interview for SA, I was given different answers ranging from 10% to 60%. I suspect that this rate varies depending on how badly they feel 
they need to fill a particular position at a particular point in time.

If you need travel arragement for your onsite interview, they will fly you from your point A to their point B and take care of hosting you during your time their.
AWS require that you arrive 1 day before the interview is to take place and they will allow you to fly home the day of the interview or the day after. Depending
on your choices, you will be in the city of your onsite interview from 2 to 3 days.

I felt that the staff members are quick to respond and that it was generally pleasant to deal with them.

There are orther details about the interview process which are interesting, like the instruction they give you about a presentation you will have to give during your
onsite interview, but what I want to focus on today is the technical phone screening. 

Format of the 90 Minutes technical phone interview
--------------------------------------------------

The technical interview is a 90 minutes phone call with a software architect during which 80% of the time is spent on technical questions and the remaining 20% 
is spent on behavioral questions. I *strongly suggest* that you focus most of your preparation energy on the technical side here. I also suggest that you understand
how you are expected to steer the interview when responding to questions. This is what I describe next.

Technical Questions
+++++++++++++++++++

All of the technical questions have the same format and only differ by their subject matter. The interviewer starts by describing a situation or a problem and then
ask for a solution or your opinion. These questions will be vague and, without additional context, only terse, general answers without much content will come up 
to mind. *That* is what you must understand: these technical questions are *meant* to be the starting point of a *conversation* with the interviewer. If you ask 
the interviewer for more context before giving an answer, you will find that is answers are *scripted*. This means that they prepared in advance for this eventuality 
and thus *expected* this behavior from you. Let's illustrate this point with a concrete question example. 
It will show you how things should unfold from the start of the question:

.. figure:: /images/AWS_conversation.png
    :target: /images/AWS_conversation.png
    :class: thumbnail
    :alt: Conversation during AWS interview

    The conversation must flow from the initial questions. You can also see AWS answers are scripted

The AWS technical interviewer will never give you any *direct* feedback on the answer you provide to questions. If you happen to answer is first question directly 
with dry one word answer, you will get a "ok good." and he will just move on to the next question unceremoniously. Do not expect the interviewer to 
*ellicit directly* the behavior I just described. They want to measure if this is part of you.

Before I post what I believe is the most detailed transcript of a SA phone interview at AWS, let me describe the behavioral part of the interview first.

Behavioral Questions
++++++++++++++++++++ 

This part of the interview is all about your *past behavior*. *Past* is the important word here because they will ask you about how you acted previously in a
work related situation. They do not care about what you would do today or how you believe you will act in the future. They will try to discover, through story 
telling, how your behavioral history lines up with their `cherished 14 principles <https://www.amazon.jobs/principles>`_. 

During my phone interview, I was asked to tell a story about a time where I "went out of my way for a customer". So I told such a story. There was a special 
structure to the story too; it was a `STAR story <https://lifehacker.com/5960201/use-the-star-technique-to-ace-your-interviews>`_.

For this part of the interview, just be ready to converse at length about your work experience in a similar role.


Interview Preparation
---------------------
Broad knowledge about the question categories mentionned above is what you need to succeed with this interview. The more you know about the subject matter in the 
interview questions, the more obvious it will for how to steer the conversation in the right direction.

A very useful source that contains this knowledge is the collection of `AWS white papers <https://aws.amazon.com/whitepapers/>`_. You need to soak up the information 
found in those papers and immerse yourself into the subject as much as you can. Here is my suggested list of reading (not necesseraly in order
of importance) for the interview preparation:

1. `AWS Storage Services Overview. <https://aws.amazon.com/whitepapers/storage-options-aws-cloud/>`_
2. `Practicing Continuous Integration and Continuous Delivery on AWS. <https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf>`_
3. `Serverless Architectures with AWS Lambda. <https://d1.awsstatic.com/whitepapers/serverless-architectures-with-aws-lambda.pdf>`_
4. `Using AWS for Disaster Recovery. <https://d1.awsstatic.com/whitepapers/aws-disaster-recovery.pdf>`_
5. `AWS Security Best Practices. <https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf>`_

Also, since I felt that the use case for the questions tended to be enterprise-customer oriented. Covering you bases on the following subjects will not hurt:

1. `IAM. <https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html?icmpid=docs_iam_console>`_
2. `SAML. <https://en.wikipedia.org/wiki/SAML_2.0>`_
3. `OAuth2 and OpenID Connect. <https://www.youtube.com/watch?v=996OiexHze0>`_

Specific interview questions
----------------------------
Here are the different categories of the interview questions I was asked:

1. Infrastructure.
2. Application development.
3. High Availibility and Disaster recovery.
4. Networking.
5. Security.
6. Databases.
7. Storage.

Next is the detail of the questions I remember, for each categories. Note that I am recalling these questions from memory, it
might not have been the exact wording of the questions.

Infrastructure
++++++++++++++

Question 1
**********
A customer has deployed a three-tier web application in an AWS region. What would you suggest to this customer if he is worried
about the availability of each separate layers ?

Question 2
**********
A team wants to build a new web application. They have decided their backend would benefit from using a microservice oriented architecture. The team members know different programming language such as python,
java, nodejs, go and erlang. The team as yet to decide what will be there execution platform. What would be your suggestion ?

Question 3
**********
An enterprise customer is developping an application that uses SAML for single sign on. The customer wants to use an existing 
on-premise Active Directory as the identity provider and wants to deploy is application server on a private VPC. Explain
what needs to be done in order to meet the customer requirements.

Application development
+++++++++++++++++++++++

Question 1
**********
A team of developper is looking to modernise their software release process and they are looking to get started with devops.
What would be your suggestion to the team as a first step.

Question 2
**********
A startup wants to create a new mobile application. Describe how you would you manage user authentication in this mobile application ?

High Availibility and Disaster recovery
+++++++++++++++++++++++++++++++++++++++

Question 1
**********
A customer reaches out to you in panic and tells you that is website has been defaced. What would you suggets the customer do
in that situation to restore the website as quickly as possible ?

Question 2
**********
A customer as an RPO of zero and and RTO of zero for a certain application. What architectural decisions would you make in
order to meet the customer requirements.

Networking
++++++++++

Question 1
**********
A customer has an application running on an EC2 instance located in a publicly acessible VPC. When the customer access the 
application from the internet, the latency is 5 miliseconds. When he accesses the application from within the VPC, the latency
is 500 miliseconds. What could be the cause of that ?

Question 2
**********
A customer produces 10TB of data daily and saves that data to an S3 bucket. The customer wants to move is operation from
a european data center to a north american but there is only a 500MB/sec network link between the 2 data centers. What would
you suggest the customer do ?

Security
++++++++

Question 1
**********
A customer wants to migrate a legacy application to the cloud. The application can only be accessed using the telnet protocol.
How would you advise the customer on making this application secure in the cloud.

Databases
+++++++++

Question 1
**********
A customer has an application that uses a relational database server. At some time during the day, the database becomes 
overloaded with the resquests from the application and it becomes unavailable. How would you suggest the customer deals with
this problem ?

Question 2
**********
A customer uses a NoSQL database as part of an application. Sometimes, the application will write a value to the database and 
immediately read it, but the read operation will return the old value instead of the new value. Can you explain what is happening
? What would be a possible solution to this problem ?

Storage
+++++++

Question 1
**********
A customer need to store blobs of 1TB of data each day and keep this data 7 years for regulatory compliance. What storage solution
would you suggest ?

Question 2
**********
A customer has an on-premise application that requires an NFSv4 and 14000 IOPS. What storage solution would you suggest to the customer who wants to migrate this application to the AWS cloud.

Conclusion
----------
You now have a pretty clear description of what you will face if you are going to interview at AWS for a solutions architect role.
If you come to the interview with the knowledge required, passing the interview should be a formality. 

Do not be too nervous and good luck in your interviews !

