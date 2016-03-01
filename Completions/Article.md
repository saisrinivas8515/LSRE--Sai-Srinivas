Seminar 0:

1. Large Scale Requirements Engineering:
	Requirements engineering for the development of large scale systems with more than 1000 requirements relates to large scale requirements engineering. The way of managing and controlling the requirements when there are more in number is large scale requirements engineering [1].
 
2. Challenges in large scale requirements engineering:
	Following article was read to answer the question, [1]
		1. Large number of customer requirements: Analysing, Specifying and managing of the requirements becomes difficult.
		2. Management of customer expectations: The progress of the initial draft till the completion of the project customer expectations needs to be matched.
		3. Changing Technology: Technology changes needs to considered as the project could take several years.
		4. Distributed teams: Previous studies shows that globally distributed teams need to be carefully managed.
		5. Traceability: Creating and managing the traces is a difficult task as there might be 1000’s of requirements.
		6. Scope change: It is natural and unavoidable in the large projects, respecting the change and still meeting the initial milestones is a difficult task
		7. Resource fluctuation: Project knowledge maintenance which provide instant access to the team members is considered a difficult task when the projects are planned for large scale.
[1] Konrad, S.; Gall, M., "Requirements Engineering in the Development of Large-Scale Systems," in International Requirements Engineering, 2008. RE '08. 16th IEEE , vol., no., pp.217-222, 8-12 Sept. 2008 [2] B. Regnell, R. B. Svensson,

Summary: 

Ruhe “The art and science of release planning”, plus some more recent works on the EVOLVE methods.

	Author speaks about incremental release and how it helps customer to have an understanding on where the project is going. Generally in industry people don’t follow any good methodology, they just select and assign the requirements to the release planning. Arthur tries to improve the release planning process by integrating two approaches. In one approach communication, knowledge of human, and negotiation of conflicts, it is named as the art of release planning. For the second approach author tries to generate a solution by applying a computational algorithm which is the science of release planning. What is release planning? “selecting and assigning features to create a sequence of product releases”.  Difficulties in release planning: Optimal selection of requirements in large and very large scale is a challenge and the scope is limited to next release. Guidelines and standards (IEEE/EIA 12207.0)related to relate plan exists. CMMI level also affects the RP. In agile development often RP for next iterations are planned by physical meetings between important stake holders,  However it doesn’t provide on how to select or prioritise the features when multiple stake holders are involved. 
	⁃	Anthony Bagnall and his colleagues assign weights to customers according to their importance to the software company.
	⁃	Ho-Won Jung’s approach selects features that give maximum value for minimum cost. 
	⁃	IFM differs from other RP approaches because of its focus on revenue projections. 
Author assumed a finite set of features and finite set of RP’s, aim is to assign features to release options. Author considered two types of dependencies among the features, coupled and precedence relation. Stakeholders are considered extremely important, stake holders are given priority i.e on a scale of 1 to 9. A function is taken in which average of stakeholders, feature prioritisation is used to maximise function in every release plan. After that a set of alternatives can be formed by solving the linear programming problem in which a solution is considered and if it is 95% of object function value, it is named as exploration phase. Finally a human expert evaluates the alternatives and selects the best one which is a consolidation phase. Feature prioritisation is done by asking stake holder to assign an ordinal relative constraint to the feature. The model provides an improvement in release planning, the model has different choice of requirements based on these experts can be selected. 

R: Berntsson Svensson, B. Regnell (2015) “A case study evaluation of the guideline-supported QUPER model for elicitation of quality requirements”, 21st International Working Conference on Requirements Engineering: Foundation for Software Quality (REFSQ’15), Essen, Germany, pp. 230-246, 2015.

	The author wants to know the practitioners view on QUPER, through a case study. In this process author presents a set of detailed guidelines of how to apply QUPER in practice, including how to handle cost dependencies between quality requirements. It was evaluated at a case company in the mobile handset domain with 24 professionals using real quality requirements. A set of guidelines are provided they are: 
	1.	Identify candidate QR: Quality requirements are defined by considering the Competitors, market segments, relevant capabilities.
	2.	Define scale and units: The defined units are used to measure the level of quality. 
	3.	Identify reference levels: Reference levels of actual and competitor products are needed to be identified.
	4.	Elicit quality breakpoints: Three types of breakpoints which are utility, saturation, differentiation breakpoints are defined. 
	5.	Estimate Cost barriers: Two cost barriers need to be estimated, one is for software changes and another one is for hardware components or software architecture. 
	6.	Set candidate requirements: Make estimations and actual requirements need to be decided.
	7.	Identify cost dependencies: Identify cost dependencies between two or more quality requirements sets and judge the quality requirement based on the cost.
Based on the guidelines mentioned above, questions were framed for case study. Two evaluations are done based on interviews and questionnaires and the following results were analysed:
Some practitioners stated that it was very easy to use and all the steps are not really necessary to implement.Overall, the following were the results of the case study conducted: QUPER model is easy to understand and implement. Roadmap view is the most most important view as it shows both cost and benefit views. Benefit view may be helpful when specifying QR, and the least important one is cost view. Finally author concludes with, future work includes evaluating the QUPER model in different domains. 

