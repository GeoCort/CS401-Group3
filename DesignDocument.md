
![craftify logo](https://github.com/ErmakovGeorge/CS401-Group3/assets/98370485/652b1961-b0f6-48b3-ae1d-767e96417c27)

Design Document for: Craftify
Authors: George Cortes, George Ermakov, Juan Sanchez, Victor Ly
Date: February 20th, 2024
Status: In Progress
 
Concept Summary 
Craftify is an innovative mobile application designed to empower users with a diverse array of Do-It-Yourself (DIY) skills and knowledge across an extensive range of categories. From basic household repairs to culinary adventures, outdoor pursuits, and artistic endeavors, Craftify serves as a comprehensive educational platform catering to beginners and enthusiasts alike.
 
With categories spanning Home Décor & Design, Cooking & Baking, Gardening & Landscaping, Electronics & Gadgets, Fashion & Accessories, Health & Fitness, Pet Care & Training, Art & Crafts, Travel & Adventure, and Technology & Innovation, Craftify offers something for everyone eager to delve into the world of DIY.
 
Whether you're sprucing up your living space, whipping up delicious homemade meals, cultivating a vibrant garden oasis, or embarking on thrilling outdoor escapades, Craftify provides the tools, tutorials, and inspiration to help you unleash your creativity, learn new skills, and accomplish your DIY dreams. Join us on this journey towards self-sufficiency and exploration with Craftify - Your Ultimate DIY Companion!
 

Audience/Custome:
 
Craftify's target audience spans a wide demographic spectrum, appealing to individuals of various ages, genders, locations, occupations, income levels, and interests. From young adults starting their journey in DIY home maintenance to retirees seeking fulfilling hobbies, Craftify accommodates diverse lifestyles and skill levels.
 
Whether you're a busy professional looking to save on home repairs, a college student seeking apartment living solutions, or a retiree eager to embark on long-awaited projects, Craftify provides accessible resources and inspiration. With categories ranging from home improvement and cooking to gardening, art, and technology, Craftify caters to the interests and needs of a broad audience, fostering creativity, self-sufficiency, and community engagement in the exciting world of DIY.
 
Background:
 
Craftify is a mobile app born from the growing interest in DIY activities. It aims to be a one-stop educational hub for DIY enthusiasts of all skill levels. Inspired by the rise of the maker movement and the popularity of online DIY content, Craftify offers tutorials, guides, and resources across a wide range of categories, including home improvement, cooking, gardening, electronics, fashion, health, pet care, art, travel, and technology.
 
Craftify's mission is to empower users to learn practical skills, foster creativity, and cultivate self-sufficiency through accessible and engaging content. Whether users are beginners or seasoned DIYers, Craftify provides step-by-step guides, interactive features, and community collaboration opportunities to support their journey in the DIY space.
 
Application Cost and Projected success:
 
Cost Considerations:
- Development Expenses
- Marketing and Promotion
- Operational Costs
- Legal and Regulatory Compliance
- Contingency Fund

Projected Success Factors:
- Market Demand
- Competitive Landscape
- Unique Value Proposition
- User Acquisition Strategy
- Monetization Strategy
- User Feedback and Iteration
- Scalability and Growth Potential

These factors collectively contribute to assessing the cost and projected success of the Craftify application in the DIY education app market. 

Interface Mockups (for projects that have a presentation layer/ GUI)
 ![GUI](https://github.com/ErmakovGeorge/CS401-Group3/assets/98370485/b0909c84-5d30-4694-9d6e-650f00d001db)

       

Design - Use Case Diagram(s)  
            See attachments.
 











Design - Detailed Design

System Diagram (Alpha Phase)
![Screenshot_2024-02-19_194354](https://github.com/ErmakovGeorge/CS401-Group3/assets/98370485/662728a3-b84c-4aa6-b25d-0a692634a5ea)




 
System Diagram:(Beta Phase - SOP) 
              +----------------------+
              |     Craftify App     |
              +----------------------+
                |               |
         +------|-------+   +---|-------+
         | Authentication |   |    Content     |
         +----------------+   +----------------+
                |               |
  +------------+  |  +-------------+   +----------------+
  | User Profile |  |  |    Search   |   |   Community   |
  +------------+  |  +-------------+   +----------------+
                |               |
         +------|-------+   +---|-------+
         | Analytics     |   |    Notifications |
         +----------------+   +----------------+ 
1. Authentication Module: (nice to have)
Responsible for user authentication and authorization.
Allows users to sign up, log in, and manage their accounts securely.
Handles password encryption, session management, and user roles.
 
2. User Profile Module: 
Manages user profiles and preferences.
Allows users to customize their profiles, set preferences, and manage account settings.
Stores user information such as name, email, profile picture, and saved preferences.
 
3. Content Module:  
Central module responsible for managing and delivering content.
Includes sub-modules for different content categories such as tutorials, guides, videos, and articles.
Handles content creation, storage, retrieval, and presentation to users.
 
4. Search Module:  
Enables users to search for specific content within the app.
Implements search functionality using keywords, tags, and filters.
Retrieves relevant content based on user queries and preferences.
 
5. Community Module:  
Facilitates community engagement and interaction among users.
Includes features such as forums, discussion boards, comments, and social sharing.
Allows users to connect, share tips, ask questions, and collaborate on DIY projects.
 
Each module interacts with the Craftify app interface to provide a seamless user experience. The Authentication module ensures secure access to the app, while the User Profile module personalizes the experience for each user. The Content module serves as the backbone of the app, delivering valuable resources, and the Search module enhances discoverability. Finally, the Community module fosters a sense of belonging and collaboration among users.
 





Related Work
Youtube, Instructables, Pinterest, WikiHow, Houzz, Skillshare.
 
Frameworks/Services/Cloud/Backends
1. Frontend Framework:
   - React Native: Craftify can utilize React Native for cross-platform mobile app development, ensuring a consistent user experience on both iOS and Android devices.
 
2. Backend Framework:
   - Node.js with Express: Craftify can leverage Node.js with Express to develop a scalable backend server for handling authentication, API requests, and database operations.
 
3. Database Service:
   - Firebase Firestore: With real-time data synchronization and scalability, Firebase Firestore is suitable for storing Craftify's user data, content, and user-generated materials.
 
4. Cloud Service:
   - Google Cloud Platform (GCP): GCP provides various cloud services such as compute, storage, and networking, enabling Craftify to deploy and scale its backend infrastructure as required.
 
5. Content Delivery Network (CDN):
   - Cloudflare: Cloudflare's global CDN and DDoS protection service can ensure fast and reliable content delivery to Craftify users worldwide, enhancing security and performance.
 
6. Analytics and Tracking Service:
   - Google Analytics: Craftify can utilize Google Analytics for valuable insights into user behavior, app usage, and engagement metrics, facilitating data-driven decision-making.
 
By selecting these frameworks and services, Craftify can efficiently build, deploy, and maintain a scalable DIY platform while ensuring a seamless user experience and actionable insights into user engagement.

 
Testing 
1. Unit Testing: Verify individual components using frameworks like Jest for JavaScript.
2. Integration Testing: Test interactions between components with tools like Supertest for Node.js.
3. End-to-End (E2E) Testing: Validate overall app flow using Cypress or Selenium WebDriver.
4. User Acceptance Testing (UAT): Gather feedback from real users through beta testing and feedback channels.
5. Performance Testing: Measure responsiveness and scalability with tools like Apache JMeter.
6. Security Testing: Identify vulnerabilities using OWASP ZAP or Burp Suite.
 





Schedule 
This schedule will also be posted on ZenBoard


Week
Tasks
Weeks 1-2
Project Planning and Setup
<img width="1677" alt="Screenshot 2024-02-19 at 4 00 46 PM" src="https://github.com/ErmakovGeorge/CS401-Group3/assets/98370485/ab1941e0-c87b-4a04-bc91-9b6b9ca82054">


- Define project scope, goals, and requirements


- Set up development environment and tools


- Assign roles and responsibilities within the team
Weeks 3-4
UI/UX Design


- User research and persona creation


- Design wireframes and prototypes


- Gather feedback and iterate on designs
Weeks 5-6
Backend Development - Authentication and Database Setup


- Set up Firebase Authentication for user management


- Implement database schema and setup
Weeks 7-8
Backend Development - API Development


- Design and implement RESTful APIs


- Backend logic for handling API requests
Weeks 9-10
Frontend Development - App Structure


- Set up project structure and navigation


- Implement basic UI components and screens
Weeks 11-12
Frontend Development - Content and Search


- Integrate with backend APIs for content


- Implement search functionality
Weeks 13-14
Frontend Development - Community Features


- Implement community features


- Enable user interaction and collaboration
Weeks 15-16
Testing and Quality Assurance


- Conduct unit tests, integration tests, and E2E tests


- User acceptance testing (UAT)
Weeks 17-18
Final Polish and Deployment


- Bug fixes and optimizations


- Prepare for app store submission and deployment


 
Dependencies 
1. Data Management:
   - Firebase Firestore or MongoDB Atlas for storing user data.
   - Firebase Authentication for user authentication.
 
2. Backend Infrastructure:
   - Node.js with Express for building the backend server.
   - Google Cloud Platform (GCP) or AWS for hosting the server.
 
3. Frontend Development:
   - React Native or Flutter for cross-platform mobile app development.
 
4. Content Delivery:
   - Cloudflare for fast and reliable content delivery.
 
5. Analytics and Tracking:
   - Google Analytics for user behavior insights.
 
 
 



