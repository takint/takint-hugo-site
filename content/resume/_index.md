+++
css = ["resume.css"]
date = "2017-05-12T10:24:23+02:00"
description = ""
scripts = ["main-min.js"]
tags = []
title = "Resume"

[params]
    # Main body sections

    # You may use markdown in summary, details and intro fields. But don't overdose, it's resume!:)

    # Summary section
    [params.summary]
        enable = true
        icon = "fa-user"
        title = "Career Summary"
        summary = "Full Stack Software Developer with 6+ years of experience in software development field and Microsoft technique through .NET Framework, C# language, MSSQL and beyond. Advanced in Front-end technique through HTML5/CSS3, AngularJS, ReactJS and JQuery.<br/>Flexible mindset, adapt with changes very effectively and positively. Always be a model in showing positivity to others. I’m a friendly guy and have a good sense of humor."

    # Experiences section
    [params.experiences]
        enable = true
        icon = "fa-briefcase"
        title = "Experiences"

        [[params.jobs.list]]
        position = "Senior Full-stack .NET Developer"
        dates = "2017 - 2018"
        company = "Groove Technology, Ho Chi Minh City, Vietnam"
        details = "It was a challenged opportunity when I joined Groove as a Senior Full-stack .NET developer, the new project with new business domain (logistics) and it demanded the latest techniques and had to finish within six months. I’ve had a chance to work with the most awesome team ever since I started my career path. My responsibilities included the initial and creating the project, design and develop features base on product owner’s requirements and mentoring junior members."

        [[params.jobs.list]]
        position = "Full-stack .NET Developer"
        dates = "2015 - 2017"
        company = "AS White Global, Ho Chi Minh City, Vietnam"
        details = "Played the role of Full-stack .NET developer. After a year, I’ve done my best and achieved the title senior .NET developer. My responsibilities in the team that I cooperated during two years were:<br> - Creating a cool web application which is a Policies Insurance management. And it made our client (Steadfast) extremely satisfied.<br> - Developing a tools which helped to migrate the database from the old version and the other Insurance applications to the new application which was developed by my team.<br> - Working with Q.A team to develop an automation testing tool for our main project.<br> - Build and run unit testing for my own codes. Implement automation test cases using Selenium framework."

        [[params.jobs.list]]
        position = "Freelancing"
        dates = "2014-2015"
        company = "FF Team, Ho Chi Minh City, Vietnam"
        details = "Project POD | (Hybrid Mobile with Xamarin) - POD stand for Pay off Debt, this mobile application is implement Snow Ball algorithm to help user manage their debt and paid it quickly. This project used Xamarin C# for development. Tracking issues with Jira.<br><br>Project Revsym product | (Single page web application) - Revenue recognition software. It is a complete Revenue sub-ledger and it also has an inbuilt Contract Management capability. Account for multiple revenue types, such as subscriptions, licenses, and professional services. I’ve worked with the front-end team and using AngularJS for this project.<br><br>Project vietnamcarrent.com | (WordPress page) - This is a WordPress page helped my client (a car rental agency) run their business. It help users easy to find a car to rent from my client."

        [[params.jobs.list]]
        position = ".NET Developer at "
        dates = "2013 - 2014"
        company = "Harvey Nash VN (Nash Tech), Ho Chi Minh City, Vietnam"
        details = "I continued my .NET career path as a developer when joined HVN which is an outsourcing company. When I had joined, the company demanded for several front-end developers who could join the first front-end oriented project of the company. I was one of the volunteer developers whom were willing to learn front-end technologies (AngularJS, LimeJS) and contributed my efforts. After a couple week of training, I had joined the project and contributed to build a lot of products for our client."

        [[params.jobs.list]]
        position = "Junior .NET Developer"
        dates = "2012 - 2013"
        company = "NEC VN, Ho Chi Minh City, Vietnam"
        details = "After I had graduated from my University, I joined NEC Vietnam (a Japan’s software company) as a junior .NET Developer. When I worked there I had been learned from the Japanese their discipline, meticulousness, carefulness and hard-working. I began my career path with Microsoft .NET technique, my responsibilities included coding follow the design and fixing bug to contribute to a Retail Cloud software which was help our clients to manage their retail chain-stores."

    # Projects section
    [params.projects]
        enable = true
        icon = "fa-archive"
        title = "Projects"
        intro = "I would like to detail some of the projects which I have been a part of."
        
        [[params.projects.list]]
        title = "LTL Project"
        url = "https://www.csglobal-ltl.com/ourplatform.php"
        tagline = "System auto-fills parts of the shipping order, e.g., addresses and other contact details, which are entered in advance in the address book."

        [[params.projects.list]]
        title = "Insight Project"
        url = "https://www.steadfasttech.com.au/insight-1"
        tagline = "INSIGHT is everything you have ever wanted from a broking system. It's a cloud-based platform that gives you what you need to run your insurance broking business - anytime from anywhere."

    # Skills section
    [params.skills]
        enable = true
        icon = "fa-rocket"
        title = "Skills & Proficiency"

        [[params.skills.list]]
        skill = "C#"
        level = "80%"

        [[params.skills.list]]
        skill = "Javascript & Angular & ReactJS"
        level = "70%"

        [[params.skills.list]]
        skill = "HTML5 & CSS"
        level = "60%"

        [[params.skills.list]]
        skill = ".NET Core"
        level = "75%"

        [[params.skills.list]]
        skill = "T-SQL & MSSQL"
        level = "65%"

        [[params.skills.list]]
        skill = "Azure Cloud Services"
        level = "70%"

+++
