# Interview Preparation Topics





<details>
<summary><strong>1.System Design</strong></summary>

&nbsp;
- **High-Level Design** 
     1. Architectural Patterns
        - Monolithic vs. Microservices Architecture
        - Event-Driven Architecture
        - Service-Oriented Architecture (SOA)
        - Serverless Architecture
        - Layered/Tiered Architecture

     2. System Components
        - API Gateways
        - Load Balancers
        - Application Servers
        - Databases (SQL/NoSQL)
        - Caching Layers (Redis, Memcached)
        - Message Queues (Kafka, RabbitMQ)
        - Storage Solutions (Object storage, Block storage)

    3. Scalability
        - Vertical vs. Horizontal Scaling
        - Partitioning/Sharding
        - Load Distribution Techniques

    4. System Communication
        - REST vs. gRPC
        - Synchronous vs. Asynchronous Communication
        - Pub/Sub Mechanisms
    
    5. Reliability & Fault Tolerance
        - Redundancy
        - Replication
        - Circuit Breaker Patterns
        - Failover Strategies
    
    6. Performance Optimization
        - Caching Strategies
        - Database Indexing
        - Query Optimization
        - Content Delivery Networks (CDNs)

    7. Security Considerations
        - Authentication and Authorization (OAuth, JWT)
        - Encryption (TLS, AES)
        - Threat Modeling
        - Secure API Design

    8. Deployment Strategies
        - CI/CD Pipelines
        - Blue-Green Deployments
        - Canary Releases
        - Rollbacks
    
    9. Monitoring and Logging
        - Observability (Metrics, Logs, Traces)
        - APM Tools (e.g., New Relic, Dynatrace)

    10. Use Case-Specific Considerations
        - E-commerce Systems
        - Social Media Platforms
        - Streaming Platforms
        - Real-Time Systems (e.g., gaming, stock trading)

   
- **Low-Level Design**

    1. Object-Oriented Design (OOD)
        - SOLID Principles
        - Design Patterns:
            - Creational: Singleton, Factory
            - Structural: Adapter, Composite
            - Behavioral: Observer, Strategy
        - UML Diagrams (Class, Sequence, Activity)
    
    2. Data Structures
        - Arrays, Linked Lists, Stacks, Queues
        - Trees (Binary, AVL, B-Trees)
        - Graphs (DFS, BFS)
        - Hash Maps and Hash Tables
        - Tries

    3. Algorithms
        - Sorting and Searching Algorithms
        - Dynamic Programming
        - Greedy Algorithms
        - Divide and Conquer
        - Backtracking
        - Graph Algorithms (Dijkstra, A*)

    4. Database Design
        - Schema Design (Normalization, De-normalization)
        - Indexing
        - Transactions and ACID Properties
        - Query Optimization
        - ER Diagrams

    5. Concurrency and Multithreading
        - Thread Management
        - Locks and Semaphores
        - Deadlock Prevention
        - Concurrent Data Structures
        - Asynchronous Programming

    6. Code Design
        - Modular Design
        - Dependency Injection
        - Interface Design
        - Error Handling
        - Logging and Debugging

    7. APIs
        - API Specification (OpenAPI/Swagger)
        - Rate Limiting and Throttling
        - Error Codes and Handling
        - Versioning

     8. Testing
        - Unit Testing
        - Integration Testing
        - Mocking/Stubbing
        - Test-Driven Development (TDD)

    9. Security
        - Input Validation
        - SQL Injection Prevention
        - Secure Coding Practices
        - Access Control

    10. Performance Optimization
        - Profiling
        - Refactoring
        - Memory Management
        - Efficient Algorithms


</details>

---

&nbsp;























<details>
<summary><strong>2. Data Structures & Algorithms</strong></summary>

- [My DSA Repository](https://github.com/saiteja8848/DSA)

</details>

---


&nbsp;


















<details>
<summary><strong>3. Development</strong></summary>







<details>
<summary><strong>a) Understanding</strong></summary>