Berntsson Svensson & Olsson “Introducing support for release planning of quality requirements –an industrial evaluation of the QUPER model”

	In the paper the author speaks about a conceptual model that incorporates quality as a dimension in addition to the cost and value dimensions used in prioritisation approaches for functional requirements. Tasks that a project manager has are requirements management, release planning and launching products. Lacking of a good release plan results in unsatisfied customers, and a market loss. QUPER model is developed to support release planning and roadvmapping of quality requirements. The paper is the analysis of investigation conducted in Ericsson on QUPER. QUPER model is based on the observations that quality is non linear and continuous. 
QUPER model is developed based on these three steps: 
1. Understanding different requirement decision scenarios, problem definition, 
2. three view models to define model definition, 
3. evaluating the model with industry experts, model validation.
QUPER model is designed in 3 views QUPER cost view, benefit view, and roadmap view. 
QUPER benefit view is the comparison between benefits of the product (usefulness) and quality. 
QUPER cost view is the comparison of the cost and the quality of the product. 
QUPER roadmap view is the roadmap of the breakpoints and cost barriers encountered above. 
Case study conclusions were overall results indicate that QUPER model is relevant in high level decision making for quality requirements in an activity such as release planning. 
QUPER improves communications regarding requirements prioritisation.

Regnell et al. “A market-driven requirements engineering process: results from an industrial process improvement programme”

	The paper describes a market driven engineering process which incorporates continues requirement elicitation and prioritisation with expert cost estimation as a basis of release planning. The process is described to be able to invent requirements based on the foreseen needs of the user and select them to compete in the market. 
The process is REPEAT (Requirement Engineering Process At Telelogic): It covers elicitation, documentation, and validation and has a strong focus on requirements selection and release planning. 
Actors in the REPEAT are: Requirements management group, Issuer(a person from marketing or customer support), Customers and users, requirements team, Construction team(designing and implementing the requirements), Testing team(a team which is responsible for verifying set of requirements), Expert (to evaluate), Requirements database.
Requirements can be changed or added at any time during the process, it consists of phases
Process : The initial state is NEW(stored by giving a priority),
Expert judgement is taken in ASSIGNED, CLASSIFY them by rough cost and effort estimation, 
SELECTED requirements are stored with the given priorities, in the end state the requirement is APPLIED, 
In the process of selection any requirements can be REJECTED. 
The results showed an increase in the release precision because it had effort estimation, prioritisation of user requirements, detailed requirement specification, and change management through every phase. But it had so many drawbacks such as connecting fragments and overload control. So REPEAT-2 was introduced which consisted of Hierarchical use-case modelling and Cost value use case prioritisation it improved sorting in an efficient way.

My reflections: The articles were helpful to answer the questions, articles clearly stated the subject and the context. Standard definitions were studied while reviewing the paper ”Market-Driven Requirements Engineering” which helped to answer the questions. Further literature study was done keeping the article keywords. The answers to the next question that is challenges in software engineering was found in the article “QUPER”, where the challenges were briefly described that are faced in large scale requirements engineering. In depth details about the Market Driven Requirements was found in the paper “Market Driven Requirements Engineering”, but most of the articles were related to the quality requirements and the use of them while implementing large scale requirements engineering. The art and science of release planning introduced the release planning concepts. The articles were really helpful in getting to know the topic or getting a basic idea on the topic. They also helped in my active participation for the next seminar.

——————————————————————————————————————————————————————————————————————————————

Seminar 1:

1. GAP / CVA / IVA Analysis?
	GAP analysis: GAP analysis is a formal business methodology to identify the gap between the future state and present state. The analysis consists of three stages they are: “what is done”- the present state, “what has to be done”- the future state, and “what is the gap”- identification of the gap. A graph is drawn to identify the changes, if there is a positive gap then the product is can still continue and if there is a negative gap then the product need to be analysed and changes should be done.
	CVA analysis: CVA(Customer Value Analysis) is a technique to know the customer value of the product and also the markets value of the product. Knowing the customer value on the product helps the company to predict the changes those are need to be done. The CVA analysis is about knowing the customer value of the product, present market’s competitor product and to know how to survive in the market.
	IVA analysis: IVA analysis is used for checking whether the product is inline with the company strategies or not. Here, the factors considered are time, money and risk etc. If not there then they should make certain changes.

2. What tools are available for Continuous Integration?
	1. Jenkins - Project page
		Jenkins does 2 things: building/testing software projects continuously and monitoring externally run jobs.
	2. Buildbot - Project page
		Buildbot allows you to perform your installation according to your requirement. starting with the simple processes and growing to the needs.
	3. Travis CI - Project page
		Integrating to github, travis works with project specific requirements.
	4. Strider - Project page
		It requires some knowledge of coding but it is extremely customisable.
	5. Go - Project page
		The tool visualises the entire continues delivery workflow with a value steam map.
	6. Integrity - Project page
		The current version of the tool works only with the github.

3. What is Technical Product Management?
	Managing a product by involving persons who has a understanding of the technical requirements. It is the process of defining the market requirements and planning release plan. Technical product manager needs to have a close interaction with the development teams so that the manager knows the present situations and react according to it.

4. What is road mapping? How can you do it large scale?
	Roadvmapping provides a list of releases to a product over a certain period of time. There exists many factors that might affect the roadvmapping in large scale requirements engineering. While roadvmapping in a large scale project the future trend and technology must also be considered. According to the article [2], the roadmap consists of 4 phases 
	1. Initiation - Forming a team for road mapping, determine strategies. 
	2. prioritisation - Prioritising the teams and determining the time frame.
	3. finalisation - Validation of the roadmap.
	4. followup - Periodical reviews and updates.

