# ecoExplorer Showcase

## What This Project Is

ecoExplorer is an interactive educational website built to help Australian children aged 8 to 12 learn about native and invasive species in a way that feels playful, approachable, and memorable. The project is framed around **UN Sustainable Development Goal 15: Life on Land**, with a focus on raising early awareness of biodiversity, ecosystem protection, and the environmental impact of invasive species in Australia.

Rather than presenting ecology as a static textbook topic, ecoExplorer turns it into an experience. The website combines storytelling, mini-games, quizzes, species exploration, and an AI chatbot to make environmental learning engaging for children while still being useful for parents and teachers.

## The Problem It Solves

Australia faces ongoing ecological pressure from invasive species, yet biodiversity education for younger children is often limited or not presented in a way that keeps them engaged. ecoExplorer addresses this by:

- translating complex ecological ideas into child-friendly language
- helping children recognise the difference between native and invasive species
- encouraging curiosity through interaction instead of passive reading
- supporting sustainability education in a format that aligns with school and family learning

## Who It Is For

- Australian children aged 8 to 12 as the primary audience
- parents who want safe, educational digital content
- teachers looking for sustainability-aligned learning tools
- future sponsors and environmental partners interested in biodiversity education

## What The Website Does

ecoExplorer is designed as a multi-feature learning platform. Based on the provided product and support documents, the full website experience includes the following:

### Storytelling

The storytelling section delivers age-appropriate stories about native and invasive species. These stories are retrieved dynamically from a central database so content can be updated without changing the frontend. The platform also includes an auto-read narration feature to support children who prefer listening, are early readers, or benefit from accessibility support.

### Gamified Learning

The main game, **Protect Elves**, is a fast-paced tapping game where children identify invasive species and stop them from reaching protected native characters. This helps reinforce ecological awareness through active, repeatable play rather than passive instruction.

### Species Collection

The species collection gives children a visual catalogue of Australian native and invasive species. Each entry is presented as an interactive card and expands into a richer profile with educational details such as:

- scientific name
- habitat
- diet
- lifespan
- ecosystem role
- fun facts

This section also supports filtering and search, helping children explore the content in a way that feels more like discovery than study.

### Interactive Quizzes

The quiz experience lets users test what they have learned through different quiz modes, including native species, invasive species, and an AI-powered quiz mode. The AI quiz uses species data stored in the platform to generate child-friendly questions that feel fresh and personalized.

### AI Chatbot

ecoExplorer includes an AI chatbot named **Bob**, designed as a friendly virtual guide for children. Bob supports typed and voice-based interaction, answers questions in a simple and encouraging tone, and helps users navigate the site while learning more about species and ecosystems.

## Why The Project Stands Out

ecoExplorer is not just an information site. It is designed as a child-focused learning experience that blends:

- environmental education
- playful interaction
- AI-assisted support
- accessible storytelling
- structured biological data

This combination makes the project stronger than a standard educational website because it supports different learning styles. Children can read, listen, play, search, ask questions, and test themselves within the same platform.

## Product Vision

The broader vision behind ecoExplorer is to build environmental literacy early. The project aims to help children care about biodiversity before these issues become abstract or distant. By introducing ecological responsibility through fun and understandable digital experiences, the platform encourages a generation of more eco-conscious Australians.

## Technical Overview

According to the support documentation, the project uses a modular cloud-based architecture designed for performance, maintainability, and scalability.

### Frontend

- Vue.js
- Tailwind CSS and Bootstrap
- Axios for API communication

The frontend focuses on strong visuals, intuitive navigation, and child-friendly interaction patterns.

### Backend

- AWS Lambda for serverless application logic
- Amazon API Gateway as the API entry point
- authEdge / Lambda@Edge for access control

This architecture allows the platform to update features independently and scale without maintaining traditional servers.

### Data Layer

- Amazon RDS MySQL for structured species and story data
- JSON-based datasets prepared and transformed before ingestion
- Open data and AI-enriched content pipelines

The structured database design supports searchable species content, dynamic stories, and quiz generation.

### Hosting and Delivery

- Amazon S3 for static hosting
- Amazon CloudFront for CDN delivery
- HTTPS via AWS Certificate Manager
- Custom domain delivery for the public website

## Data and Content Pipeline

One of the most interesting parts of the project is how content is assembled. The provided documents describe a pipeline that combines:

- open ecological data sources
- curated biological facts
- AI-supported enrichment
- manual review for child-friendly quality

Data is sourced from reputable platforms such as the Atlas of Living Australia, Wikipedia, and iNaturalist, then cleaned and transformed into a structured dataset. AI tools including OpenAI models and Google Gemini are used to rewrite or enrich information in ways that are more engaging and easier for children to understand. The final result is educational content that remains factual while being more accessible to the target audience.

## Ethics and Safety

The project documents make it clear that ecoExplorer was designed with ethical considerations in mind, especially because the audience is children.

Key principles include:

- no personal data collection from users
- child-appropriate AI prompting and responses
- educational rather than manipulative use of gamification
- privacy-conscious platform design
- content aimed at empathy, sustainability, and ecological responsibility

This is an important part of the project because it shows the team treated child safety and responsible AI use as part of the product, not as an afterthought.

## Maintenance and Operational Support

The support materials show that the project was also planned as a maintainable system, not just a prototype. Operational planning includes:

- source control and version backup through GitHub
- AWS-hosted database backup strategy
- security assessment and vulnerability testing
- data update procedures for species datasets
- governance and handover documentation for future maintainers

That means the project was designed with continuity in mind, making it easier for future teams, sponsors, or maintainers to extend and support the platform.

## Security Approach

The documented security posture includes:

- HTTPS enforcement
- SSL/TLS certificate management
- restricted database access
- cloud-based access boundaries
- vulnerability assessment and penetration testing

The project also references the use of common security testing tools and a dedicated security plan, showing that security was considered as part of deployment and operations.

## Future Potential

The product documents position ecoExplorer as a platform with strong long-term expansion potential. Future growth could include:

- more native and invasive species
- additional ecological topics beyond animals
- richer teacher and classroom support materials
- broader sponsor and environmental partner collaboration
- expanded educational content aligned with sustainability learning

Because the project already combines cloud delivery, structured content, and AI-assisted educational features, it has a solid foundation for scaling beyond its initial release.

## In One Sentence

ecoExplorer is a child-focused environmental education platform that uses storytelling, games, structured species data, quizzes, and AI support to teach Australian children about native and invasive species in a fun, safe, and meaningful way.

## Source Basis

This showcase summary is based on the two project documents you provided:

- `Support Document.docx`
- `Product Document.docx`

It is intentionally written as a polished showcase overview of the full project and avoids including sensitive operational credentials from those documents.