- Computer Fundamentals  
- Operating System - commands
- Networking  
- Internet and Web  
- Programming Languages and Paradigms  
- Build Automation tools
  - Gradle  
  - Maven  
  - Ant  
</details>


<details>
<summary><strong>b) Frontend</strong></summary>

- Markdown  
- Cascading Style Sheets (CSS)  
- Scripting Language (JavaScript)  
- Frameworks:  
  - **Angular Concepts**  
    - 1. Introduction to Angular
        - What is Angular?
        - Why Angular?
        - Angular CLI: Installing and creating a new project using Angular CLI.

    - 2. Basic Setup & Architecture
        - Angular Modules (NgModules): Understanding the purpose of NgModules and how they are used to organize the app.
        - Component Basics: Learn how to create components, templates, and styles.
        - Component Metadata: Use of @Component decorator, understanding component lifecycle.
    
    - 3. Templates & Directives
        - Data Binding: Interpolation, property binding, event binding, and two-way binding.
        - Directives: Structural directives (ngIf, ngFor), and attribute directives (ngClass, ngStyle).
        
    - 4. Services & Dependency Injection
        - What are Services?
        - Injecting Services into Components: Using the constructor to inject services.
        - Dependency Injection (DI): Angular’s DI mechanism for managing dependencies.
       
    - 5. Routing
        - Setting up Angular Routing: How to configure routes using RouterModule.
        - Route Parameters: Dynamic route parameters and query parameters.
        - Navigation and Guards: How to programmatically navigate and use route guards for protecting routes.

    - 6. Forms
       - Template-driven Forms: Working with ngModel, form validation, and form controls.
       - Reactive Forms: Creating form groups, form controls, and handling validation in reactive forms.


    - 7. Http Client & Observables
       - Making HTTP Requests: Using Angular's HttpClient to make API calls.
       - Observables: Understanding the role of RxJS Observables in Angular, handling async data.
       - Http Interceptors: Modifying requests and responses globally.


    - 8. Pipes
        - Built-in Pipes: Understanding pipes like DatePipe, CurrencyPipe, JsonPipe, etc.
        - Custom Pipes: Creating your own pipes for transforming data.

    - 9. State Management
        - Service-based State Management: Using services to manage state between components.
        - NgRx (optional): Advanced state management using the Redux pattern with NgRx.


    - 10. Lifecycle Hooks
        - Component Lifecycle: Understanding lifecycle methods like ngOnInit, ngOnChanges, ngOnDestroy, etc.
        - Change Detection: Learn how Angular detects changes in components and updates the UI.

    - 11. Unit Testing
        - Testing Components: Writing unit tests for components using Jasmine and Karma.
        - Testing Services: Mocking dependencies and writing tests for services.


    - 12. Advanced Topics
       - Lazy Loading: Load feature modules on demand to optimize application performance.
       - Custom Directives: Creating reusable custom directives.
       - Angular Universal: Server-side rendering (SSR) for Angular apps.
       - Advanced RxJS: Learn higher-order observables, operators like switchMap, mergeMap, etc.
       - Web Workers: Running heavy tasks in a separate thread.
       - Custom Schematics: Create custom CLI commands for Angular projects.

    - 13. Optimization and Performace
       - Ahead-of-Time Compilation (AOT): Benefits and how Angular compiles templates before the browser.
       - Tree Shaking: Removing unused code.
       - Change Detection Strategies: OnPush strategy for optimization.
       - Lazy Loading Routes & Modules: Loading modules only when required.

</details>



<details>
<summary><strong>c) Backend</strong></summary>

A) Programming Languages  
  - Basics
    - Java Syntax and Structure
    - Variables and enum
    - Control flow statements
    - Functions and Methods
    - Exception Handling
    - Input and output handling
    - File Handling
 - Object oriented programming
 - Java Memory management
 - Mutlithreading and event-loop
 - Datasturctures - collections
 - Reflections,Annotations
 - Functional programming concepts