Summary:

Gorschek & Wohlin “Requirements Abstraction Model”

Considering the Market Driven Requirements Engineering, requirements are gathered from internal sources and also from external sources. As there will be a large and continuous flow of requirements managing and controlling becomes difficult. The requirements arrive in different shapes to the analysts. These requirements might be in any level and can be of any type such as a new feature, bug fixing and improving the quality attributes.
The authors of this paper, identified this as a gap and developed a model called Requirements Abstraction Model (RAM). Author focuses on the creation of RAM model in close corporation with industry and validated is done through feedback. Requirements gathered in MDRE process may vary in their level of abstraction in software organisations, requirements may be more detailed and some requirements are more in abstract form. The paper aims to provide recognition in the need for a model to place the requirements in the suitable level. 
The main reasons for developing the RAM model was described as direct need identified in industry and suitable method for managing the requirements on multiple levels of abstraction. 
Benefits of using the RAM model is described as, the requirements are compared with the product strategies are inline with the goals set by organisation, requirements are broken down to abstract level, the model provides a clear understanding on estimation and the effort required for the requirements, requirements on the same level of abstraction can be compared with each other, Requirements come from several levels of abstraction so that it provides understanding of each requirement. 
RAM model is implemented in 3 levels:
	▪	1. Specify: Specifying the initial requirement and eliciting enough information. Four attributes are manually specified they are
	▪	Description: provides the information about the requirement.
	▪	Reason: why the requirement is specified and benefit of the requirement.
	▪	Risk: describes the restrictions and risks with the requirements.
	▪	Title: It reflects the contents of the requirement.
	▪	2. Place: what abstraction level is specified requirements reside on. It consists of four abstraction levels they are
	▪	Product level: It is the most abstract level that a requirement can come in, the requirements are considered abstract enough to be directly able to reflect on product strategies.
	▪	Feature level: The requirements on this level are features that the product supports.
	▪	Functional level: This requirement should be a depict what a user should be able to perform, the functional activities are concentrated.
	▪	Component level: The requirements consists of information in detail. Developers can directly work on this level of requirements.
	▪	3. Abstraction: Breakdown of requirement depending on initial placement of the requirement. The process involves the creation of new requirements or linking to the existing requirements. It follows two rules to do this work, the first rule is no requirement exists without having a connection to the product level, the second rule is all requirements have to be broken down to functional level.
	▪	To validate this model, two validations are done one is static and dynamic validation. The static validation is based on reviews and walkthroughs the results were, the benefit of RAM is it has customised levels and so the organisation can use this model based on their need, and the risk involved is if the product strategies are not defined then the model cannot be used. While the developers and testers agreed that all functional or component level requirements are not always in a testable ready state. In dynamic validation the results are, practitioner’s provided a positive feedback while validating it and the action steps are easily done effortlessly and the main issue is while addition of new requirements and comparing the created requirement with original requirement. RAM helps the developers to easily work on the product, it helps managers to easily manage the requirements.

J. Karlsson, K. Ryan, “A cost-value approach for prioritizing requirements”, IEEE Software, 1997.

	 Author makes statements about the problems in selecting the subset of requirements which satisfies the customer needs and that matches the time given to complete and different estimations. Authors developed a tool for requirements prioritisation on a cost value based approach. The tool can prioritise the candidate requirements in two dimensions:
	1.	According to their value to the customers.
	2.	According to the estimated cost of implementation.   
The cost value approach prioritise requirement according to their relative value and cost.
Process: 1. Requirement engineers make sure that the specified requirements are complete and unambiguity. 
	       2. Customers or users apply AHP(Analytical Hierarchy Process) pairwise comparison method to access the relative value.
	       3. Experienced software engineers apply AHP’s pairwise comparison to check relative cost to implement each candidate requirement.
	       4. A software engineer uses AHP to calculate each candidate requirement’s relative value and implementation cost, and plots these on a cost–value diagram.
	       5. Stakeholders use cost-value diagram as a conceptual map for analysing and discussing.
AHP(Analytical Hierarchy Process):
	To help us make decisions(identify, analyse and make tradeoffs), AHP compares alternatives in a stepwise fashion and measures their contribution. The steps are as follows:
	1.	Set up the n requirements in the rows and columns of an n × n matrix(incase you have 4 requirements place and you want to know their relative value, place them in 4*4 matrix). 
	2.	Perform pairwise comparisons of all the requirements according to the criterion.
	3.	Use averaging over normalised columns to estimate the eigenvalues of the matrix 
	4.	Assign each requirement its relative value based on the estimated eigenvalues.
A case study was conducted to know the usage of cost value analysis and the results were plotted on cost value analysis graph. Finally the discussion results in the selection of requirements for the development and release planning process. The method is easy to perform the practitioners really felt useful. But the method consists of many issues and the method is more suited for the small scale requirements.

Khurum & Gorschek “A method for early requirements triage and selection utilizing product strategies”

	Market driven development is gaining interest in the recent times and it is directly affecting software development, more precisely requirements. The growing interest for the customer specific software development is responsible for the change. The main difference between MDRE and the traditional way is, it comes from internal sources (dev., sales team, bug reports etc.,) and external sources (users, customers, competitors etc.,). 
