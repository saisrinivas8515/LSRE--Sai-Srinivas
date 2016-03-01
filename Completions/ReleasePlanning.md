As described in the previous submissions during the week 46 to 51, the work done is as follows:
The work done during the weeks 46 to 51 are described in the previous submission: the summary on the previous submission is as follows,
1. Read articles about the Release planning, “A systematic review on strategic release planning”, by Mikael Svahnberg, Tony Gorschek, Robert Feldt , Richard Torkar , Saad Bin Saleem ,Muhammad Usman Shafique.
2. Started clarifying on the already posted issues, added duplicates and clarifications to the posted issues.
3. Added dependencies to the issues and clarified issues by adding the new requirements. 
Follow the link to find the issues added by me: 
4. Assigned myself some issues, mostly i tried to stick to one domain (or similar to the domain).
Follow the link to find the issues assigned to me:
 
Summary of the methodology followed:

Requirements prioritisation:
	To know the importance of the prioritisation, the following articles were studied and the main points were

[1] Berander, Patrik, and Anneliese Andrews. "Requirements prioritization."
[2] Laura Lehtola, Marjo Kauppinen, Sari Kujala, “Requirements Prioritization Challenges in Practice”

A project manager has to retain the project scope in accordance with the schedule, time frame, budget, staff resources and quality goals. Prioritise the requirements in accordance with the importance of the particular feature to the customer. Regular check with the customers might help in case if the project is following a incremental model, so that they might be helping in telling which is the best feature to implement at the time when compared to the market. Customers and developers must collaborate for the success of the project. When large scale is considered there will be approximately 1000 of requirements which makes decisions impossible to make, prioritisation helps to cope up with these decisions. Prioritisation helps in selecting the core requirements of the system and also helps in implementing the selected requirements in order. 
While prioritising the requirements these are the factors that must be helpful to distinguish, “Importance, penalty, cost, time and risk”.
While looking at the article there exist many prioritisation techniques,
1. Analytical Hierarchy process: Systematic decision making method which compares all the possible pairs of hierarchically classified requirements and find the requirements which has high priority. While considering large scale there will be 1000’s of pair wise comparisons and this might take a lot of time.
2. 100$ test is a simple technique where there will be given a 100 imaginary points to all the stake holders and they distribute the points among the requirements. In some cases the decisions might be contradicting as the resources can be allocated only to the important features, the risk is the requirements may not be prioritised according to the actual priorities.
3. Numerical Assignment: Grouping of the requirements into three standard sub groups, must, should, optional grouping into these subgroups helps to know whether to implement the given requirements or not. 
4. Ranking: Marking a requirements in a selected ordinal scale, i.e., the most important requirement is marked as 1 and the least as n (considering if there are n requirements). Difference of opinions might arise, and they can be mitigated by combining different stakeholder opinions but it is a time consuming process.
5. Top ten requirements: The method is picking up the top ten requirements by each stakeholder from the available ones and prioritise based on those ratings. There involves critical judgement and dealing with 1000’s of requirements could be tough.

Based on the following available techniques the decided technique used is to do a Numerical assignment or group assignment. We had a meeting and the decided methodology is to use MoSCow. The methodology suits the current project because of the deadline and version control. The versions are already given and the deadlines are fixed for each version, in this scenario the risks of not implementing certain important features rises and so the methodology is selected.

The following article describes MoSCoW [3] Sarah Hatton, “Choosing the Right Prioritisation Method”.

The methodology is to understand the relative importance of the work to be done in order to make the progress and keep the deadlines. It is based on the relative priorities. The methodology provides a vision of what to expect before even start of the project. 
The model mainly consists of grouping in four sub groups they are Must have, Should have, Could have, and Won’t have. 