B) Frameworks  
  - A) Modules
      - Security
      - Database connectivity
      - Logging
  - B) Reactive && Non-Reactive  

</details>




</details>

---






&nbsp;



<details>
<summary><strong>4.About Software Testing</strong></summary>

- **Types of Software Testing** 
    - Software Testing can be broadly categorized into two types:
        - Manual Testing : Testing performed manually by humans without using automated tools.Suitable for exploratory, usability, or ad-hoc testing.
        - Automated Testing : Testing performed using automation tools and scripts.Efficient for repetitive tasks and regression testing.

- **Levels of Software Testing** 
    - These levels define the scope and purpose of testing at different stages of development:
        - Unit Testing : 
            - Focuses on testing individual components or functions.
            - Example: Testing a single method in a class
        - Integration Testing : 
            - Tests interactions between multiple components or systems.
            - Example: Verifying data flow between a frontend and a backend service.
        - System Testing :
            - Tests the complete application as a whole.
            - Example: Verifying all features of an e-commerce website.
        - Acceptance Testing :
            - Ensures the software meets business requirements and is ready for release.
            - Example: User Acceptance Testing (UAT).

- **Types of Testing Based on Purpose** 
    - Functional Testing:
        - Verifies that software functions as intended.
        - Example: Checking if a login form accepts valid credentials.    
    - Non-Functional Testing:
        - Focuses on performance, usability, and reliability.
        - Examples :
            - Performance Testing: Checks speed and stability under load.
            - Security Testing: Identifies vulnerabilities in the application.
            - Usability Testing: Ensures the software is user-friendly.
    - Maintenance Testing:
        - Conducted after software deployment to ensure stability during updates or changes.
        - Example: Regression Testing.
- **Ways to Perform Software Testing** 
    - Black-Box Testing
        - Focuses on input-output without knowing internal code.
        - Example: Testing a calculator app by entering numbers.
    - White-Box Testing
        - Involves testing internal structures or code logic.
        - Example: Testing loops and conditions in code.
    - Gray-Box Testing
        - Combines black-box and white-box approaches, with partial knowledge of the system.
        - Example: Testing APIs with some knowledge of backend structure.

- **Methods of Software Testing** 
    - Static Testing
        - Testing without executing the code.
        - Example: Code reviews, walkthroughs, and static analysis.
    - Dynamic Testing
        - Testing by executing the software.  
        - Example: Running the application and observing outputs.

    - ## Comparison of TDD and BDD
        | **Aspect**          | **TDD**                                   | **BDD**                                   |
        |----------------------|-------------------------------------------|-------------------------------------------|
        | **Focus**           | Code functionality                        | User behavior and business requirements   |
        | **Syntax**          | Programming language (unit tests)         | Natural language (Gherkin syntax)         |
        | **Collaboration**   | Primarily developer-centric               | Involves stakeholders, QA, and developers |
        | **Tools**           | JUnit, NUnit, pytest                      | Cucumber, SpecFlow, Behave                |
        | **Test Granularity**| Unit tests                                | Behavior (end-to-end or integration tests) |


- **Techniques Used in Testing** 
    - Boundary Value Analysis (BVA)
        - Tests boundaries of input values.
        - Example: Testing for 0, 1, and 2 if the range is 0-100.

    - Equivalence Partitioning
        - Divides input data into valid and invalid partitions.
        - Example: Grouping age values into valid (18–60) and invalid (<18, >60).

    - Decision Table Testing
        - Tests combinations of inputs and their outcomes.
        - Example: Verifying how a calculator handles various operator combinations.

    - Exploratory Testing
        - Ad-hoc testing without predefined test cases.
        - Example: Randomly clicking around a UI to find hidden bugs.

    - Regression Testing
        - Ensures new changes don’t break existing functionality.
        - Example: Retesting a shopping cart after adding a new discount feature.

    - Smoke Testing
        - Basic testing to check critical functionalities.
        - Example: Ensuring the login page loads.

    - Sanity Testing
        - Focused testing to verify specific functionality after minor updates.
        - Example: Testing only the search bar after its update.