This paper presents a method that utilises strategies for early requirements triage. Performing a early triage (discarding inappropriate) can help while doing a large scale requirements. Author proposed two methods both based on a few questions: “where do we want to go”, finding out the right balance between the long term goals and short term objectives. “how will we get there”, Product strategy. “what to do”, rules of road. “why would we be successful”, to produce a competitive product strategy. “when will we get there”, roadmap. 
Part one triage: Early requirement triage, step 1 is to specify the questions, “where we want to go”, “how will we get there”, “what to do”. Step 2 is assigning weights to the answers of the questions “where to go”, “How to get there”, “where to do”. Step 3 is comparing the requirements, as of give points out of 100 for each the answers of requirements.
Part two Requirements selection for each release, Consists of 2 steps, Step 1 is to specify product-technology roadmap, gives an overview of the relationship between the product releases and successive technologies. Step 2 is Estimating the resources, using models such as COCOMO. 
Part three Strategy Rationale, documentation of the reasoning to the decisions that are answered previously in strategic questions. 
Industrial validation of MERTS is done and has been found that the method would offer decision support and structure, clarify goals, objectives and enable requirements triage. The method is found to have some drawbacks, it consumes a lot of time at the start of the project and it is a resource intense process to gather as it has the process of consulting different stake holders for the sake of business goals and formalising them to a common set. The method is validated by conducting interviews to the practitioners and found that the method is easy to implement and the method is helpful for both strategic and technical product managers. But the limitation is that the method was only validated with a reduced scope i.e., limited number of practitioners.  

R. Berntsson Svensson, T. Gorschek, B. Regnell, R. Torkar, A. Shahrokni, R. Feldt (2012) “Quality Requirements in Industrial Practice – an extended interview study at eleven companies”, IEEE Transactions on Software Engineering, vol.38(4), pp. 923-935

	When the functional requirements are only considered in a developing a product it leads to dissatisfaction and failure. So while developing a product, Quality Requirements should be focused. The authors identified two types of the companies called business to business companies(B2B) and Business to customer(B2C).  
The main goals of the article is to investigate the most important quality requirement, the interdependencies between the quality requirements in the companies and how the cost estimation is performed and how accurate is it on the quality requirements. 
Authors conducted interviews in 11 companies based on the questions framed and has been identified, the most important quality requirement for B2C is usability and B2B is safety.
The most common interdependency types are found as REQUIRES to B2C and CVALUE to B2B. Finding dependencies is identified to be a complex task and with large scale in place it is further more difficult, but they have impact on the planning, design and quality. 
There isn’t any distinction between the quality requirements and functional requirements during the cost estimation.
The quality requirement that are dismissed are not reassessed, authors have depicted that during the dismissal of quality requirements there is a clear gap between the project leader and project manager. Quality is requirements are dismissed for the reasons such as low priority than functional requirements and cost estimation. 
A quality requirement is reconsidered when insisted by the customer and discussed with developers, and they take decisions depending upon the timeframe available.

Gorschek & Davis “Requirements Engineering. In search of dependent variables”

	The paper describes the framework of dependent variables while accessing the requirements engineering. The author concentrates on how organisations can improve the process of performing Requirements Engineering in a project. 
Assessment can be made on two bases, these are: 1. Comparison of the requirements process where organisations can measure the time or effort to the best practices available, 2. The initial product that is the result of conducting the requirements engineering process, this could be measured in terms of quality of the requirements of the product.
Author states that, while attempt to improve the requirements engineering process most organisations fail in giving importance to the resulting product. To address this dependent variable have been found, which could actually accelerate the requirements engineering process. The different levels that are identifies are mentioned below:
	1	Phase: Two main attributes in this level are cost and quality. The cost is the effort required per each requirement and total development duration. Similarly quality can be the quality level of the requirements specification document.
	2	Project: The phase is compared with the project success, the factors like time and budget and if all the requirements are met. The attributes will be same as the above level.
	3	Product: Product success is determined by comparing them against factors that are customer satisfaction on the final product and all their requirements. The attributes for this level are selection of the requirements and degree of impact on the customer.
	4	Company: How the products sale in the market determines a companies success, fate of the project is determined if the project is completed late and over budget.	
	5	Society: If the product proves to harm the society, even though it earns money the product is considered to be a failure. so companies want to make sure that the product to be a success without harming the society.
The paper delivers the knowledge in the form of different levels and the impact of requirements engineering can be withdrawn. The success of a product can be considered from the given levels. The goals of the product should be of present goals, the future goals should inline for the product in future. There is a necessity in drawing a roadmap to know the present requirements and then the limit must pushed for requirements which align for future. 


My reflections: Articles given where really helpful for answering the questions given, GAP and IVA analysis were briefly described in the paper “requirements engineering. in search of dependent variables”. As the basic information was known a detailed study could be done on the topic. GAP, CVA and IVA analysis were searched on various online sources with the knowledge that the paper gave me, and i was successful in extracting the answers. Next question was “tools available for continues integration”, with little or no known information various online sources were searched as there was no literature identified. The next question was to define technical product management, as i couldn’t find the answer in any article, i looked up for the literature in databases and i found and the article was helpful in gaining knowledge about technical product management and technical project manager. Roadvmapping was introduced in the paper “requirements abstraction model”, and the basic knowledge was further improved by literature study. Among all the articles the paper that is i felt important was “Requirement Abstraction Model”, the Abstraction model gives a view on how requirements should be handled. The cost value approach and MERTS are found useful in certain cases in industrial practice. Quality Requirements in industrial practice identified the importance of interdependencies.

