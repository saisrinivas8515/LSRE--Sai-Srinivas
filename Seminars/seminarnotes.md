What is large scale requirements engineering?
According to  the thesis written by Krzysztof Wnuk, "Understanding and Supporting Large-Scale Requirements Management". If the size of the system and complexity of software continues to increase, they result in large sets of requirements.

What are the challenges in large scale requirements engineering?
Challenges that exisits are Large number of customer requirements, Formal interface to customer, Management of customer expectations, Changing technology, Traceability, Scope change and creep, Resource fluctuation.

What is the order of magnitude of the number of requirements we are discussing?
Approximately 1000 requirements are considered to be large scale according to the paper "Can We Beat the Complexity of
Very Large-Scale Requirements Engineering?".

Release planning: Prioritising RP depends on the importance of stakeholders. Features are prioritised according to the available resources and importance of stake holders.

The Art and science of release planning:

	Author speaks about incremental release and how it helps customer to have an understanding on where the project is going. What is release planning? “selecting and assigning features to create a sequence of product releases”.  Difficulties in release planning: Optimal selection of requirements in large and very large scale is a challenge and the scope is limited to next release. Guidelines and standards (IEEE/EIA 12207.0)related to relate plan exists. CMMI level also affects the RP. In agile development often RP for next iterations are planned by physical meetings between important stake holders,  However it doesn’t provide on how to select or prioritise the features when multiple stake holders are involved. 
- Anthony Bagnall and his colleagues assign weights to customers according to their importance to the software company.
- Ho-Won Jung’s approach selects features that give maximum value for minimum cost. 
- IFM differs from other RP approaches because of its focus on revenue projections. 
Author assumed a finite set of features and finite set of RP’s, aim is to assign features to release options. Author considered two types of dependencies among the features, coupled and precedence relation. Stakeholders are considered extremely important, stake holders are given priority i.e on a scale of 1 to 9. Feature prioritisation is done by asking stake holder to assign an ordinal relative constraint to the feature.


Introducing Support for Release Planning of Quality Requirements – An Industrial Evaluation of the QUPER Model 

	In the paper the author speaks about a conceptual model that incorporates quality as a dimension in addition to the cost and value dimensions used in prioritisation approaches for functional requirements. Tasks that a project manager has are requirements management, release planning and launching products. Lacking of a good release plan results in unsatisfied customers, and a market loss. QUPER model is developed to support release planning and roadvmapping of quality requirements. The paper is the analysis of investigation conducted in Ericsson on QUPER. QUPER model is based on the observations that quality is non linear and continuous. QUPER model is designed in 3 views QUPER cost view, benefit view, and roadmap view. QUPER benefit view is the comparison between benefits of the product (usefulness) and quality. QUPER cost view is the comparison of the cost and the quality of the product. QUPER roadmap view is the roadmap of the breakpoints and cost barriers encountered above. Case study conclusions were overall results indicate that   QUPER model is relevant in high level decision making for quality requirements in an activity such as release planning. QUPER improves communications regarding requirements prioritisation. 


A Market-DrivenRequirementsEngineeringProcess:Results from an IndustrialProcessImprovementProgramme:

	The paper describes a market driven engineering process which incorporates continues requirement elicitation and prioritisation with expert cost estimation as a basis of release planning. The process is described to be able to invent requirements based on the foreseen needs of the user and select them to compete in the market. The process is REPEAT (Requirement Engineering Process At Telelogic): It covers elicitation, documentation, and validation and has a strong focus on requirements selection and release planning. 
Actors in the REPEAT are: Requirements management group, Issuer(a person from marketing or customer support), Customers and users, requirements team, Construction team(designing and implementing the requirements), Testing team(a team which is responsible for verifying set of requirements), Expert (to evaluate), Requirements database. 
Process : The initial state is NEW(stored by giving a priority), Expert judgement is taken in ASSIGNED, CLASSIFY them by rough cost and effort estimation, SELECTED requirements are stored with the given priorities, in the end state the requirement is APPLIED, In the process of selection any requirements can be REJECTED.   


A Case Study Evaluation of the Guideline-Supported QUPER Model for Elicitation of Quality Requirements: 

	The author wants to know the practitioners view on QUPER, through a case study. In this process author presents a set of detailed guidelines of how to apply QUPER in practice, including how to handle cost dependencies between quality requirements. It was evaluated at a case company in the mobile handset domain with 24 professionals using real quality requirements. A set of guidelines are provided they are: 
1. Identify candidate QR
2. Define scale and units
3. Identify reference levels 
4. Elicit quality breakpoints
5. Estimate Cost barriers
6. Set candidate requirements
7. Identify cost dependencies
Based on the guidelines mentioned above, questions were framed for case study. The following were the results of the case study conducted: QUPER model is easy to understand and implement. Roadmap view is the most most important view as it shows both cost and benefit views. Benefit view may be helpful when specifying QR, and the least important one is cost view. 


