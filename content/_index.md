---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: ae_hero
    id: home
    content:
      eyebrow: Kuwait · Data & AI · Cloud
      name: Ahmed Ewis
      role: Data Scientist & AI Solution Architect
      lead: I design, build, and ship **secure, production-grade AI** on Azure — from LLM and agentic solutions to classical machine learning — for enterprise banking.
      chips:
        - Azure AI Foundry
        - LLMs & RAG
        - Agentic AI
        - MLOps
        - Docker & CI/CD
        - Guardrails & Security
        - Data Governance
      photo: images/ahmed-ewis.jpg
      badge: Microsoft Certified Architect
      buttons:
        - label: Get in touch
          url: '#contact'
          icon: fas fa-paper-plane
          style: ae-btn-primary
        - label: LinkedIn
          url: https://www.linkedin.com/in/ahmedewis95/
          icon: fab fa-linkedin-in
        - label: GitHub
          url: https://github.com/AhmedEwis
          icon: fab fa-github
        - label: Kaggle
          url: https://www.kaggle.com/ahmedewis
          icon: fab fa-kaggle
      stats:
        - value: 6+
          label: Years in Data & AI
        - value: 10+
          label: Production ML Models
        - value: 6
          label: Professional Certifications
        - value: Enterprise
          label: AI in Banking
    design:
      background:
        gradient_start: '#0a1a33'
        gradient_end: '#14305c'
        gradient_angle: 135
        text_color_light: true

  - block: ae_about
    id: about
    content:
      kicker: About
      heading: Turning complex data into measurable business value
      summary: |-
        Microsoft Certified Data Scientist, Azure Solutions Architect, and Azure AI Apps and Agents Developer with over 6 years of experience delivering secure, scalable, AI-driven cloud solutions. As a Data Scientist and AI Solution Architect, I specialize in generative AI, agentic solutions, Azure architecture, and transforming complex data challenges into measurable business value. I combine strong analytics, technical leadership, and stakeholder communication to drive innovation and organizational growth.
      interests:
        - Data Science
        - Artificial Intelligence
        - Voice AI & Custom Neural Voice
        - Cloud Solutions
      education:
        - degree: MSc Chemical Engineering
          institution: Kuwait University
          year: 2023
          gpa: 3.71/4.0
          link:
            label: Read thesis
            url: uploads/Ahmed_Ewis_thesis.pdf
        - degree: BSc Chemical Engineering
          institution: Kuwait University
          year: 2018
          gpa: 3.3/4.0

  - block: ae_cards
    id: expertise
    content:
      kicker: What I do
      heading: Core Expertise
      subheading: End-to-end AI delivery, from architecture to secure production.
      items:
        - icon: fab fa-microsoft
          title: Azure & Microsoft Foundry
          points:
            - Azure AI Foundry, Azure OpenAI, AI Speech
            - Azure ML and App Service
            - Cloud solution architecture
        - icon: fas fa-robot
          title: LLMs & Agentic AI
          points:
            - RAG and enterprise knowledge assistants
            - Multi-agent workflows, Copilot Studio
            - Custom Neural Voice and speech AI
        - icon: fab fa-docker
          title: Production & MLOps
          points:
            - Docker and CI/CD with GitHub Actions
            - Monitoring, drift detection, retraining
            - Enterprise deployment and publishing
        - icon: fas fa-shield-alt
          title: Guardrails & Security
          points:
            - AI guardrails and content safety
            - Identity, RBAC, and secrets management
            - Secure networking and private endpoints
        - icon: fas fa-balance-scale
          title: Data Governance & Compliance
          points:
            - GDPR and data residency
            - Central Bank of Kuwait (CBK) CORF
            - Responsible AI
        - icon: fas fa-chart-line
          title: Machine Learning
          points:
            - Churn, propensity, and segmentation models
            - Forecasting and recommendation systems
            - scikit-learn, PyTorch, TensorFlow

  - block: ae_skills
    id: skills
    content:
      kicker: Toolbox
      heading: Skills
      groups:
        - name: Programming & ML
          icon: fas fa-code
          items: [Python, R, SQL Server, NoSQL, scikit-learn, TensorFlow, PyTorch, Keras, Julia, Git]
        - name: Cloud & AI
          icon: fas fa-cloud
          items: [Azure Cloud, Azure AI Foundry, Azure ML, Google Cloud, AWS SageMaker, LLMs, LangChain, Generative AI, Computer Vision]
        - name: Back End & DevOps
          icon: fas fa-server
          items: [Flask, FastAPI, Docker, GitHub Actions, Heroku, Firebase, Supabase]
        - name: Data Governance & Compliance
          icon: fas fa-user-shield
          items: [GDPR, CBK CORF, CBK Regulations, Data Residency, Responsible AI]
        - name: Reporting & Visualization
          icon: fas fa-chart-pie
          items: [Power BI, Tableau, Advanced Excel]
        - name: Soft Skills
          icon: fas fa-users
          items: [Problem-Solving, Decision Making, Stakeholder Management, Technical Consulting, Mentoring, Cross-Functional Leadership]

  - block: ae_timeline
    id: experience
    content:
      kicker: Career
      heading: Experience
      subheading: From engineering foundations to enterprise AI in production.
      companies:
        - name: Warba Bank
          mark: W
          tone: blue
          url: https://www.warbabank.com/
          location: Kuwait
          period: Feb 2022 – Present
          tag: 2 promotions
          roles:
            - title: Data Scientist
              dates: Feb 2025 – Present
              points:
                - Architected AI solutions in production
                - Custom Neural Voice & speech AI
                - LLM, RAG & agentic AI on Azure
                - Dockerized deployment & CI/CD
                - Guardrails, security & governance
            - title: Senior Data Engineer
              dates: Feb 2023 – Feb 2025
              points:
                - Led machine learning into production
                - Architected 10+ production ML models
                - MLOps — monitoring, drift & retraining
                - Cloud & on-premises deployment
            - title: Data Engineer
              dates: Feb 2022 – Feb 2023
              points:
                - Development of machine learning models
                - Churn, propensity & segmentation
                - Automated dashboards & reporting
        - name: Kliky AI
          mark: K
          tone: violet
          url: https://kliky.ai/en/
          location: Kuwait
          period: Jul 2021 – Dec 2022
          tag: Part time
          roles:
            - title: AI Engineer
              dates: Jul 2021 – Dec 2022
              points:
                - Led AI development end to end
                - Generative AI with GANs
                - Text-to-video MVP
                - Fine-tuning BERT & CLIP
        - name: Bait Al Aseel Group
          mark: BA
          tone: amber
          url: https://baitalaseel.com/
          location: Kuwait
          period: Aug 2018 – Jan 2022
          roles:
            - title: Chemical Engineer
              dates: Aug 2018 – Jan 2022
              points:
                - Data analysis & forecasting
                - Costing sheets & pricing
                - Tendering
                - Technical documentation
        - name: Kuwait University
          mark: KU
          tone: teal
          url: https://ku.edu.kw/
          location: Kuwait
          period: Mar 2018 – Feb 2021
          tag: Part time
          roles:
            - title: Teaching Assistant & Research Co-Supervisor
              dates: Mar 2018 – Feb 2021
              points:
                - Programming courses for youth
                - Research data analysis & mining
                - Student research support

  - block: ae_certs
    id: certifications
    content:
      kicker: Credentials
      heading: Certifications
      items:
        - code: AB-100
          title: Agentic AI Business Solutions Architect Expert
          issuer: Microsoft
          issuer_key: microsoft
          icon: fab fa-microsoft
          year: 2026
          url: https://learn.microsoft.com/en-us/users/ahmedewis95/credentials/2a226523424f7a12
        - code: AI-103
          title: Azure AI Apps and Agents Developer Associate
          issuer: Microsoft
          issuer_key: microsoft
          icon: fab fa-microsoft
          year: 2026
          url: https://learn.microsoft.com/en-us/users/ahmedewis95/credentials/4122ab67d5476232
        - code: PMLE
          title: Professional Machine Learning Engineer
          issuer: Google Cloud
          issuer_key: google
          icon: fab fa-google
          year: 2023
          url: https://www.credly.com/badges/72f631c9-392a-43aa-b19a-6ec3be6b5be6
        - code: ACE
          title: Associate Cloud Engineer
          issuer: Google Cloud
          issuer_key: google
          icon: fab fa-google
          year: 2023
          url: https://www.credly.com/badges/ff87caa3-767b-4869-b38a-58e3edddadf2
        - code: DP-100
          title: Azure Data Scientist Associate
          issuer: Microsoft
          issuer_key: microsoft
          icon: fab fa-microsoft
          year: 2023
          url: https://www.credly.com/badges/e9573cc9-8dd0-4d63-ae02-95547a18630e/
        - code: IBM
          title: Data Science Professional Certificate
          issuer: IBM · Coursera
          issuer_key: ibm
          icon: fas fa-award
          year: 2020
          url: https://www.coursera.org/account/accomplishments/specialization/certificate/YK5XBQKN4UKV
      courses:
        - title: Machine Learning
          issuer: Stanford University · Coursera
          year: 2020
          url: https://www.coursera.org/account/accomplishments/certificate/CN5XY4YGKTVY
        - title: Convolutional Neural Networks in TensorFlow
          issuer: DeepLearning.AI · Coursera
          year: 2021
          url: https://www.coursera.org/account/accomplishments/verify/MGAFNTRA9U5J
        - title: Time Series Analysis with Python
          issuer: 365 Data Science
          year: 2021
          url: https://learn.365datascience.com/certificates/BB-3E69BCB366/
        - title: Customer Analytics in Python
          issuer: 365 Data Science
          year: 2021
          url: https://learn.365datascience.com/certificates/BB-78C4085615/
        - title: SQL + Tableau + Python
          issuer: 365 Data Science
          year: 2021
          url: https://learn.365datascience.com/certificates/BB-118A04A53A/

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Thanks for visiting! If you have questions or want to connect, feel free to reach out. You can contact me directly through the form below or at my email address. Looking forward to your message!
      # Contact (add or remove contact options as necessary)
      email: eng_ahmed95@outlook.com
      #phone: 888 888 88 88
      #address:
        #street: 450 Serra Mall
        #city: Stanford
        #region: CA
        #postcode: '94305'
        #country: Kuwait
        #country_code: KW
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 17:00 to 21:00'
        - 'Friday 11:00 to 15:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      #coordinates:
        #latitude: '37.4275'
        #longitude: '-122.1697'  
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/sor3a95'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'live:eng_ahmed95_1'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://us05web.zoom.us/j/6826285731?pwd=7rmLWKuO0RzODCFgYzopzuDeNRSHES.1'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