————————————————————————————————————————————————————————————————————————————————————

Seminar 2:

1. Boston Matrix- It is an informal tool to find out where the product is standing in the market with respect to both the market share and market growth. It will help the companies to find the the product present state and what is needed to get to the desired state. When market growth and market share are considered the matrix is divided into four squares. 
The states are 
	Dogs - Low market growth and also low share. They show no signs of development and they always need more money than the output.
	Cash Cows - High market share with low product growth. They sit in the market and earn the companies, companies might plan for a rerelease keeping the present market and technology but the best thing to do is enjoy the cash turnover and sendoff when turns into a dog.
	Question marks - Low market share but high product growth. There is an increasing demand in the market but the product will not earn any money. As the state is dangerous for any company the product could be turned into cash cows or stars.
	Stars - High market share and high market growth, it is the ideal state a product can be in.
It is useful to know whether a product can be invested or maintain or drop. 

2. How do you connect your requirements to your architecture? 
Requirements are the properties of the system, so basically they act as design goals and based on the goals architecture is built. Goal might be built on the functional or non functional requirements. Based on the architecture there are 4 systems 1. pattern based architecture design, 2. Multiple view model, 3. Evaluation based architecture design, and 4. Transformation based architecture design. Different models are used as per the suitability of the requirements and architecture.

3. Can you connect all requirements directly? What do you do if you cannot?
As the abstraction level of the requirements changes all the requirements cannot be connected directly. In order to connect the requirements the vague requirements must be worked up and the abstract requirements should be worked down.

Summary:

v.d. Weerd & Brinkkemper “Towards a reference framework for software product management”

The paper provides a reference framework for software product management. The author identifies key terms, research questions and education to managers. Software product management is about requirements management, managing portfolio, road mapping, release planning for a software product. 
Before finalising the framework author conducted a literature review and then created a reference framework and validated through a case study form the product managers. The proposed framework is based upon artefacts and stakeholders. 
The artefacts consists of different hierarchy levels which consists of the following 
1. portfolio management - managing the products, introducing new changes, decisions regarding lifecycle of product, trend decisions
2. roadmap of products in a time frame - product is planned for long-term and also planning of technological resources, elements and their relationship with the product
3. release planning - the requirements are prioritised based on a method then the next release product requirements are selected.
4. requirements management - analysing the requirements, removing any redundancy in the requirements and linking the requirements based on their functionality then these are organised according to the product.
The paper describes the stakeholders as 
1. Internal stakeholders - Developers, testers etc.
2. External stakeholders - Customers, competitors etc.
The selected requirements are documented and finally they are validated by the stakeholders to start the development process.

Regnell & Brinkkemper “Market-Driven Requirements Engineering for Software Products” (Chapter 13 in Engineering and Management of Software Requirements)

The paper follows on challenges faced in market driven requirements engineering context. 
Authors stated that software products have two dimensions: 
1. Degree of customisation - Further classified into three,
	1. generic products, 
	2. customisable products,
	3. customer-specific products
Generic level product is used with minimal configurations to be done by the end-user. A customised product is useful after it has been developed according to the needs of a specific customer.
2. Hardware and software content - 
	1. pure hardware in which products are fixed to particular hardware architecture, 
	2. embedded systems are the products which consist of hardware and their embedded software,
	3. pure software is the products independent of hardware.
In the context of MDRE the process should maintain a continuous flow while having informal discussions with the requirements throughout the life cycle and the organisation should take risks alongside the decisions in the key activities and release planning focussing on time-to-market and return-of-investment.
Challenges faced in MDRE are described as follows by conducting a survey at five different companies. 
	•	Balancing market pull and technology push: the challenge that is balancing technology-based requirements and market needed requirements. 
	•	Chasm between marketing and development: Communication between the market analysts and developers need to be good to have a quality product. 
	•	Organisational instability and market turbulence: Key people leaving the organisations is a risk of lacking necessary documentation and structure, when a new person comes he should be able to adopt.
	•	Simple tools for basic needs: Simple tools for preferred for the basic activities as the challenge is to find solutions to the problems. 
	•	Requirements dependencies: The dependencies between requirements are a major challenge as it makes the release planning process complex. 
	•	Cost-value estimation and release planning: Release planning is a major task and the Cost estimation is a major challenge.
	•	Overloaded requirements management: Maintaining the requirements becomes difficult as the requirements are overloaded. 
Main characteristics of MDRE process is to do the road mapping and release planning. A taxonomy was established which creates roadmaps. This taxonomy scheme classifies roadmaps broadly into four categories: Science and technology roadmaps, Industry technology roadmaps, Corporate or product technology roadmaps, and Product or portfolio management roadmaps.  
The major challenges in MDRE process is find the type of requirements, there are two types of requirements, 
Alpha requirements- They are golden grains as these add value to the product.
Beta requirements- These are low quality and these requirements must be rejected.
These impacts the success of the product. A release plan is formed from a roadmap document and a set of requirements are selected to analyse and a workable product is built.

D. Leffingwell “Scaled Agile Framework” Link: http://v3.scaledagileframework.com/ 

