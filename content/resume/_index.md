+++
css = ["resume.css"]
date = "2022-11-09T02:50:52+02:00"
description = "Jim Le's online resume"
scripts = ["main-min.js"]
tags = ["resume", "cv", ".net developer", "full stack .net developer", "software developer", "front-end developer", "angular developer", "react developer"]
title = "Resume"

[params]
    # Main body sections

    # You may use markdown in summary, details and intro fields. But don't overdose, it's resume!:)

    # Summary section
    [params.summary]
        enable = true
        icon = "fa-user"
        title = "Career Summary"
        summary = "Full Stack Developer providing 10 years of software implementation and development expertise. With extensive successful years building awesome software in the domain of Banking, Logistics, Insurance, and Retail. Proficient in programming and problem-solving abilities to deal with projects using Microsoft technologies such as .NET Framework, .NET Core, C#, MSSQL, Azure and Entity Framework. Wide-ranging experience in utilization of Front-end technique through HTML5/CSS3, Angular, React, JQuery and TypeScript.<br><br>Open-minded and detail-oriented to create plans, delivery satisfied results to the team and meet the client’s expectations. Proactive in communication and investigation to solve the issues and maintain high-quality standards for the projects in a stable way. Flexible mindset effectively and positively adapt to changes and challenges. Friendly and have a good sense of humor to cross-culture practices in multi-cultural teams and international business protocol."

    # Skills section
    [params.skills]
        enable = true
        icon = "fa-rocket"
        title = "Skills & Proficiency"

        [[params.skills.list]]
        skill = "C#"
        level = "78%"

        [[params.skills.list]]
        skill = "Javascript"
        level = "80%"

        [[params.skills.list]]
        skill = "Angular"
        level = "79%"

        [[params.skills.list]]
        skill = "ReactJS"
        level = "75%"

        [[params.skills.list]]
        skill = "HTML5 & CSS"
        level = "80%"

        [[params.skills.list]]
        skill = ".NET Core"
        level = "78%"

        [[params.skills.list]]
        skill = "T-SQL & MSSQL"
        level = "70%"

        [[params.skills.list]]
        skill = "Azure Cloud Services"
        level = "65%"

    # Experiences section
    [params.experiences]
        enable = true
        icon = "fa-briefcase"
        title = "Experiences"

        [[params.jobs.list]]
        position = "Senior Consultant, Full-Stack Dev"
        dates = "2021 - Now"
        company = "Avanade Canada Inc., Vancouver BC, Canada"
        details = "• Has being sent to TD Bank as a software consultant helped EzWeb team to build the Payment Plan feature.<br>• Created components and initiated the unit testing for the team.<br>• Contributed new components and features to the internal UI framework of the team."

        [[params.jobs.list]]
        position = "Full Stack Software Developer"
        dates = "2019 - 2022"
        company = "TechEquipt Pty Ltd, Sydney, Australia"
        details = "• Implemented multiple React components and features around the Nextjs framework for a find-and-research-properties platform that belongs to a leading real estate firm in Canberra, AU.<br>• Wrote component documents and demonstrations in Storybook to help team members learn and use the new and existed components more easily.<br>• Found and fixed issues come from both backend and frontend to maintain and keep the product always robust."

        [[params.jobs.list]]
        position = "Senior Full-stack .NET Developer"
        dates = "2017 - 2018"
        company = "Groove Technology, Ho Chi Minh City, Vietnam"
        details = "• Played the key role in enterprise projects to build and delivery highly complex logistics platforms for the customer in Asia, Europe, and Australia.<br>• Successfully architected and initiated fundamental features of the project on time after the first five milestones. Professionally designed and developed features base on the requirements of the product owner.<br>• Assisted and collaborated with the QA Team to identify and resolve the problem of the project; expertly reviewed the code of junior developers.<br>• Mentored and presented about technical topics to the team; guided new team members through the knowledge and technique of the projects.<br>• Wrote T-SQL scripts to maintain and migration database using MS-SQL Server."

        [[params.jobs.list]]
        position = "Full-stack .NET Developer"
        dates = "2015 - 2017"
        company = "AS White Global, Ho Chi Minh City, Vietnam"
        details = "• Contributed to the development of a powerful insurance broking platform in Australia.<br>• Developed and maintained tools which helped to migrate the database from the old version and the other Insurance applications to the new application which was developed by my team.<br>• Communicated with QA team in Australia to devise an automation testing tool of the main project with Selenium.<br>• Implemented the process of writing and running unit test for my own codes as applying TDD. Enrolled as a member of a scrum team."

        [[params.jobs.list]]
        position = "Freelancing"
        dates = "2014-2015"
        company = "FF Team, Ho Chi Minh City, Vietnam"
        details = "Project POD | (Hybrid Mobile App with Xamarin) - Pay off Debt application help to manage the debts, this mobile application is implemented Snow Ball algorithm to help user manage their debt and paid it quickly. Developed by using Xamarin and C#.<br><br>Project Revsym product | (Single page web application) - Revenue recognition software. It is a complete Revenue sub-ledger and it also has an inbuilt Contract Management capability. Account for multiple revenue types, such as subscriptions, licenses, and professional services. Cooperated with the front-end team in US and contributed the code using KnockoutJS for this project.<br><br>Project vietnamcarrent.com | (WordPress page) – Applied and utilized WordPress page to make a webpage for my client (a car rental agency) efficiently run their business. It help users easy to find a car to rent from the owner."

        [[params.jobs.list]]
        position = ".NET Developer"
        dates = "2013 - 2014"
        company = "Harvey Nash VN (Nash Tech), Ho Chi Minh City, Vietnam"
        details = "• Played role developer in scrum team which is implemented Agile methodology.<br>• Performed a wide range of duties, including implementing new features, fixing bug and maintaining finished products.<br>• Contributed ideas and designs for product’s features via ad-hoc meeting,retrospective.<br>• Trained in such open source technologies as PHP, LimeJS, CentOS, and Varnish."

        [[params.jobs.list]]
        position = "Junior .NET Developer"
        dates = "2012 - 2013"
        company = "NEC VN, Ho Chi Minh City, Vietnam"
        details = "• Implemented features of the project follow the design from the experts, debugged to troubleshoot the issues from user feedbacks.<br>• Communicated with QA team in Japan, providing daily process reports for the underperforming features of the project.<br>• Learned and trained with Japanese discipline, meticulousness, carefulness and hard-working."

    # Projects section
    [params.projects]
        enable = true
        icon = "fa-archive"
        title = "Projects"
        intro = "I would like to detail some of the projects which I have been a part of."
        
        [[params.projects.list]]
        title = "LTL Project"
        url = "https://www.csglobal-ltl.com/ourplatform.php"
        tagline = "System auto-fills parts of the shipping order, e.g., addresses and other contact details, which are entered in advance in the address book.<br> - Solutions: Domain Driven Design, API implements RESTful API, ORM using EF Core (code first), MSSQL server and Azure Cloud Services.<br> - Back-end: .NET Core 2.x, C#.<br> - The front-end: Angular 2/4 and KendoUI components.<br> - Testing: automation test with Telerik Test Studio.<br> - Utility: Git with Bitbucket, issues tracking with Jira."

        [[params.projects.list]]
        title = "Insight Project"
        url = "https://www.steadfasttech.com.au/insight-1"
        tagline = "INSIGHT is everything you have ever wanted from a broking system. It's a cloud-based platform that gives you what you need to run your insurance broking business - anytime from anywhere.<br> - Solutions: Clean architecture, API implements REST style URL, ORM using EF 6 (database first), MSSQL server and Azure Cloud Services.<br> - Back-end: .NET Framework 5, C#.<br> - The front-end: EmberJS, CSS3 with flex-box layout.<br> - Testing: automation test with Selenium, unit test with NUnit.<br> - Utility: Git with GitHub, issues tracking with Gemini tracker."

        [[params.projects.list]]
        title = "Bodog ODC"
        url = "https://www.bodog.eu/"
        tagline = "Technologies include:<br> - Back-end: Drupal 7, PHP.<br> - The front-end: CSS with Responsive Design, Sencha Touch and LimeJS (game engine).<br> - Server: Varnish for server-side caching, CentOS.<br> - Utility: Source control with SVN, issues tracking with Jira."
+++