A Cost–Value Approach for Prioritising Requirements:

	 Author makes statements about the problems in selecting the subset of requirements which satisfies the customer needs and that matches the time given to complete and different estimations. Authors developed a tool for requirements prioritisation on a cost value based approach. The tool can prioritise the candidate requirements in two dimensions:
1. According to their value to the customers.
2. According to the estimated cost of implementation.   
The cost value approach prioritise requirement according to their relative value and cost.
Process: 1. Requirement engineers make sure that the specified requirements are complete and unambiguity. 
	 2. Customers or users apply AHP(Analytical Hierarchy Process) pairwise comparison method to access the 			   	    relative value.
	 3. Experienced software engineers apply AHP’s pairwise comparison to check relative cost to implement each 			             candidate requirement.
	 4. A software engineer uses AHP to calculate each candidate requirement’s relative value and implementation      		             cost, and plots these on a cost–value diagram.
	 5. Stakeholders use cost-value diagram as a conceptual map for analysing and discussing.
AHP(Analytical Hierarchy Process):
	To help us make decisions(identify, analyse and make tradeoffs), AHP compares alternatives in a stepwise fashion and measures their contribution. The steps are as follows:
1. Set up the n requirements in the rows and columns of an n × n matrix(incase you have 4 requirements place and you want to know their relative value, place them in 4*4 matrix). 
2. Perform pairwise comparisons of all the requirements according to the criterion.
3. Use averaging over normalised columns to estimate the eigenvalues of the matrix 
4. Assign each requirement its relative value based on the estimated eigenvalues.
A case study was conducted to know the usage of cost value analysis and the results were plotted on cost value analysis graph.

A Method for Early Requirements Triage and Selection Utilising Product Strategies:
	Market driven development is gaining interest in the recent times and it is directly affecting software development, more precisely requirements. The growing interest for the customer specific software development is responsible for the change. The main difference between MDRE and the traditional way is, it comes from internal sources (dev., sales team, bug reports etc.,) and external sources (users, customers, competitors etc.,). 
This paper presents a method that utilizes strategies for early requirements triage. Performing a early triage (discarding inappropriate) can help while doing a large scale requirements. Author proposed two methods both based on a few questions: “where do we want to go”, finding out the right balance between the long term goals and short term objectives. “how will we get there”, Product strategy. “what to do”, rules of road. “why would we be successful”, to produce a competitive product strategy. “when will we get there”, roadmap. 
Part one triage: Early requirement triage, step 1 is to specify the questions, “where we want to go”, “how will we get there”, “what to do”. Step 2 is assigning weights to the answers of the questions “where to go”, “How to get there”, “where to do”. Step 3 is comparing the requirements, as of give points out of 100 for each the answers of requirements.
Part two Requirements selection for each release, Consists of 2 steps, Step 1 is to specify product-technology roadmap, gives an overview of the relationship between the product releases and successive technologies. Step 2 is Estimating the resources, using models such as COCOMO. 
Part three Strategy Rationale, documentation of the reasoning to the decisions that are answered previously in strategic questions. 
Industrial validation of MERTS is done and has been found that the method would offer decision support and structure, clarify goals, objectives and enable requirements triage. The method is found to have some drawbacks, it consumes a lot of time at the start of the project and it is a resource intense process to gather as it has the process of consulting different stake holders for the sake of business goals and formalizing them to a common set. 

Quality Requirements in Industrial Practice- An Extended Interview Study at Eleven Companies
	When the functional requirements are only considered in a developing a product it leads to dissatisfaction and failure. So while developing a product, Quality Requirements should be focused. The authors identified two types of the companies called business to business companies(B2B) and Business to customer(B2C).  
The main goals of the article is to  investigate the most important quality requirement, the interdependencies between the quality requirements in the companies and how the cost estimation is performed and how accurate is it on the quality requirements. 
Authors conducted interviews in 11 companies based on the questions framed and has been identified,
the most important quality requirement for B2C is usability and B2B is safety. 
The most common interdependency types are found as REQUIRES to B2C and CVALUE to B2B. Finding dependencies is identified to be a complex task and with large scale in place it is further more difficult, but they have impact on the planning, design and quality. 
There isn’t any distinction between the quality requirements and functional requirements during the cost estimation.
The quality requirement that are dismissed are not reassessed, authors have depicted that during the dismissal of quality requirements there is a clear gap between the project leader and project manager. Quality is requirements are dismissed for the reasons such as low priority than functional requirements and cost estimation.
  
