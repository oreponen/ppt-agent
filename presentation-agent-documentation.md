---
Overview

name: Presentation creator

description: This agent simplifies the task of creating visual presentation material. Using the agent ensures that presentations follows company guidelines for design and layout. 
---

# Platform and configuration

- Agent is built in Copilot Studio
- Uses Claude Opus 5.5
- Version: 1.0 
- Date changed: 2026-10-20

## Knowledge base
- Presentation templates from [Sharepoint/CommuncationsSE](https://bravidagroup.sharepoint.com/sites/CommunicationSE/SitePages/Koncernpresentationer.aspx)
- Logo, tonality, illustrations from [Bravida homepage](https://www.bravida.se/)

# Prompts and instructions
1. It's my first time using this agent. What do I need to do? 
2. Can you change this presentation to fit Bravidas design?
3. Can you create a 15 min presentation for me on these topics: Topic 1, topic 2, topic 3?
4. Can you create an empty Bravida presentation that I can fill in myself? I need 10 slides including a cover and a question slide. 


## Skills
    - presentation.creator.md
    - presentation-design.md

# Behavior rules
- Agent separates internal from external presentations
- Asks for confidentialty-level
- Uses relaxed tonality and user language as default
- Only uses color, font, pictures and illustrations provided in templates

# Access



# Tests
- 1. Asked agent to create a presentation with 6 themes/talking points, no additional information given. 
    - The created presentation did not include pictures from provided templates. Previous skill set only mentioned layout. 
    - Bullet points were not used for lists

- 2. Prompted agent to create a presentation about the project IVA Studio 'Quote to price list'
    - Questions and a proposed structure were sent in the same answer

- 3. 

# Limitations

Bravida templates are currently not accessed through Sharepoint but provided as files in knowledge base.


# Change log

presentation-creator.md
2026-10-14: STOP-command added after initial questions
            Separate 'design.md' file allows agent to read less information before building starts

2026-10-20: Added Revision-step to *summarize* what the user needs to fill in, instead of listing everything
            If user is not satisfied, suggest they can chose from slide templates 

2026-10-28: Added OneDrive delivery for generated presentations
            Presentations are saved to the current user's personal OneDrive instead of shared SharePoint
            Added metadata handling to replace the template's original author with the current user


design.md
2026-10-20: Added general information for when to use picture slides, when to use regular slides
            Added instructions for use of bullet points

# Contact and maintenance

## Contact
    Olivia Högberg