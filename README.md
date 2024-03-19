<!-- Your Name's Portfolio -->

<h1 align="center">Martin Meyer</h1>

<p align="center">
    A collection of my projects and skills
</p>

## About Me

I've spent nearly a decade building large and complex classified web projects. My experience goes beyond just coding and fixing bugs. As the senior leader for three projects, I've honed my skills in understanding business needs and clarifying expectations. This approach allows me to offer solutions that are truly effective, not just quick fixes.

I collaborate closely with designers and mobile developers, ensuring we deliver complete products from the drawing board to the final launch.

I've contributed to several key projects, such as:

AutoMart
Truck and Trailer
AgriMag
My background is in web development, with a strong history in the marketing and advertising sectors. I'm proficient in SQL, JavaScript, Microsoft Azure, ASP.NET, and C#, backed by a Bachelor's Degree in Computing with a focus on Software Engineering from Belgium Campus.

Outside of work, I enjoy staying active, exploring nature, and expanding my knowledge. Writing about new technologies and demystifying them for others is a passion of mine, time permitting. I also dedicate time to personal projects that test new technologies. This helps me stay informed and anticipate potential challenges in my professional projects.

I'm particularly fond of the Microsoft ecosystem, utilizing Azure for hosting web projects, storage blobs, and functions, which simplifies deployment. My preferred development setup combines .NET Core with JavaScript frameworks for an efficient front-end development process.

### **Work Experience**

**September [2015] - Present Senior Developer & Team Lead at [Dot Slash]**

For almost the past 9 years, I have worked on mostly 3 big classifieds projects at Dot Slash. I have worked on a variety of projects over this time however these 3 became my main responsibility.

**Agrimag Project**: A web project built on Azure App Services and .NET Core 6.

**Truck and Trailer Project**: This extensive project is divided into several key components:

- **Account and Advert Placement**: Building on Azure App Services with .NET Core 6, I integrate Vue.js for dynamic data display and interactive tables.
- **Indexer**: I oversee an API service using Azure and .NET 6 that streamlines the indexing of advertisements to Elastic Search.
- **ReIndexer Function**: I manage an Azure Functions app to reindex new adverts every two hours, ensuring constant up-to-date data availability.

**Automart - Legacy System**: Maintenance and innovation go hand in hand as I work with .NET 3.5, Jenkins, and IIS VM server deployment:

- **Legacy API/Admin/Account**: Deployment through Jenkins and maintenance on IIS VM servers.
- **Legacy Task**: Console applications (.exe) are scheduled via Windows Task Scheduler on a VM, automating database and Elastic Search tasks.

**Daily Responsibilities**:

1. Building new features - Keyword search functionality, new call functionality.
2. Debugging and solving issues and launching fixes. These are bugs like adverts not displaying correctly, some functionality not working as expected, basically any bug reports on the sites get divided up into the team to be solved. The most complex and critical tasks go to me and then passed on from there.
3. Launching and maintaining the sites. This includes reviewing and merging PRs, launching all sites to pre-live environments and then swapping to live environments once all checks have been done.
4. As Team Lead, I also assist with an effective flow of the project, this means that I make sure that tasks are assigned to my team and everyone has work. This also means that I make sure everyone understands the client requirements of the tasks so that they work correctly and have a clear expectation of what to deliver. I also check into the statuses of tasks and make sure the testers and project managers have noted the changes and either test or get client feedback, this is to make sure tasks keep moving forward and there is no block to get the task live.

**Strategic Roles and Value:**

1. Architecting and planning project infrastructure: This happens about once a year when we are refactoring/rebuilding the existing legacy systems or starting new ones. Like when we rebuild Agrimag and Truck and Trailer from .NET 3.5 to .NET Core 6. I will then start planning the architecture of the project, usually in a simple Clean Code Architecture where I would set up a Solution that will consist of 5 projects:
    1. Web Layer: This is the public-facing site and will have all the views and controllers needed for user interaction and displaying data. Also contains the project setup and settings like interface registration, Middleware redirects, Microsoft Identity integration for accounts login, and global setting registration like connection strings.
    2. Core Layer: This will have all our Interfaces and core models that all the other projects refer to as a central point so that there is no circular or tightly coupled dependencies with each other.
    3. Application Layer: This is where all the implementations live of all interfaces in core.
    4. Infrastructure Layer: This project is responsible for outside connections like SQL Database and Elastic Search.
    5. Test Layer: This will be a project for running Xunit unit tests on the critical functions.
2. Managing client expectations: When big planning is needed it is important to manage client expectations by designing and planning realistic deadlines and estimations of tasks.
3. Help with team development and recruitment: As team lead, there are other expected responsibilities above being a Senior developer on the projects.
    1. Planning and designing systems that can evaluate an employee's current level and skills as well as the expected level.
    2. Develop a job spec for intermediate to senior development job applications as well as then interview those candidates.
    3. Help architect a company culture that can exist in a fully remote company.
    
    **Technologies and Methodologies**:
    
    - **Azure Services**
    - **.NET Core 6 & .NET 3.5**
    - **Vue.js**
    - **Elastic Search**
    - **Jenkins & IIS VM Deployment & Azure App Service deployments**
    - **Xunit Testing**.
    - **SQL**.

## Contact Me
Email: jackolboy300@gmail.com

