**When?** 
6th June 2023, 15:00 - 16:00 Europe/London ([see in your time zone](https://arewemeetingyet.com/London/YYYY-MM-DD/15:00))

**What?** 
*[SATRE (Standardised Architecture for Trusted Research Environments)](https://medium.com/satre) is a DARE UK Driver Project working to standardise access to secure data in trusted research environments. It includes University of Dundee, Alan Turing Institute, UCL, Ulster University, Research Data Scotland.*. 
[Collaboration Cafes](https://the-turing-way.netlify.app/community-handbook/coworking/coworking-collabcafe.html) are **online collaboration and coworking calls** for anyone interested in learning about, discussing and contributing to the project.

**Who?** 
***Anyone** interested in our project & the TRE space is welcome to join this call. No prior sign-ups needed!*

***All questions, comments, and recommendations are welcome!***

---

## Check-in and icebreaker 

**Name + Pronouns + Introductions + Location + Summer holiday plans + an emoji ([emoji cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md))**
*(Remember that this is a public document. You can use a pseudonym if you'd prefer.)* 

33+ attendees

## How to contribute to the project

Please read a walkthrough of the project and how to contribute: [Walkthrough Doc on GitHub](https://github.com/sa-tre/satre-specification/blob/main/docs/Walkthrough.md) or [Google Doc Version](https://docs.google.com/document/d/1zAWxubPWxukDN8WKIXe89uhJitSaicp5/edit?usp=sharing&ouid=105089893876648516018&rtpof=true&sd=true)

## Today's theme: Information Governance

Today we welcome discussions on Information Governance in TREs and have have pre-set a breakout room for this. If you have experience in this area we encourage you to join the breakout room. If you would like to work on something else, please feel free to propose your own breakout room topic at the beginning of the call.

## Breakout rooms: Topic proposals and notes

*While no sign-ups are required to attend Collaboration Cafe, if you have an idea for a topic you'd like to discuss in a breakout room, please add it below and put your name next to it. A good place to start to find discussion topics are on the [SATRE Specification GitHub Repository Issue Board](https://github.com/sa-tre/satre-specification/issues).*

* Main room: General help with getting involved with SATRE and Collab Cafe (HS on Tuesdays, AL on Thursdays)
* Breakouts:
    * **Today's Theme:** Information Governance
    * Reviewing capability-based, draft standard sections
    * X
    * X

### 1.1 Compliance, monitoring and reporting Room 1)
-- much of this will go in the guidance part that will help people make sense of the statements

- 5 attendees
- All of these are mandatory - is that strictly needed?
    - At this level probably, but as we go down levels maybe that shifts
- These are all broad - 
- Things that aren't there
- regular review/audit of documents, people, roles, technology itself, process
    - e.g. we got audited by NHS Digital a few years ago, issues of roles and people moving on, version control...
    - this is relevant under 1.3 also
    - part of this is ensuring things like DSPT are up to date prior to audits
- roles and responsibilities
    - Real people need to be asigned to actually take the responsibilities on. e.g. pre audits

#### add to 1.6 points 
- Mandatory annual training = some places are every three years. Is every one year really needed?
    - general cyber security is every year
    - small value suppression for instance doesn't need to be annual, or the training burdens are too high to be annual
    - You want everyone to do the training relevant to their role as often as agreed. And a way of tracking that training. 
    - OR is it training that is needed or assessment of capabilities/skills/knowledge
    - how do we enable short term workers to come in easily. e.g. via researcher accreditation apporach, or even at a not so grand level - do a test. 
    - Prove competency every 12 months for instance. **Suggest this as change**


#### add  to other sections
- compliance
    - you are able to audit that you're complanint with data provider agreements...
    - something about a DPIA data controller relationship - (related to managing external relationships)
- Policy regulation and management
    - proces and policy in place to respond to requirements 

- Who is **you**?
    - people implementing the TRE?
    - Can we be more explicit
    - risk is differently understood and is a different kind of motivator throughout organisations
    - defining roles is important here. 

- Why can't we have Python (or other apps/packages etc.)
    - e.g. in some Scotland TREs it's not allowed. But it is in many other TREs
    - Who decideces, audits needs 
    - maybe we have to say something under risk management
    - Acknowledge balance of control vs bringing in more users / useability
    - Put this into risk assessment or guidance
        - "ensure you consider the risk of removing functionality that pushes people outside of the environment - e.g. rebound effects"

### 1.2 Policy regulation and management
- Duplication of existing standards?
    - Not intended to replace adherence to standards
- What are you assessing?
    - Add some better examples
- Don't be prescriptive
- Expectations around availability/use of data
- Obligations to data controllers/subjects: how to decide appropriate access controls
- What data is being accessed?
- Policy for onboarding data:
    - You have a process in place to assess the legal and regulatory implications of handling the data through its full lifecycle.
    - What security controls are necessary?
    - data classification, tiering
    - risk based approach to access
    - how far do you take the assessment?
    - Organisational compliance with GDPR?


### 1.3 Quality management
- 5 attendees
- Is there a general section on change management? E.g. software, how it changes to the infratstructure itself
- IG mean different things to different people, so need to define what is & isn't in scope. Would also expect to see change management in here - e.g. if software needs change, who should be involved?
- Might be handy to include policy/procedural reviews
- Most people in ISO27001 already have those checks, need to be careful to not repeat processes. Be careful that we're not checking TREs for something they're already checked for.
- Is there space to have a separate TRE accreditation, or are all these other accreditations okay for TREs
    - It's not SATRE's job to do that, it may be DARE UK's job to do that. DARE's favourite is DEA, or the NHS SNSDEs, trying to bring this all together. Everyone wants to move towards it, quite what that will be remains to be seen
- Accreditations have a place to show you are doing things to an accepted standard
- Wants to map out the IG parts to an organisational model, to see who's responsibile for what, what people are doing, what's missing
    - Agrees. Is it in DARE's gift to come up with some kind of accreditation, given that data controllers have lots of different requirements. All these efforts are necessary but not yet sufficient
- Change control would need to be there. Other parts that aren't covered - assets management. How are you managing the data you are storing on TRE, the users, the projects. Quality management should include e.g. asset register. I would like to see instructions for how to set up a TRE effectively.
- There is a general change control process that you would deploy to manage the documents that you have. This starts with an asset register. 
    - Any aspect of change you would one a change management process that governs it
- Output management should be included in 1.3, applying Statistical Disclosure Control
    - Need something specific on outputs
- DPIAs not responsibility of the TRE, they happen separately - so more 'check one has been done' is the TRE responsibility. Wording needs to be pretty broad and need to give examples. E.g. for algorithms we would expect there to be a DPIA and an Algorithm Impact Assessment. Maybe it needs to be worded that the data controllers are satisfied that all technological controls are in place for the project to proceed. This perhaps depends on the levels involved with regard to who instructs who (eg of EDRIS and EPCC)
- There perhaps needs to be teased out something about the roles and the levels of TRE oversight
- Does the title quality management capture it. Without the organisational view too is not easy to input fully at this stage. 
- Defining the roles including who is doing what and chain of organisation is important for following in case of audits or issues 

### 1.4 Risk management
- Focussed on risk management within a TRE
    - Should it include member accreditation?
    - What kind of risks are intended to be covered? What's the scope? e.g. data curation, use of data in proejcts? Or more a security specification?
- Example from existing TRE: Assets, classified threats, vulnerabilities, impact of compromise.
    - All related to data within the TRE
    - Threats to do with breaches of data
    - Significantly narrower than above
- Lot's of governance issues are outside TRE, risks are one fo the things that can be inside
    - What about risks like leaving laptops on train? Obviously outside of scope
- Some sort of risk management setup, but doesn't indicate how mature setup is. Back to what's the scope?
    - Documented on university pages, but quickly links out to other areas
    - Should be linked to quality management and compliance sections
- Point of spec: is it to facilitate a risk management process?
    - Lot of hoops when completing risk assessment e.g. asset grouping, impacts of compromise, likelihood, whether you're comfortable with final risk level
    - Is purpose of 1.4 in the spec to facilitate that process?
    - Most people currently figure it out themselves. The spec should facilitate this.
    - If a reference implementation complies with the SATRE spec, does it mean a lot of the risk assessment is automatically done?
    - Automatically populate a risk matrix
- Document should provide guidance on how to do those things, rather than working it out yourself
    - Someone new to risk amangement might not know where to start
    - Agree everything on list is required
    - Most TREs will have external compliance requirement, where how to do it will be encapsulated in those other documents
- Currently talks about what the organisation running the TRE has to do
    - So wouldn't create the populated risk matrix
- Can an implementation (i.e. code-base) be accrediated, so that there's less work to accredit the deployed TRE?
    - Currently all done by humans
    - E.g. If standard says "monitor all logins" then if reference and implementation comply that requirement is already fulfilled
- https://github.com/sa-tre/satre-specification/issues/74
- Guidance on how to do things E.g. "You have a way to score risk"
    - Be more specific? Is it a comprehensive automated risk matrix that can be automatically monitored by code? Or is it a person who updates spreadsheet every month?
    - Examples of how other institutions have done it
    - Would like to encourage more automated compliance
- Need more text indicating that the "risk management" section ties in with other sections, make it clear that e.g. compliance is a separate section
    - Some text at the start of the doc saying what each section covers
- If this specification covers the deployment/organisation (and not or in addition to the implementation) what value does this spec bring? Why not just go straight to ISO27001 controls to know how to manage risk?
    - Value is this is what you have to put in place to run the TRE. May not be useful for and ISO27001 accredited organisation, but useful for new organisations to know where to start.



### 1.5 Project management

- 4 attendees
- No detail (yet) on data lifecycle, source, consent, ethics approval, data sharing agreements _etc._
- Ownership of outputs, processed data assets
  - Both of those items are somewhat covered in "Data management". Unclear now how these areas relate to eachother. Technical vs policy?
  - Separating technical and policy is risky. It is not technical controls that form the basis for compliance with standards/regulations.
- It could make sense to separate requirements into sections. How fixed are the current sections?
  -  Not set in stone. Can be rearranged however makes sense. Split into sections for readability, to allow referencing and cross-referencing.
- At HIC data team have checklists which ensure processess are followed, steps cannot be skipped. Infrastructure team setup/manage environments. May have to implement bespoke data security requirements (e.g. access control) for a project. Would be helpful for requirements to be 'encoded' for infrastructure team, this is different to requirements like data sharing agreements _etc._. **Help to check that the technical implementation can meet the requirements**.
- Turing for example could match a project with different levels of risk to the highest of the risks.
- Project onboarding guidance - mixing the responsibilities of different roles. _E.g._ infrastructure team only need to know whether they should create infrastructure of not. They don't need to know the details that the data team may do.
- Missing details about what happens between set up and shut down. Archiving, long term data.
  - Should be covered in data lifecycle. My feeling is this is difficult to standardise across different shapes of TREs. _E.g._ ephemeral TREs where the TRE operator does not want to curate data sets or hold long-term archive data, relationship with data provider may not allow this.
- Lack of version control within environments making work and producing outputs difficult. Can a requirement be part of IG.
  - PICTURES working on code ingress process - develop outside, bring code to data (one way). Much easier to work this way than developing inside and bringing code out. 
- Reproducibility - preservation of data (or preparation), analysis pipeline. Auditing, capturing of environment.
- Definition of project team roles - TRE users not admins. _E.g._ analysts read/write, PI read only.
  - May be information security. ISO27001, RBAC.
- Current structure not aligned with five safes. In general, grouping is odd and makes document hard to understand.
  - Should try to follow up on this :point_up: 

### 1.6 Member accreditation

- 5 attendees
- Information Governance is this covering data items, some categories may be more about output.
- Whole gamut, everything to do with data and information related to project.
- What are the different roles
- Roles are covered in section 6
- Are different people able to be different roles, are you able to distinguish between their activities.
- If single person has different roles, you would expec them to have different training for each role and have different access for each.
- What is I have different organisational membership.
- Missing aspect, there need to be checks on people accessing TRE
- Need to have checks and criteria Identity and Verification Checks on anyone accessing the TRE. University accounts to be used to have access. Are they bona fide researchers?
- And that needs to link back to the persons host organisation.
- Ability to do discovery to define the project they want to run. Prior to obtaining ethical approval.
- Needs to connect to a prior approved entity. Financial, legal and ethical approval.
- Are researchers active members, do we checkout inactive members?
- Are members offboarded e.g. project only lasts 6 months.
- People may move on and off project, new members starting. If they're the only member involved in the chain of custody. What happens if they leave. Where does accountability lie.
- Is the 12 month statement about re-training count as active, part of the criteria for offboarding
- Certainly needs to be part of the process. Person's role will determine the training. What they can and can't do in their role. Should also be signing an agreement.
- Potentially split into two elements. If person is affiliated to an org they take that training in the organisation separately. Specific for the particular role and platform.
- Needs to have specific training and separate out operations you expect other parts of the org to do
- Matters to revisit:
  - Needs Identity verification (here or elsewhere) this is prior to being able to identify accredited members.
  - Record of members signing agreement to their commitment on usage.
  - Needs offboarding process (automatically?)
  - Needs chain of responsibility so secure ownership on leavers.
  - Relevant training could split into core e.g. institutional Cyber/GDPR training and specific training for role in specific TRE.
  - Clarity around how persons with different roles will action different activities.

### Wrap up

- Room 1 
- Room 2, Onboarding data and what is needed, seems to be out of the scope of current version so will need including in next versions
- Room 3: Organizational and responsibility mapping
- Room 4: which is the scope of risk management wihtihn this specification, does complying wiht this spec automatically mean that a big chunk of risk matrixes are filled? (would massively help IG folk)
- Room 5: lots of discussion on project management and what that should cover, what is IG and what is the other. Reproducibility, how to ensure that work done is up to standard and reproducible
- Room 6: defining roles vs people and the overlap, more clarity on language in the spec please, adding a declaration or agreement that someone would go through to onboard projects; and actually hot to off board.

- Feedback on this session
- Contribute!
- Next session - Thurs 15th June
    - PPIE engagement in collaboration Cafes

- Structure of categories. Room 2 talked about maybe another category popping up, room 3 talked about new IG process coming up. Why are we breaking up & categorising the elements of a standard architecture for TREs in this way. People generally talk about the TREs as 5 safes. Might just be easier to converse with a broader audience to map e.g. technical solutions onto the 5 safes. 
    - All the guidance docs etc. are very good and say the right things, difficulty is they don't have structure. E.g. 5 safes is great, but does it help you fill in the middle bit of what you want to achieve and why. 5 safes fit at the principles level, cut across all the design decisions that you could make. E.g. when we talk about federation, we should use the paper that's gone into draft. X has been trying to build up a structure on which we can then hang on all the previous good work that has been done. 
- Risk for SATRE project boil the ocean. Big ask to do the governance & the technical, if we focus on the technical being influenced by the governance that is ok.
    - Principle of JIT architectural design, which is difficult here. If you want to buy a TRE in a box and switch it on, you need some IG requirements.
- Document is going very wide. A standard TRE, if built open source, with any decisions as options for users, the governance can be managed under those options. Everything can then be a discussion point, approaching it from a more product creation standpoint. Anything we're not sure about can be a dropdown/option depending on e.g. 5 safes.
- Can SATRE focus on safe setting, and do a broad coverage of other safe principles





### Link List ✨ 
* Capability-based standard PRs [data management](https://github.com/sa-tre/satre-specification/pull/84) [IG](https://github.com/sa-tre/satre-specification/pull/86)
*
* 