Scale agile framework by Leffingwell consists of these layers: portfolio, program and team. 
1. Portfolio: The portfolio layer consists of the release of stories in time spans, the architecture also evolves according to these stories, product portfolio management talks 				about the content, integration and releasing. 
		It also contains portfolio backlog in which the current stories along with the future  story is stated.
		The layer also consists of portfolio metrics in which it measures the lean portfolio metrics, Kanban metrics, they are used to show the progress by different charts. 			These metrics are helpful in managing the portfolio layer. Generally a typical agile team will define, build and test a system, the number of individuals will range between 		50 to 125. The layer concentrates on the technology oversight, business needs are identified and these are prioritised. Occasionally management also provides a 			certain feedback to the teams based on their progress and team layers. 
2. Program: The program layer consists of a chain of people from technical departments like developers, architects, testers, designers etc., to coordinate mutually and have a 			better solution to the needs of the business. Project is visualised and the stories are road mapped as per the customer requirements and to have view of the future of 			the product. To get a working product only the features of the products and these are implemented by the technical staff, based on release of demand components. 			Every agile release train will go through this type of implementation. The scale agile framework meet the business needs by mitigating the barriers by following above 			steps.
3. Team: The team layer is a mutual understanding between team members. Also teams can be self- organising, autonomous and global teams, traditional dividing of roles in a 			team is not encouraged in order to have a understanding among the team members and better working efficiency. The agile teams develop the product in 					iterations so each story is fitted into suitable iterations.

Wnuk et al. “Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering”

There is much difference between the scope of the release and scope of the project. Scope of the release: the requirements which are to be developed on the particular release and Scope of project: the requirements which are developed on the whole project. In the paper authors tried to investigate the causes and effects of over-scoping a project and how does a agile practice affect the situation. A case study was conducted in a company that deals with very large scale requirements and it consists of many units like requirement unit, software unit, product unit, and usability design unit. The units are responsible for collecting, managing, maintaining the scope of requirements to implementing them. The company uses a stage gate model which consists of milestones to manage the project. In a total seven milestones the scope is updated for each milestone. Milestone 2 does all the scoping and all the requirements are domain-specific. 
The company introduced agile at the time of case study. Author identified and specified the agile requirements engineering practices they are mentioned as: release planning flow in which the scope is continuously managed and one continuous scope, The team should decide on the changes of scope and values assigned to the feature, gradual and iterative dealing of requirements, integrated requirements engineering, acceptance criteria. 
Case study consists of 3 phases, in the first one the author assumes some causes and hypothesis. The assumed hypothesis are used for interviewed in the second phase. In the third phase, the results are validated by conducting the interviews with six practitioners.
The results are analysed and found that over scoping can affect the overall project development, this is considered to be one of the most crucial part of decision making. The study has shown various factors that look up to over scoping. 
Some of the causes of over scoping are continuous requirements inflow, overview of responsibilities, less involvement of development team, unclear vision of the goals. 
The effects are change to project scope, delays, quality issues etc.,
Applying the agile principles causes some less damage to the project i.e., critical features are not delayed, and fast feedback etc.
Finally the author mentions that through the implementation of agile principles the overscoping the project cannot be avoided. So over scoping is still a challenge to all the large scale industries.

Wnuk et al. “Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”

The software product should be on par with the market needs to gain profits. Client needs continuous improvising and making necessary changes to the product. Directing and choosing these progressions are important for making a mark in the business sector. Decision making is a critical process when choosing the required features that are to be included in a product. These decisions are based on several characteristic needs.
It is exceptionally hard to choose which change prerequisites ought to be incorporated. To successfully enhance the RE, decision making ought to be committed towards decision-making perspective. It is imperative to recognize the elements that influence the decision lead time and the outcome. Here the lead time implies the time from when the issue is accounted for and the decision is made whether to acknowledge or dismiss the reported issue. Likewise the relationship between the decision outcome and attributes furthermore the relationship between the choice result and choice lead time.
In early stages, these qualities are found through the organization's log and made a factual examination on it and after that an overview is led with different experts who are not from vast scale industry. At that point the overview results are contrasted and the contextual analysis comes about. The aftereffects of the paper are as follows. The qualities which affects the decision lead time are Number of items, Release number, and kind of client. As the number of items are more it requires more decision lead investment. So the choice can be made rapidly if the multifaceted nature of the issues can be lessened by separating into smaller issues. At that point discharge number product offering trait change and lead time relationship is fluctuating.
According to this paper, this organization has more functionalities in the prior release so additional time is taken for right on time release than later releases. Additionally, another finding is that there will be no relationship between these two as an ideal opportunity to settle on a choice is same for all releases. At that point the relationship between the kind of client and their impact on lead-time for choice is estimated. The choice result and various items influence relationships that are the major share of the choices will get rejected and for extensive scale commercial enterprises, the quantity of ventures do not have any impact on choice result.
Likewise, this is a contextual investigation where information form only one organization log is not adequate to sum up the outcomes as the result in this paper negates. At that point the release number and decision result additionally have the same issue that the summed up result is not given. As the study respondents are for the most part from bespoke tasks while the considered organization is business sector driven. So the relationship between release number and decision result won't be the same and can't be summed up with a solution. At that point the kind of client and decision result will be more acknowledged of issues when the client is more vital and less acknowledgment for the client with less significance. The lead-time fluctuates for decision result which is bolstered by the decision log as the rejected choice takes additional time then acknowledgment choice while entirely repudiating result is raised from the review. The primary reason is said that the study respondents are not quite the same as the case concentrated on the organization. So the distinction is differed. This paper is helpful for specialists as there is an examination crevice in it as there is no summed up result in this paper. This paper offers the professionals to know the choice that some assistance with decision making process time and whether that much time should be utilized or a better a choice which has less losses when executed than squandering time to choose.
My perspective on this paper is that it is better in the event that they chose huge scale industry specialists as their specimen populace so better results might be there. This paper gives the distinction of choice making in expansive scale and little scale commercial enterprises. These can be concurred as there is very repudiate results in this paper and there is a need of further research with the premise of this paper.

