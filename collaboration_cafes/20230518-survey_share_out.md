**When?** 
18 May 2023, 15:00 - 16:00 Europe/London ([see in your time zone](https://arewemeetingyet.com/London/2023-05-18/15:00))

**What?** 
*[SATRE (Standardised Architecture for Trusted Research Environments)](https://medium.com/satre) is a DARE UK Driver Project working to standardise access to secure data in trusted research environments. It includes University of Dundee, Alan Turing Institute, UCL, Ulster University, Research Data Scotland.*. 
[Collaboration Cafes](https://the-turing-way.netlify.app/community-handbook/coworking/coworking-collabcafe.html) are **online collaboration and coworking calls** for anyone interested in learning about, discussing and contributing to the project.

**Who?** 
***Anyone** interested in our project & the TRE space is welcome to join this call. No prior sign-ups needed!*

***All questions, comments, and recommendations are welcome!***

---

* 25+ attendees

## Breakout rooms: Topic proposals and notes

*While no sign-ups are required to attend Collaboration Cafe, if you have an idea for a topic you'd like to discuss in a breakout room, please add it below and put your name next to it. A good place to start to find discussion topics are on the [SATRE Specification Repo Issue Board](https://github.com/sa-tre/satre-specification/issues)*. If you're breakout room is discussing an Issue, we encourage you to write up any thoughts directly in the Issue thread.

* Main room: Survey Share-out
* Breakouts Rooms: 
    * Intro to project and GitHub repository
    * User engagement
    * IG: https://github.com/sa-tre/satre-specification/issues/69
    * Tiering: https://github.com/sa-tre/satre-specification/issues/68
    * TRE purpose and how overlaps and drives purpose and spec
    * 
    * 

### Break out notes

#### IG

- ... initial discussion not captured
- Focus on content of issue (68)
  - proposal - supporting different sensitivities is a requirement, preset configurations is an optional feature
- Mix of 'requirements' and 'ways to implement'. Tiering is an example of the later. The meaning of tiering is quite different for models where work is done in a ephemeral instance vs. a large persistent data store. What would be useful in the specification is example of Tiers, requirements and suggestions of how to achieve this rather than _specific_ requirements
- Tiers are likely to be very domain and context specific (risk appetite). Consider modifying data to meet research requirements rather than meeting controls to data.
- Feels like feeling of risk appetite and difference of appraoches across domains is being captured. Supporting different levels of sensitivity is fairly, but not universally popular, configurations less so.
- May be necessary to distinguish between privacy and security, what does sensitivity mean?

#### TRE Purpose

- how can make collaborative research speedy, efficient, low cost (in TREs)?
- Requires governance, infrastructure.
- Question. Is the purpose of TREs provide secure access to data or to enable research?
- TRE is an administrative system for IG, legal, Data sharing agreements etc.
- Data is not the difficult issue.



### Link List ✨ 
* Github issues: https://github.com/sa-tre/satre-specification/issues (50-69 are survey MCQ answers for discussion)
* The spec these will go into: https://satre-specification.readthedocs.io/en/latest/
* Glossary issue for anyone who wants to work on this: https://github.com/sa-tre/satre-team/issues/15
*

#### User engagement

5 attendees

Assistants are finding challenges in engaging with users and to work with them in setting up systems.

SATRE project will host two user engagement sessions next week:

* 24th May 11.30-13.00 BST & 26th May 14.00-15.30 BST 
* Agenda 
    * Introduction to TREs  
    * The SATRE project- activities and goals 
    * An open-source reference architecture 
    * Group discussion of users experiences 
    * How to engage with the reference architecture as a user 

Is it worth categorising users across types? create user personas?
* Technical, open to innovation users vs "pointed by the finger" who want to be guided and stay with what they know
* Some may assume this (a system) is not for them, yet we need to engage with them
* Provide plenty of materials in advance



## Agenda

| Time | Activity |
| ---- | -------- |
| **12.05 - 12.15** | Intro to SATRE and Survey Share-out (HS,JG) |
| **12.15 - 12.25** | (1st breakout session) |
| **12.25 - 12.30** | (☕️ Break) |
| **12.30 - 12.55** | (2nd breakout session) |
| 5 mins | :wave: Reflections and close |


### Notes

* Q: Will we look for patterns/clusters in the survey responses?
    * This is do-able for Likert responses
* Q: Even though survey responses came from a diverse population, could there be any bias i.e. lots of software engineers that result in a skewed specification. How do we deal with this?
    * Community consensus will be important to address this and define what we might be missing as the specfication takes shape.
    * Some responses were from an organization rather than indivduals - perhaps they should carry more weight?

### Different goals for TREs / how to decide what should be required vs optional (Room 4)

4 attendees

#### Purpose of TRE
- Support speedy, cost-effective, high quality research
- Best problems usually require most collaboration
- Collaboration requires ethical framework, legal framework, financial framework and associated collaboration infrastructure
- At Crick focus is on supporting collaboration, not using TRE just to allow access to certain datasets.
- At Turing similar, goal is to maximally support researchers in productive research with widest access to compute, analysis and collaboration tools, while keeping sensitive data secure enough.
- A TRE isn't just the underlying technology (or even primarily). It's the mechanism to support the chosen IG process, which will differ across different organisations, funders, ethics processes, data providers.
- Goal of SATRE is to align on common approaches where possible and identify commonalities and differences in IG and processes and technical mechanisms to support that.

### Feedback at the end of the call

* We will work on a way of capturing contributions for those not so familiar with GitHub
* HackMD is a barrier to entry
    * Google Docs is more familiar
        * But might struggle with lots of usage
        * 
* We could do with more time in the breakout rooms next time
* And we could provide scribes to capture HackMD notes
* Can we have e.g. a sprint version where every 2 weeks we release a version that people can comment on
* Can we have 10/15 minutes at the beginning to bring people up to speed with HackMD
* Or instructions we record and share out beforehand
    * We can do GH training for just engaging in the issues
* Is it worth starting with specific issues that we can get peoples thoughts on, e.g. bring specific issues we want community input on
    * Then have scribes/note taking for specific issues
* How to convert issues to PRs - how to encourage this? Are insisting on using forks best?