1. Must have (Minimum Usable Set): Requirements placed in the category are critical to the current version of the delivery. The product is not valid without implementing these features. 
2. Should have: Requirements placed under the category are important for the product but not vital for the release. The requirements can be implemented if time permits or else they can be swept for the next release. These requirements has a fair chance of releasing in this version.
3. Could have: Requirements placed under the category are desired for the product but not necessary. The feature that could improve user functionality or user experience with the system. The requirements need not be in the current version of the release, if time permits they can be included or else they could be ignored.
The decisions between the should and could are made by reviewing the degree of pain caused by removing the requirements among all the stakeholders.
4. Won’t have: Requirements placed in won’t are agreed by all the stakeholders as least critical and or not appropriated in the following release. They could be included in the next releases if all the resources permits or else they are ignored.

Moscow method is highly suitable when there are changing requirements, It provides stability to the project by accumulating the requirements, i.e., new requirements could be adjusted by prioritising without affecting the already prioritised requirements. The method is suitable for both small scale and large scale requirements, it is easy to perform and quick to understand.
Prioritising the requirements early might reduce the amount of risk of deviation into other areas [3].

On the down side it doesn't offer any support for making the decision, i.e., a manual decision or a expert opinion is required ignorer to rate the priority of a requirement and compare it to others. Some times decisions such as should or could are impossible to judge. After prioritising won’t for the current version, it is tough to make the decision to include it or not in the next version.

Since the prioritisation method is chosen and i started working on the assigned requirements and there were dependencies between the requirements. To understand which ones to implement in the following release and which ones to ignore, the following article helped: [4] “An industrial survey of requirements interdependencies in software product release planning." 
Requirements should be selected for a release plan so that there are less number of interdependencies among them. The identified interdependencies will lead to the requirements with more dependencies in the same release, and each release can be a working product. According to the article there exists 6 types of interdependencies they are: AND, OR, REQUIRES, TEMPORAL, ICOST, CVALUE. 
Understanding the dependencies between the articles lead to the successful prioritisation of the requirements, when every one contributed.
After the prioritisation of the requirements according to the MoSCoW methodology the document is uploaded to and the link is https://drive.google.com/file/d/0Bz_7Gx1hn6L9ZmhOalZhbEx0NjQ/view

After the prioritisation according to the milestones is done, the assigned requirements are 
1. Restricted Interface - Version 0.1
2. Managing and conduct a course - version 0.1
3. Personal start page - Version 0.1
4. Market - Version 0.5
5. Quick and easy overview - Version 0.5
6. Managing Course participants - Version 0.8
7. Participator privileges - Version 0.8
8. Personalised views - Version 0.8
9. Add new users as course participant - Version 0.8

Work done and Lessons learned:

Breaking down the requirements in Github, by posting questions. After the clarification of the issues, started adding new issues 
(https://github.com/mickesv/LSRE-ReleasePlanningProject/issues/created_by/saisrinivas8515).
Worked on levels of abstraction from the article [5], “Requirements abstraction model” and which broke down on all the requirements.
1. Product level
2. Feature level
3. Functional level
4. Component level

Further studying the article [3], provided clarity on the dependencies by these 6 interdependencies.
1. AND, 2. OR, 3. REQUIRES, 4. TEMPORAL, 5. ICOST, 6. CVALUE

As decided, i assigned my self 10 issues which are mostly interrelated. (https://github.com/mickesv/LSRE-ReleasePlanningProject/issues/assigned/saisrinivas8515)
Started labelling the issues by the labels available, and added new labels to the existing one’s.
Decided on using the MoSCoW for requirements prioritisation methodology and started working on assigning the requirements to different versions 
(https://drive.google.com/file/d/0Bz_7Gx1hn6L9ZmhOalZhbEx0NjQ/view) 
The articles [the art and science of release planning] and [market driven approach] were understood for the purpose of solving release planning and road mapping. 

During the course of release planning I have understood the following concepts, techniques for prioritising the requirements [], and the merits and demerits of the techniques.
Every release plan should have a clear goal of improvement form the previous release. The factors that might affect the release planning are dependencies among the requirements and the levels of requirements. 
 


 

 


 
