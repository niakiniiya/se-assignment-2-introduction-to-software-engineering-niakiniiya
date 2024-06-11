[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15256029&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
    Software engineering is a systematic, disciplined, and quantifiable approach to the development, operation, and maintenance of software.

What is software engineering, and how does it differ from traditional programming
    Software engineering is a systematic, disciplined, and quantifiable approach to the development, operation, and maintenance of software while traditional programming refers to the conventional approach of writing code to create specific instructions for a computer to follow.

Software Development Life Cycle (SDLC):
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase; Agile vs. Waterfall Models:
    WATERFALL MODEL 

        Feasibility Study
        The main aim of feasibility study is to determine whether it would be financially and 
        technically feasible to develop the product. 
        
        Requirements Analysis and Specification
            The aim of the requirements analysis and specification phase is to understand the exact 
        requirements of the customer and to document them properly. This phase consists of two 
        distinct activities, namely requirements gathering and analysis and requirements specification.

        System Design
            The design phase is to transform the requirements specified from the SRS document into a 
        design that is suitable for implementation in some programming language. 

        Coding and Unit Testing
            The coding and unit testing phase (sometimes referred to implementation phase because the 
        design is implemented) of software development involves translating the software design into 
        source code using a programming language. 

        Integration and System Testing
            During the integration and system testing phase, the modules are integrated based on the 
        system design. The different modules rarely integrated all at one instead integration is 
        normally carried out incrementally over a number of steps.

        Maintenance
            Ensure the software remains functional, relevant, and high-performing after deployment. It includes:
                Corrective Maintenance: Correcting errors that were not discovered during the product development phase. 

                Perfective maintenance: Improving the implementation of the system, and enhancing the
                functionalities of the system according to the customer’s requirements. 
        
                Adaptive maintenance : Migrating the software to work in a new environment. For example,
                moving the software to work with a new operating system. 

    AGILE MODEL
    Concept
        The product owner will determine the scope of their project. If there are numerous projects, they will prioritize the most important ones. The product owner will discuss key requirements with a client and prepare documentation to outline them, including what features will be supported and the proposed end results. 

    Inception
        The product owner will pick the best people for the project while also providing them with the necessary tools and resources. 
    
    Iteration
        It is also referred to as construction. It tends to be the longest phase as the bulk of the work is carried out here. The developers will work with UX designers to combine all product  requirements and customer feedback, turning the design into code. 
     
     Release
        The quality assurance team needs to perform some tests to ensure the software is fully functional. The agile team members will test the system to ensure the code is clean — if potential bugs or defects are detected, the developers will address them swiftly. 
    
    Maintenance
        The software will now be fully deployed and made available to customers. The software development team will provide ongoing support to keep the system running smoothly and resolve any new bugs.

    Retirement
        Decommission the software when it is no longer needed or is replaced by a new system.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
    
   Waterfall model is suitable for projects with well-defined requirements and where changes are unlikely. It follows a sequential approach with distinct phases and extensive documentation while agile model is suitable for projects where requirements may evolve. It follows an iterative approach, emphasizing flexibility, collaboration, and customer feedback.

Requirements Engineering:
What is requirements engineering? Describe the process and its importance in the software development lifecycle.
    
    Requirements engineering is the process of defining, documenting, and maintaining the requirements for a software system. It is a critical part of the software development lifecycle (SDLC) as it lays the foundation for what the system should do and how it should perform.

    Process:
    Requirements Elicitation: Gathering requirements from stakeholders through interviews, surveys, observation, and document analysis.

    Requirements Analysis: Analyzing the gathered requirements for clarity, completeness, consistency, and feasibility.

    Requirements Specification: Documenting the requirements in a clear, precise, and unambiguous manner, typically in a Software Requirements Specification (SRS) document.

    Requirements Validation: Ensuring the documented requirements accurately reflect stakeholder needs and are feasible to implement.

    Requirements Management: Managing changes to the requirements as the project progresses and maintaining traceability of requirements.

    Importance:
    Design and development: Provides a clear understanding of what needs to be built.

    Improves quality: Helps in identifying potential issues early, reducing the risk of costly changes later.

    Facilitates communication: Ensures all stakeholders have a shared understanding of the requirements.

    User satisfaction: By capturing and validating user needs, it ensures the final product meets user expectations.

Software Design Principles:
Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
    
    Modularity in software design refers to dividing a software system into separate, self-contained components or modules, each responsible for a specific part of the functionality.

        Improved maintainability: Easier to understand, debug, and modify individual modules without affecting the entire system.

        Scalability: New features can be added by developing new modules without altering existing ones.

        Reusability: Modules can be reused across different projects, reducing development time and cost.

        Parallel development: Different teams can work on different modules simultaneously, speeding up the development process.

Testing in Software Engineering:
Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
    Unit testing: It is the process of testing individual components in isolation. It is a defect       testing process.

    Integration Testing:Tests the interaction between integrated components or modules, it ensures combined parts work together as intended.

    System testing: During development involves integrating components to create a version of the 
    system and then testing the integrated system. The focus in system testing is testing the 
    interactions between components.

    Acceptance Testing: Tests the system's readiness for deployment which is usually performed by end-users or clients to validate the software against their needs.

Version Control Systems:
What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

    Version control systems are tools that help manage changes to source code. They enable multiple developers to work on a project simultaneously without overwriting each other’s work.

    Importance:
    Collaboration: Allows multiple developers to work on the same project concurrently.

    Tracking changes: Maintains a history of changes, enabling developers to revert to previous versions if needed.

    Backup: Provides a backup of the source code.

    Branching and Merging: Supports creating branches for new features or bug fixes, which can be merged back into the main codebase.

    Examples:
    Git: Distributed VCS with features like branching, merging, and distributed repositories.

    Subversion (SVN): Centralized VCS with strong support for directory versioning and atomic commits.

    Mercurial: Distributed VCS known for its ease of use and performance.

Software Project Management:
Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
    A software project manager is responsible for planning, executing, and closing software projects. Ensuring that the project meets its goals within the constraints of time, budget, and quality.

        Key Responsibilities:
            Planning: Defining the project scope, objectives, and deliverables. 

            Resource Management: Allocating resources, including team members, budget, and tools.

            Risk Management: Identifying potential risks and developing mitigation strategies.

            Communication: Facilitating communication among stakeholders, team members, and clients.

            Monitoring and Control: Tracking project progress, managing changes, and ensuring the project stays on schedule and within budget.

        Challenges:
            Scope Creep: Managing changes to the project scope.

            Constraints: Balancing limited resources and time.

            Team Coordination: Ensuring effective communication and collaboration among team members.

            Stakeholder Management: Meeting the expectations and requirements of various stakeholders

Software Maintenance:
Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

    Software maintenance involves modifying and updating software after its initial deployment to correct faults, improve performance, or adapt to a changed environment.

    Types of Maintenance:
        Corrective Maintenance: Fixing bugs and errors discovered after the software is deployed.

        Adaptive Maintenance: Updating the software to work in a new or changed environment (e.g., new operating system, hardware changes).

        Perfective Maintenance: Enhancing and improving existing functionalities based on user feedback and new requirements.

        Preventive Maintenance: Making changes to prevent future problems and improve maintainability.

Ethical Considerations in Software Engineering:
What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
    Ethical Issues:
        Privacy: Ensuring user data is protected and used ethically.

        Security: Developing secure software to protect against malicious attacks.

        Intellectual Property: Respecting copyright, patents, and other intellectual property rights.

        User Impact: Considering the social and environmental impact of software on users and society.
    
    Ensuring Ethical Standards:
        Adherence to Codes of Conduct: Following professional codes of ethics from organizations like ACM and IEEE.

        Transparency: Being transparent about data usage, software limitations, and potential impacts.

        Responsibility: Taking responsibility for the software’s impact on users and society.
        
REFERENCES
https://www.wrike.com/
https://www.geeksforgeeks.org/

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].