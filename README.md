## App Name: MoodMoji

## Team Members
- Nicoleta Dublea
- Sara Beslic

## Description
The cute animated design-inspired mood-tracking app allows users to input their daily thoughts and emotions through emojis and journal writing.

## App Concept
**Use Case**: The app helps users develop a habit of self-reflection and emotional awareness by providing a simple, visually appealing way to track their daily moods and thoughts.
Individuals aged 13 and above who enjoy introspection and journaling, as well as those seeking a supportive tool to track and better understand their emotions.

## High fidelity prototype
![frames MoodMoji](frames.jpg)

## User Flow Diagram
![flow MoodMoji](flow.jpg)

## Usability Test
[Download the Usability Test](MoodMojiUsabilityTest.pdf)


## MoodMoji Development Process 
The development process for MoodMoji was fast-paced and efficient, taking us just under two weeks, as initially planned for the Code Lab. We started by dividing the tasks between us, so we knew exactly what each of us had to focus on.

By day 3, we had already set up the database and completed most of the design, along with a few smaller details. By the end of the first week, the app was nearly done. We only had a few minor issues left to address and the user testing to go through.

By the day before our final presentation, the app was fully functional. We managed to test it with five users, all the features were working smoothly, and the app was ready to be downloaded.


## Database 
![Database](database.jpg)

The MoodEntity ID is auto-generated and distinct from the emoji ID. The EmojiId corresponds to the Emoji class, EmojiId=id(Emoji class), which is assigned a number ranging from 1 to 12. The properties associated with each emoji are retrieved from the database based on the saved EmojiId.


## Heuristic Evaluation during app development
**1. Visibility of System Status**

No major issues found.

**2. Match Between System and Real World**

No major issues found.

**3. User Control and Freedom**

**Issue:** Users can easily edit or delete mood entries easily, but there’s no confirmation dialogue after deleting an entry. 

**Solution:** Adding a confirmation dialog for delete actions to avoid accidental loss of data. 

**4. Consistency and Standards**

No major issues found.

**5. Error Prevention**

**Issue:** The app prevents invalid inputs by disabling the "Add Mood" button if no emoji is selected, but the journal field doesn’t validate excessive input. 

**Solution:** Adding input length limits or warnings for the journal field to prevent saving excessively long entries. 

**6. Recognition Rather Than Recall**

No major issues found.

**7. Flexibility and Efficiency of Use**

**Issue:** Basic users can track moods quickly, but advanced users may find it difficult to analyse trends over time without detailed reports.

**Solution:** Adding optional features like mood graphs or filters for advanced users. 

**8. Aesthetics and Minimalist Design**

No major issues found.

**9. Help Users Recognize, Diagnose, and Recover from Errors**

**Issue:** There are no error messages or warning when deleting an entry. 

**Solution:** Considering to add error messages. 

**10.Help and Documentation**

No major issues found.








**Strenghts:** 
- The use of emojis for mood tracking is intuitive, making it engaging and easy for users to understand and interact with.
- A clean and consistent design across the app improves usability and reduces cognitive load.

**Weaknesses:**
- Some actions, like deleting entries, lack a confirmation step, which could lead to accidental mistakes.
- The app currently offers a limited set of features, which may not fully meet the needs of users looking for deeper emotional analysis or reporting.

## Test Setup
The usability test was conducted with 5 participants, focusing on understanding how they interact with the app and identifying any usability issues in the user flow, focusing on tasks such as adding an entry with an emoji and notes, editing and deleting a journal entry and more.

## Target Group
- Age: 13+
- Interests: Mood tracking, self-reflection, journaling

## Hypothesis and Questions
**Hypotheses**:
1. Journaling alongside emojis will enhance users’ reflection on their emotions, encouraging deeper self-awareness.
2. The calendar-based navigation system will allow users to easily access and navigate their mood records over time.

**Questions**:
1. Are users able to complete the "Add Mood" and "Update" actions without external help?
2. Does the app encourage consistent mood tracking over time?

## Metrics
1. Task Completion Rate
2. Error Rate
3. SUS Score
4. Qualitative Feedback


## Tasks
**Task 1:** Open the calendar and select a date to view its details;

**Task 2:** Add a new mood for today and write a short note;

**Task 3:** Update an old journal entry;

**Task 4:** Delete today's entry; 

**Task 5:** Edit a journal entry through the journal view.

After all of the tasks were realized, testers were given a SUS and post-task questionnaire.

## Results
--adding later--

## Final App 
--adding later pics and description--


## Contributions
**Sara**-Designed and integrated the database, implemented the calendar view UI and logic, developed the journal feature, managed navigation, created the emoji object and applied its properties across the app, contributed to testing, and worked on the landing screen.

**Nicoleta** – Designed the high-fidelity Figma prototype, integrated navigation with pop-up windows, refined design details throughout the app, implemented the confirmation dialog box, prepared emoji images, and tested design responsiveness across different phone sizes.

**Together** – Worked on pop-up windows, conducted testing, and collaborated on design ideas.

## Final Thoughts
**Sara**-

**Nicoleta**- --adding later--