P. Carlshamre, K. Sandahl, M. Lindvall, B. Regnell, J. Natt och Dag, “An industrial survey of requirements interdependencies in software product release planning”, in Proceedings of the fifth IEEE International Symposium on Requirements Engineering, 2001.

An incremental development has been most important part of the industrial use and had led to most important developments. In this type of incremental development prioritization of the requirements plays an important role and interdependencies and nature of requirements is not known. Hence it draws the attention of further research in this area. This research is carried by conducting an informal survey with five different companies. These five cases are outlined briefly.
Requirement managers from different company types small company, medium company software engineering institute, large telecommunication company. Different types of interdependencies are given as AND, REQUIRES, TEMPORALCVALUE, ICOST, OR.
The value related and functional related interdependencies have been tabulated. As it mentioned prioritization of the plays important role in release planning. The relationship between requirements, and the interdependencies have been categorized.
In the present survey, 20 percent of singular requirements have been identified. Identification of the singular requirements is less time consuming. If two requirements are have similar kind of slogans then it means they are related to each other. To identify similarities and support the identification of interdependencies between the requirements lexical analyser has been applied to the collected data from companies.
Dependent requirements have been identified and it has been found 20 percent has been identified from the collected data. An interdependencies is calculated this situation is similar to the low coupling in design phase. The same kind of reasoning and terminologies could be used and degree of requirements coupling and release coupling is defined. From the identification of interdependencies the release planning will find a minimizing the release coupling.
The research paper had made huge contributions towards the market driven software development. It has provided an insights about how the ideal case of requirements interdependencies has deviated. It was also concluded that only few requirements are responsible for interdependencies. The visualisation has been most powerful full for identification of the interdependencies. The further research in area could be useful and needs further treatment

My reflections: The questions in the seminar is to discuss about the Boston Matrix and connection of the requirements with the architecture of the software. The articles given in the seminar doesn’t discuss about this and various sources were studied to answer this. The article “Market Driven Requirements Engineering” gave a clear idea on how a MDRE project works. The article describes the techniques that are currently used to demonstrate the challenges faced. Another article i found interesting was the one with the interdependencies, the article specifies that there are 6 interdependencies that must be considered in order to release a perfectly working product. Overall the above discussed articles gives good knowledge on various aspects.

————————————————————————————————————————————————————————————————————————————

Seminar 3:

Summary:
Wnuk et al. “What Happened to Our Features? Visualization and Understanding of Scope Change Dynamics in a Large-Scale Industrial Setting” 

Changing requirements and evolving technologies are the two factors which are affected while taking decisions on the features to be implemented when developing software platforms for product lines. It is necessary to continuously assess the changes in the domain as it shows impact on scoping decisions. There is a need for change in decisions as circumstances change, which results in a dynamic transformation of the scope. The authors in this paper have put forward a technique called Feature Survival Charts (FSC) which shows changes in the scope over time and these changes can be viewed in several colors, where each color represents change in the scope. In order to evaluate and validate the technique proposed, it has been implemented on three projects. For complex systems, requirements can be counted in thousands and is not mandatory that all of them are to be included in the future development projects. Hence, a subset of requirements is to be selected and this selection process is called scoping. The technique is proposed to find the reasons behind the changes in the scoping process, which is the problem of product line projects. This technique is a remedy for the above mentioned problem. The company selected to evaluate the technique is large and uses a stage-gate model where, the project progress in the companies is controlled by several milestones and tollgates. The practitioners involved in development and evaluation of the FSC chart and corresponding tracking measures are: a process manager, two requirements manager and a Key Performance Indicators (KPI) manager. The projects chosen or selected to evaluate the technique are based on the length, number of features considered in the scope and the possibility to analyze and visualize important changes in the scope of the project. All the three projects have different starting points and are at different milestones. The similar group requirements analysts of the project are affected, but they differ in the size, time of analysis and complexity of the project. 
The results indicate that, with a significant increase or decrease in the number of features, there is also an increase or decrease in changes in the scope. Therefore numbers of features and change in scope are proportional. In case of time length, it is inversely proportional. With the increase in the time length, the change in scope decreases and with the decrease in the time length, the change in scope increases. To measure the tracking of the scope, the measurements are divided into time related and feature related measurements. Generally, the goal of the measurements is to portray the velocity and volatility of the scoping process. Each of the time related and feature related measurements are divided into a set of scope tracking measurements. Time related measurement is defined with only one measurement: Number of positive and negative scope changes per time stamp/baseline (M1). Feature related measurement is defined with four measurements: Time to feature removal (M2), Number of state changes per feature (M3), Time to birth (M4), Reason for scoping decision (M5). The theoretical analysis of proposed measurements are compared and are tabulated. Two approaches were used to tabulate the theoretical results. The subjective analysis of results requires a deep and extensive domain knowledge and further additional information. Therefore, this is acquired and gathered by interacting with requirement managers. Theoretical validation is truly situation dependent and thus should be repeated for every new situation. Apart from the theoretical analysis, empirical evaluation of measurements is also performed. They are represented through graphs. 