</details>

---




















&nbsp;


<details>
<summary><strong>5. Building, Deploying, Monitoring, and Rollback Plan</strong></summary>

 - **Topics** 
    - Git
    - Docker  
    - Kubernetes  
    - Linux Commands
    - SLO, SLI && SLA  

</details>

---













&nbsp;




<details>
<summary><strong>6.Learning</strong></summary>

## **Extraction,Transformation and Loading (ETL)**



&nbsp;
## **Artificial Intelligence**
- Systems that simulate human intelligence.
- Encompasses a broad range of techniques and applications.
- Examples:
  - Smart assistants (e.g., Siri, Alexa)
  - Autonomous systems
  - AI-driven decision-making systems

### **Subfields of Artificial Intelligence**
1. **Machine Learning (ML)**
   - Systems that learn from data (structured and unstructured).
   - Core techniques:
     - **Supervised Learning**: Learn from labeled data (e.g., regression, classification).
     - **Unsupervised Learning**: Find patterns in unlabeled data (e.g., clustering, dimensionality reduction).
     - **Reinforcement Learning**: Learn by interacting with an environment.
   - Foundations:
     - Inference and Statistical Modeling
     - Evaluation Metrics (e.g., Accuracy, F1-Score)

2. **Deep Learning (DL)**
   - Neural networks with multiple layers (hierarchical learning).
   - Specialized architectures:
     - **Convolutional Neural Networks (CNNs)**: For image-related tasks.
     - **Recurrent Neural Networks (RNNs)**: For sequence and time-series data.
     - **Transformers**: For text, vision, and multimodal tasks.
   - Applications:
     - Image recognition
     - Speech synthesis
     - Generative content creation

3. **Natural Language Processing (NLP)**
   - Systems that process and understand human language.
   - Core tasks:
     - Text classification (e.g., spam detection)
     - Sentiment analysis
     - Machine translation
     - Question answering
   - Advanced models:
     - BERT, GPT, and T5 for contextual understanding.
   - Applications:
     - Chatbots
     - Voice assistants
     - Summarization tools

4. **Generative AI**
   - AI systems that generate new content (e.g., text, images, music).
   - Core techniques:
     - **Variational Autoencoders (VAEs)**: Generate structured outputs.
     - **Generative Adversarial Networks (GANs)**: Create realistic media content.
     - **Diffusion Models**: Emerging for high-quality image and video generation.
   - Applications:
     - DALL·E: Text-to-image generation.
     - ChatGPT: Conversational AI.
     - Codex: AI for code generation.

5. **Retrieval-Augmented Generation (RAG)**
   - A combination of generative AI and retrieval systems.
   - Core concepts:
     - Use knowledge bases and search engines to augment model responses.
     - Example tools: LangChain, Pinecone, Weaviate.
   - Applications:
     - Knowledge-driven chatbots.
     - Intelligent document querying.
     - Personalized learning assistants.

---

## **Hierarchy of AI Topics**
### 1. Artificial Intelligence (Parent Domain)
   - High-level systems simulating human intelligence.

### 2. Machine Learning (Subfield)
   - Learning from structured and unstructured data.
   - Techniques: Supervised, Unsupervised, and Reinforcement Learning.

### 3. Deep Learning (Subset of ML)
   - Neural networks with hierarchical structures.
   - Specialized for complex tasks such as image and text processing.

### 4. Natural Language Processing (Subset of AI)
   - Focus on processing and understanding human language.
   - Advanced models include transformers like BERT and GPT.

### 5. Generative AI (Subset of AI)
   - Focus on creating new and original content.
   - Techniques: GANs, VAEs, Diffusion Models.

### 6. Retrieval-Augmented Generation (Emerging AI Subfield)
   - Augments generative models with external knowledge.
   - Tools: LangChain, vector databases.


</details>
