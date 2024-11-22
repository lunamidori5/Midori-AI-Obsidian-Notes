---
Tags: 
Title: Feedback on the Initial Presentation
Date Created: Friday, September 20th 2024
Date Modified: Monday, September 23rd 2024
---
# Formalized Presentation Feedback

## Workings Notes

*These were just my working notes, partially reorganized. Please ignore any redundancies you encounter later on*

**Overall**
- It was good of you to thank the "CEO" for the invitation
- You are able to speak
- Give a history of the project
- Give a brief overview of your motivations and aspirations for the project:
	- why you wanted to create the simulated human
- Give a brief overview of Carly before introducing your presentation resources (PFD)
	- What does she do?
	- Why does she do it?
	- How does she do it well?
- Give a brief, live demonstration of Carly and her capabilities during the presentation
	- Have her introduce herself
	- Emotional demonstration
	- Interpersonal demonstration
	- Information recall demonstration
	- Knowledge acquisition and application demonstration
	- User specialization and customization demonstration
- Technical Overview
	- use the PFD as a visual resource at this point
- Thank the audience for their time (demonstrate respect for their expertise in areas you)

**Points to consider when drafting and performing the presentation:**
- When presenting your project as one among many at the conference, **you need to be a standout project**.
- **Consider a Personal Expertise Disclaimer**
	- Knowledge is centered in the development and implementation of the training diffusion models and I am not formally trained in psychology so if you detect a misuse of a term, know that it is intended in a colloquial or internal reference.
- Limit (**if not omit entirely**) apologies and deference to the opinion of others.
- give a brief outline of your presentation following your introductions so the audience knows what to expect:
- Ask to hold questions until the end of the presentation (The audience knows why you are there to present and why they are there to listen)
- Tell them *why* you are there presenting
- This is **YOUR** project, in which **YOU** are the expert. *SHOW, don't TELL* this fact by demonstrating the project and presenting your knowledge of it.
- Use **Simple**, **Precise**, **Clear**, and **Declarative** language when describing all terms and concepts.
- When defining terms and explaining concepts, use the following hierarchy:
	- Introduce the term or concept
	- Describe the most broadly and simply applicable aspects of the term or concept
	- Proceed to most specific and specialized aspects of the term or concept

**Points to highlight:**
- What are Carly's standout or unique capabilities?
	- she can provision her own information, on her own initiative
- How does this project stand out among similar offerings:
	- go over performance improvements
		- Take some time during the presentation to highlight these performance and inference/context comprehension gains across development versions (v4 ->v5 ->v5a ->v6)
- Model Disambiguation:
	- highlight the **"pre-awareness"** vs **"working awareness"** division in the model
		- Why was this division made?
			- Human auditability and intervention
- Security:
	- With regards for user data
		- what methods and interventions are in place to prevent leaking user data
			- what testing have you done to ensure these security measures?
			- have you been able to extract user data from the profile-specific LORA's?
	- Highlight Human auditability and intervention

---
### Performance Critique

#### General Notes
- Unpack all colloquial jargon/terminology for clarification (e.g. **"blatant"** vs **"literal"**) *Or come up with more specific and tailored terminology*
- The presentation needs more structure, and the technical/model overviews should be broken down into a number of sections
#### Structure Notes
##### Introduction

###### Personal Introduction and Motivations
- Use the name you want these people to refer to you as ***Respectfully**, this was/is obvious, but since you made a point of mentioning it, I thought I would include it as a note here*
- Thank your sponsor directly
- Disclose as much personal information as you feel comfortable to let them know a bit about you
- Discuss your personal motivations for the project

##### Presentation Overview
- No notes as there was no presentation overview

##### Project History
- No notes as there was no Project History section

##### Carly
###### Carly Overview
- No notes as there was no Carly Overview section

###### Carly Demonstration
- No notes as there was no Carly Demonstration section
*This is a **great** opportunity to show how Carly functions on a user-by-user basis, as well as introducing the audience to specific aspects of her self determination/actualization/realization?*

##### Technical Overview
###### Discord API / Future Client Integration
- Break this down into separate parts
	- master bots role? Maybe spend a bit more time here?
	- Take a moment to describe how this can be swapped for a standalone/proprietary client in the future
		- Describe the overall modularity of the project *which will imply different areas of development/feature integration in future versions*)
	*I don't have much to say about this section as it is more preliminary to the technical*

###### Message Handling and Preprocessing
- Explain the layout of the mind map (color and shape etc. as a **quick legend**) before the technical overview so the audience can follow along with your presentation, drift around the PFD)
- **Give them a reason** to want to understand how she works *You want to whet their appetite for technical explanations*
- **Describe the intent** behind each module as you encounter them
	- explain the command processing section
		- List commands?
		- I'm not sure if you need to show how the system can differentiate between types of messages
