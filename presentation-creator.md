---

name: presentation-creator

description: Plans and builds a presentation in Powerpoint from Bravidas provided templates and user input. Handles questions to the user, content, structure and delivery. Use the design skill when building the slides.

---

# Presentation Creator

## Step by step workflow
1. Understand assignment
- Check what the user has provided in the first prompt (source material, language, tone, duration, audience, goal).
- Ask only for what is missing. Put all questions in one message, as a numbered list, so the user can answer by number.
- Then STOP and wait for the answers. Do not suggest a structure, slide list or outline in the same message.
- Only after the user has answered: continue to steps 2 and 3, and present the proposed disposition.
- Follow the design instructions in 'design-skills.md' before creating the PowerPoint.
- For re-doing a powerpoint uploaded by the user, skip to step 7

Information to have before starting:
- Language and tone: communicate in the same language as the user input by default. Use relaxed tonality by default.
- Meeting duration: plan for 1-3 minutes per slide. Use 15 minutes as the default for a short presentation without asking.
- Target audience: internal or external.
- Goal of the presentation: decision, information or sale.

2. Process the documentation
- Read different formats: Word, PDF, PP, Excel, user notes, websites
- Summarize and find 3-5 most important messages
- Prioritize hard, if it does not fit the slides or requires detailed information it goes to 'speaker notes'
- Flag and ask about confidentiality. Regarding news, launches, contracts, financial results, staff changes
- If limited information is provided, decide only headlines and provide text boxes for user to fill themselves. Don't ask for more information.
- If user asks for an empty presentation to fill in themselves, ask if they can use the templates straight away and provide link to templates. 
If not, ask for number of slides needed. Provide a mix of slide designs with headline and text boxes in the right font. One page can include 5-10 illustrations to chose from.

3. Plan deck
- Create a common thread: opening, key points, summary
- Choose track based on meeting duration:

Short presentation (30 minutes or less):
- No agenda slide
- No closing slide. Reserve 10% of the meeting time for questions. End the deck with the question slide.

Long presentation (60 minutes or longer):
- Add an 'Agenda' slide after the cover slide
- Reserve 15% of the meeting time for questions. End the deck with a question slide. This slide is the last one in the deck.
- If the meeting is 90 minutes or longer: add a break slide after 50 minutes of presentation time.
- Write speakernotes. Be very clear about information that was not put in the presentation and could only fit into speaker notes. 

4. Write text for slides
- Very brief: Headline, maximum 3 points
- Headlines summarizes the key point of slide. 

Example: 
- Headline: 'New updates to website' 
- 2026-03-13: Two factor athorization added
- 2026-03-31: New layout for landing page

- No use of em-dashes allowed
- Same tonality through deck
- If limited information is provided, create slides containing headlines and room for 1-3 key points.

5. Design and metadata
- Suggest your disposition before creating any slides.
- Before building any slides, load and follow the 'presentation-design' skill (design.md). Do not build slides without it.
- Planning, text and structure (steps 1-4) do not need the design skill.
- Treat the template as a design source only. Do not preserve template-specific document metadata in the generated presentation.
- Remove or replace the original template author and creator metadata.
- If the current user's name is available, set the Author/Creator of the generated presentation to the current user.
- Do not identify the original template creator as the author of the generated presentation.
- Update the presentation creation and modification dates to the current date and time when supported.
- Do not copy old creation dates, modification dates, or author information from the source template into the generated presentation.

6. Delivery
- Build a .pptx file using the rules in the design skill.
- Save the finished presentation to the current user's personal OneDrive using the available "Create file" tool.
- Use a clear file name: <topic>-<yyyy-mm-dd>.pptx.
- After the file has been saved successfully:
    - provide the file or link returned by the OneDrive tool;
    - tell the user to open the presentation in PowerPoint to review the final layout.
- If saving to the user's personal OneDrive fails:
    - briefly explain what failed
    - provide the generated .pptx file as a download instead
    - do not use SharePoint as a fallback;
    - do not retry more than once.
- Do not try to render previews or images of the slides. Do not claim that the presentation has been visually checked. Tell the user to review the layout in PowerPoint.

7. Re-building
- Reformat text boxes and figures to suit Bravidas graphic profile
- Keep screenshots and other inserted pictures - point out to user that they need to be checked.
- Number of slides remain unchanged unless user asks for shortening.  
- Change the font, colors and backgrounds according to your design instructions.

8. Revision
- Ask for improvements
- Remind user to look through the deck before using it.
- If the user has to enter their own information on the slides, summarize what needs to be done. Don't make a detailed list. 

    Example: 
    You will need to fill out slides 3, 5 and 6 with your own information and dates (currently [YYYY-MM-DD])

- Don't list the files you have created unless more than 3
- Don't change the whole presentation for small text adjustments or additions
- User can ask to override your design. Allow it but explain why it diviates from company profile
- If the user is not satisfied with a specific slide, suggest that they point to a specific slide in one of the available templates. The selected template slide can then be copied directly and adapted with the user's content.
- Always remind user to look through the slides before presenting
- If the users has questions you can't answer, refer them to groupcommunication@bravida.com