The visualization technique presented in the paper provides feedback on the ongoing scoping activities in projects in the companies. The measurements given in the paper are inclined towards complementing the visualization technique. The results are positive and are considered valuable as acknowledged by the practitioners who were involved in development and evaluation. The industrial evaluation that is on applying the technique to the company projects paved a way for the application of this technique on other large scale projects. Although, the applied company is large and deals with developing of technically large projects, the results cannot be generalized as the complexity of projects may vary from company to company. Therefore, it would be better if the results are interpreted with some caution. Additional and in-depth studies on scope dynamics visualization would further increase our basic knowledge and understanding on its usefulness. The technique can be further enhanced by zooming interactively, depicting the size and complexity of features by anticipating their relation.


Wnuk & Gorschek “Obsolete Software Requirements” 

Rapid changes in the technologies and changing needs and demands have challenged the traditional requirement engineering practices. It’s very important to identify the outdated or obsolete requirements. Not much research has been done in the field of obsolete requirements and not many are even familiar with term obsolete requirements. The present research tries to find out what are obsolete requirements, how do they impact the industry and how the industry copes with such requirements.
An empirical investigation was carried out with the help of 219 respondents from different software organisations located in 45 countries. After the data collection, statistical analysis is done using chi square method. According to the analysis majority of the software practitioners have said that obsolete is serious issue in the requirement engineering process. Different dimensions of the obsolete requirements like type of OSR (Obsolete Software Requirements) that will become obsolete, methods to identify and manage these requirements were precisely described.
From results it was known that most of practitioners defined these requirements as the requirements which are in no longer use and also having OSR was a serious challenge for the software organisations. The standard requirements which are law based are less likely to become obsolete, but the ambiguous requirements have more probability to become obsolete. There are few tools and methods to identify these type of requirements but the data shows there are no sure tools. Many of the respondents try to keep the obsolete requirements without deleting them to have traceability and reference. Finding out the obsolete is predominantly a manual process and only few respondents are willing to have automated tools for identification. It was also known that OSR impacts are more on the large and very large scale projects.
The research clearly indicates the importance and challenges of having the obsolete requirements. It has precisely explained about identifying and managing obsolete requirements. The authors have made a huge contribution by identifying the different tools and methods to manage these obsolete in the given project. The research also exemplifies the need of the automated tools for identifying and management of obsolete requirements to mitigate the present challenges of existence of OSR’s

My reflections: The first paper described that the technique developed for easy viewing of the scope changes are useful for companies, as the scope consists of features and the features consists of requirements. The seminar discussion on the articles was that it makes much difference when there are a huge pile of requirements than the smaller requirements. The second paper focuses on the requirements that are not used by a company and a companies always focuses for the which requirements are useful. Based on the previous data the author tries to determine the obsolete requirements.

———————————————————————————————————————————————————————————————————————————— 

Seminar 4: 

1. What tools are available for requirements management? 

	Enterprise level management tools - Enterprise level implementation but very costly and loaded with features.
		IBM Rational DOORS
		Borland Caliber
	Mid market management tools - They maintain nice balance, targeted for mid range market.
		Accompa
		Jama
	Entry level management tools - Affordable tools which are not that great.
		Atlassian JIRA
		FogBugz
	Open source management tools - aNimble 

2. For agile requirements management tools:
	Jira Agile, HP Agile Manager, VersionOne, Work Management.

"Assessing challenges of continuous integration in the context of software requirements breakdown: a case study"

Continuous Integration (CI) is the concept in which the teams do integration of the code daily multiple times. As the process is most suited to the agile methodology, many companies adopted it.There is a need for breakdown of the requirements to maintain continues integration, thus the quality of the code can be maintained and time is also not wasted.
The thesis is mainly focussed on assessing the challenges of continuous integration and requirements breakdown and their influence on the whole process. The author conducted a case study at Ericsson to identify the challenges and also conducted interviews to collect the opinions. 
Author identified that the following process is being followed: 
- the code is developed and pushed into work branch
- after the functionality is developed it pushed to latest local version branch in which tests are conducted
-if it passes the tests then these new changes are pushed into pre-test build 
- regression tests are conducted and 
- finally the code is pushed into latest stable version and the whole system is tested.
Ericsson appoints operational product owners as they will prioritise the requirements so team members can easily breakdown the requirements and update their sprint backlog from this product backlog. The challenges that are faced in the company are identified in this case study: 
- The mindset of developers
- Tools and infrastructure
- software requirements
- testing tools which support CI
- code dependencies
- Understandability
- Domain applicability
Requirement abstraction is a major challenge considering breaking down the requirements, as for most of the requirements it is hard to find abstraction levels. Along with that there are few more challenges alignment of requirements, customer value to satisfy. Customer may think that the developed features are not useful, and guiding principle need to be there provide a clear guidance on break down of requirements. 
Requirements break down led to the development of smaller units and these units are provide challenges for the companies to carry out the testing. Hence these must be combined to form features. Using CI to product delivery is possible but the number of integrations done should be generalised and finalised. 

Reflections: The authors identified some challenges from CI and also from the perspective of the requirements breakdown, that helps the companies to handle these challenges before integration. CI is an important as it will deliver high quality product with in the specified time frame. A range of continuous integration tools are there in the market which can be used to provide a better management in the area.