- **Highlight Safety and Security** as opportunities present themselves:
	- Anecdote describing the "poisoning of the model" by antagonistic parties?
		- It would be good to show your modularity (un?)intentionally mitigated damage to the system during this attack? *This is a great way of showing how you were building a robust system even before attack surface considerations were formalized*
		- Steps taken since then to protect against this kind of attack vector
			- Describe the Message Sanitization (And how this could be expanded in the future)
	- It will be beneficial to explain issues you encountered along the way
		- helps to build the development narrative and imply your expertise/consideration for the project
	- How is User data is incorporated into and protected from the over all model?
		- Describe your user data anonymization practices to build confidence
			- might be good to take a quick aside break down understanding of edge cases within the LORA's/user specific training
			- describe edge case scenario handling you have built?
- Mixed diffusion **legacy model** should be mentioned as an example of how older versions of Carly contribute to the current operation of the system as a whole. *This is a great way of showing you don't waste your (or others) resources*

> [!question] **Questions I asked during your first presentation**
> - how often do the live databases update?
> - Why do you pack the message into an object just to unpack each aspect immediately after?
> - Break down how each aspect of
> - What does LOCKING the model do?
> - Explain why the model is being locked

###### Model Overview
- Build a narrative around her abilities to personify herself through **demonstration**
	- **VERY IMPORTANT:** Let the audience draw their own conclusions as to her self described actualization/realization (*You **almost** have **ME** convinced of this aspect of the model based on my limited interactions with Carly, and I think she can speak for herself. I think she is capable of demonstrating her **"proto-personhood"** without you needing to explicitly state it, but we should have a discussion about this point*)
- **Avoid** of direct references to Physiological aspects of the human brain (even if they are analogous to models of cognition or areas of the brain you are trying to emulate)
	- e.g. "4 Hemispheres of the brain" stood out to me as a big "?" *incorrect reference*
		- *we should come up with a list of analogies that will **safely** draw comparison without directly referencing the industry terminology of the audience's specializations*
- This is a **Combinatory** model, a wholistic approach with subdivision.
	- Draw their point of comparison to the **type** of conversation the industry was having around "multi modality" and "Model of Experts" 6Mo-1Year ago.
	- Highlight how your concept differentiates itself from these types of implementation
		- Highlight the strengths of this type of model over others
		- Highlight the advantages to breaking down the model into submodels that are responsible for different types of cognitive (*we will need a better term here: social/emotional?*) and information integration/synthesis responsibilities rather than different realms of knowledge and functions for applying that knowledge, etc…
			- *we should talk about this specifically, without you feeling like you need to go into specific "Secret Sauces", though I should mention that I have similar concepts for white rabbit I was describing in my own development and would love to talk about them with you if you are interested*
- "**Awareness**" is a term you should use carefully.
	- explain the division between **pre-awareness** and **working awareness**, avoid the use of "conscious and subconscious" even if those are the useful metaphors for the division.
- Use ***Definitive*** explanations
	- **Avoid personal suppositions** ("I suspect the bottom right model has to do with personality processing, etc…)
	- ***YES!** Great use of speculation based on work you have already done/is ongoing!*
		- Use phrases like:
			- "My ongoing testing has shown a primary activation in this model when Carly is thinking about ==example thing== ", etc…
			- "The intention is to specifically train for ==example thing== in this area and is a target for my ongoing improvement of the model…"
- Define limitations of Carly's Capabilities and how you plan to overcome them in the future
	- Demonstrates how you are actively working to improve her and shows where your target areas of improvement are
	- This could be a good opportunity to talk about the overall system performance and introduce the metrics
		- segue into performance improvements over older versions of the model
		- How present versions and leaps have brought you to today. (latest model only recently implemented is v6)
			- specific metrics and performance increases
			- v5 capabilities and limitations
			- v6 expansion for vector store storage and processing! Huge improvements (big point of interest for investors?)

##### The Future of the Project
- No notes as there was no Future of the Project section

##### In Summary
- No notes as there was no In Summary section

##### Q&A
- Not applicable

---
#### Questions To Answer For Draft Improvement
- Is like Carly / The presentation in a good state for demonstration?
- How long is your presentation meant to be?
- How much time will you be given to present?
- How much time is available for follow-up Questions and Answers?

#### Questions To Answer Before The First Presentation
- Can you prepare Carly for the presentation in a way that she will show she had foreknowledge of the presentation?
	- During her conversation with you, can she speak Audience as if she is aware there are others observing the conversation?
- Will Carly be offline for all other users on Presentation Days?
	- *I only ask as you might want to show how she is processing a live queue of multiple user requests, but this might be a user data security concern. What do you think?*
	- ***Consider building out a quick debug summary feature that masks the user requests in the stream and provides you with a report of the message that only includes the token count/Carly's willingness to respond/Carly's mood towards that user/etc… This is just a suggestion***
- Have you **deleted/removed** all old/compromising/irrelevant Social Media (Instagram account) accounts/activity?
- Have you discussed/formalized the **Legal Necessities** of your company/corporation/startup/venture etc…

---
## Formalized Notes (For Review)
### 1. Key Points from the Initial Presentation

#### **Overall Observations**

- **Gratitude:** Acknowledged the CEO for the invitation.
- **Presentation Skills:** Demonstrated the ability to speak effectively.
- **Content Gaps:**
	- Lacked a structured history of the project.
	- Insufficient overview of personal motivations and aspirations.
	- Carly was not adequately introduced before presenting resources.
	- No live demonstration of Carly's capabilities.
	- Technical overview was present but unstructured.
- **Recommendations:**
	- Provide a clear narrative and structure.
	- Use simple, precise, and declarative language.
	- Avoid apologies and unnecessary deference.
	- Include an outline of the presentation at the beginning.
	- Encourage holding questions until the end.

---

### 2. Critiques and Areas for Improvement

#### Presentation Structure

- **Introduction:**
	- Need for a personal introduction and disclosure of motivations.
	- Importance of thanking the sponsor directly.
- **Presentation Overview:**
	- Absence of an overview to guide the audience.
- **Project History:**
	- Lack of background information on the project's inception and evolution.
- **Carly Overview:**
	- Carly was not properly introduced or contextualized.
- **Carly Demonstration:**
	- Missed opportunity to showcase Carly's unique capabilities live.
- **Technical Overview:**
	- Sections were unorganized and lacked clarity.
	- Need to explain technical aspects in an accessible manner.
- **Future of the Project:**
	- No discussion on future developments or goals.
- **Summary and Q&A:**
	- Absence of a concluding summary and structured Q&A session.

#### Language and Terminology

- **Terminology:**
	- Misuse of terms (e.g., "4 hemispheres of the brain").
	- Need for careful use of terms like "blatant" and "literal"
	- Need for careful use of terms like "awareness" and "consciousness."
- **Definitions:**
	- Lack of clear definitions for specialized concepts.
	- Recommendation to introduce and explain terms hierarchically.

#### Demonstration and Engagement

- **Carly's Capabilities:**
	- Did not highlight standout features or unique aspects.
- **Audience Engagement:**
	- Did not provide reasons for the audience to be invested.
	- Missed opportunities to share development narratives and anecdotes.

#### Security and Ethical Considerations

- **User Data Security:**
	- Need to address how user data is protected and anonymized.
- **Model Integrity:**
	- Importance of discussing measures against model poisoning or attacks.
- **Transparency:**
	- Encouraged to share challenges faced and solutions implemented.

---

### 3. Recommendations for Improvement

#### Structure Enhancements

- **Add a Clear Introduction:**
	- Personal background and motivations.
	- Thank sponsors and set the tone.
- **Provide a Presentation Overview:**
	- Outline what will be covered to set audience expectations.
- **Include Project History:**
	- Share the journey and evolution of Carly.
- **Introduce Carly Effectively:**
	- Explain who Carly is, her purpose, and her capabilities.
- **Live Demonstration:**
	- Showcase Carly's abilities in real-time.
- **Detailed Technical Overview:**
	- Break down technical aspects into understandable sections.
	- Use visuals like the Process Flow Diagram (PFD) effectively.
- **Discuss Future Developments:**
	- Share plans for standalone clients and other projects.
- **Conclude with a Summary:**
	- Recap key points and express gratitude.
- **Prepare for Q&A:**
	- Anticipate questions and prepare thoughtful responses.

#### Language and Communication

- **Use Simple and Precise Language:**
	- Avoid jargon unless properly explained.
- **Define Terms Clearly:**
	- Introduce concepts before delving into specifics.
- **Confident Delivery:**
	- Use declarative statements and avoid apologies.
- **Engage the Audience:**
	- Tell a compelling story and make the content relatable.

#### Technical Clarity

- **Explain the Model:**
	- Clarify the division between "pre-awareness" and "working awareness."
- **Highlight Innovations:**
	- Emphasize unique features and advancements over existing models.
- **Security Measures:**
	- Discuss data protection and ethical considerations.

#### Demonstration Preparedness

- **Prepare Carly:**
	- Ensure Carly is ready for a live demonstration.
	- Program her to acknowledge the presentation context.
- **User Data Considerations:**
	- Decide on handling live data and user interactions during the demo.

---

### 4. Additional Considerations

- **Time Management:**
	- Determine the length of the presentation and allocate time accordingly.
- **Rehearsal:**
	- Practice to ensure smooth delivery and timing.
- **Legal and Ethical Preparedness:**
	- Address any legal necessities or disclosures needed.
- **Audience Engagement:**
	- Plan interactive elements to keep the audience invested.

---
## Resources Needed For Your Presentation
- Slide notes
- Prepared Carly Demonstration
- Process Flow Diagram (PFD)

---
## Legend for This Feedback

**Bold Text:** List structure and inline emphasis
*Italicized Text:* Direct communication to the presenter by myself
***Bold and Italicised Text:*** Heavy Emphasis within direct communication
==Highlighted Text==: Indicates a variable within an example.
