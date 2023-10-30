# Usability and implementation

**When?**
18th July 2023, 15:00 - 16:00 Europe/London ([see in your time zone](https://arewemeetingyet.com/London/2023-07-18/15:00))

**What?**
_[SATRE (Standardised Architecture for Trusted Research Environments)](https://medium.com/satre) is a DARE UK Driver Project working to standardise access to secure data in trusted research environments. It includes University of Dundee, Alan Turing Institute, UCL, Ulster University, Research Data Scotland._.
[Collaboration Cafes](https://the-turing-way.netlify.app/community-handbook/coworking/coworking-collabcafe.html) are **online collaboration and coworking calls** for anyone interested in learning about, discussing and contributing to the project.

**Who?**
_Anyone_ interested in our project & the TRE space is welcome to join this call. No prior sign-ups needed!

**_All questions, comments, and recommendations are welcome!_**

---

## Check-in and icebreaker

14 attendees added their names

## How to contribute to the project

Please read a [walkthrough of the project and how to contribute](https://satre-specification.readthedocs.io/en/latest/contributing/walkthrough.html)

## Today's theme: Usability and implementation

We’ll be discussing what how the specification needs to be written, and what else needs to be in place, for your organisations to consider adopting it.

This will include asking questions like:

- Does the current structure and content feel like the right approach?
- What organisational buy-in would we have to have for you to trust it/want to use it?
- What would it need to align with (e.g. ISO, DSPT, Goldacre Report etc.)
- What barriers would there be to you making your TRE SATRE aligned?

## Breakout rooms: Topic proposals and notes

_While no sign-ups are required to attend Collaboration Cafe, if you have an idea for a topic you'd like to discuss in a breakout room, please add it below and put your name next to it. A good place to start to find discussion topics are on the [SATRE Specification GitHub Repository Issue Board](https://github.com/sa-tre/satre-specification/issues)._

Possible questions for today:

- Does the current structure and content feel like the right approach?
- What organisational buy-in would we have to have for you to trust it/want to use it?
- What would it need to align with (e.g. ISO, DSPT, Goldacre Report etc.)
- What barriers would there be to you making your TRE SATRE aligned?

* Main room: General help with getting involved with SATRE and Collab Cafe (HS on Tuesdays, AL on Thursdays)
* Breakouts:
  - **Today's Theme:** Usability and implementation

### Notes

#### Main room discussion

- What do you need to put a TRE in place?
  - Staff, information governance, technical requirements
  - There is also a need for them to comply with GDPR, show safe data management practice

#### Breakout room 1

6 attendees

Notes:

- On a first look feels like a good set of best practices' nice to have, potential overlap but also complement existing acreditation (ISO). It can become detail not in the accreditation, or become superseeded.

  - The scope at this point is guidance, and it being a community led effort. with the aim that it will be picked up and continued
  - This looks like good community input into an accreditation, worth whether or not that happens

- Would be useful if list of statement would be numbered and classified by mandatory or not

- How specific are you going to be?

- "You must carry out a data processing assessment for all projects requiring a TRE that are working with sensitive data."

  - Requirement should be on the project not the TRE operators
  - You could frame recommended as 'advisory'
  - do check the rest of the wording in these lines

- Some things in the specification seem obvious,

  - This is good, and they should be. the aim is to put them together as they currently are in bits across many docs, policies, reports...

- SDE and TRE as distinct things.

  - What is the difference?
  - TRE is environment that data comes into, SDE is wider: includes relationship with data provider

- What can we do to ensure that the sub-national SDEs at least are aware of SATRE as possible before they get building, so they can use it for guidance, should they want to?

  - Come back to NHS with v1.0

- What organisational buy-in would we have to have for you to trust it/want to use it?
  - A challenge we face is demonstrating our TRE meets best practice, could we find a way to ensure that if a TRE meets SATRE esp, that is enough to demonstrate compliance with other accreditations? SATRE to allow us to navigate the forms/requirements
  - NHS cloud controls that aren't relevant
  - Talk to [DARS](https://digital.nhs.uk/services/data-access-request-service-dars)
  - DSPT

#### Breakout room 2

8 attendees

Notes

- Does the current structure and content feel like the right approach?
- What organisational buy-in would we have to have for you to trust it/want to use it?
- What would it need to align with (e.g. ISO, DSPT, Goldacre Report etc.)
  - NHS sub group meeting last week on a similar topic. Group aware SATRE exists, members keen to make sure SATRE aligns with DSPT.
  - All three. Want to reduce the number of standards. Identify overlap, for example, if you have ISO27001 a number of the DSPT requirements are automatically accounted for.
  - Uncertainty about how SDEs will look. Implication that TREs outside of NHS will not be allowed to handle NHS data.
  - Reducing the number of independent schemes you have to comply with will help. Working through one list is better than ten.
  - Desire for some boilerplate for a TRE with specific suggestions. E.g. "Here is what you need to do, for this requirement there are these four options we can recommend".
    Reduces time required. Focuses people on the important points of what they need and need to do.
  - The product (of the current phase) will not be a formal standard. Is a best practice guide (or something similar) useful?
    - Will tend to be ignored if it is not forceful (you must do this). For example, Goldacre report has been read but does not force action.
    - What would make you feel like you have to comply?
    - You need DSPT for using NHS data, that is mandatory.
      Researchers will therefore 'demand' this.
      Operational must-haves are compelling
      Good alignment with, for example, ISO27001 would make SATRE more attractive.
      "My driving license lets me drive any model of car"
    - If SATRE was well aligned, would you be interested in also getting SATRE as an additional achievement?
      - ISO27001 isn't _for_ research. The fact that SATRE is geared for particular research is a strength.
        We have ISO27001 for our DSH, having SATRE as a badge of standard for this type of research would be good, reassuring for researchers.
  - Regarding idea of recommendations not just requirements. SATRE is also aiming to build TRE implementations which comply with SATRE (TREEHOOSE, Turing DSH, ...). Would this be useful? One reference implementation, many?
    - It seems useful.
      Aware of TREEHOOSE without having used it.
  - Some accreditations apply to the (technical) solution.
    Reference implementations would cover this, make this easy to 'copy'.
    There are also business processes/controls etc. Should SATRE also cover these things?
    - It is all important and interdependent.
      Anything which make implementation easier is good.
    - Not if it is redundant, i.e. repeating what is in another standard.
      Like above, if there was a mapping to other standards this would help, but with understanding _and_ implementation.
    - Going back to car analogy.
      There is a danger that users see a compliant reference implementation as assumes that is all they need to run a safe environment without thinking about "road quality, M.O.T, etc."
      There are things a technical implementation cannot provide
    - Agreed.
      Still, reducing number of certifications is important. Saves time, improves clarity.
  - What other certifications? Are the existing certifications actually compatible?
    - Not sure.
    - Would require its own audit to know.
    - ISO27001 and DSPT are the two obvious ones.
      Goldacre report is promenant, but recommendations are yet to be implemented as laws/standards
    - Also [digital Economy Act (DEA)](https://www.gov.uk/government/collections/digital-economy-bill-2016)
    - DEA mentioned, not very familiar.
      [Caldicott](https://www.gov.uk/government/publications/the-caldicott-principles) - set of principles implemented by DSPT (completely compatible)
    - One key differentiator in requirements is that SDEs are intended to overcome internal data siloing. An aspect of this is sharing e.g. clinical data within an organisation so that there is better visibility and access. In some ways this is counter to the aims of a TRE where researchers are restricted to the data that they are allowed to access.
- What barriers would there be to you making your TRE SATRE aligned?

### Wrap up

- Future topics
  - Quite technical - how a TRE is constituted
  - The TRE used to be defined as the analytical platform/the area where data is accessed, rather than the data warehouse, etc. Not sure if that will change?
  - What will SDEs be, how will we work with them
  - Further work on glossary
- Room 2
  - Focus on standards
  - Don't want just another standard
  - being compatible with ISO is very important
    - Would be great if SATRE could say "If you have ISO, you already meet requirements x, y, z"
  - Goldacre report is influential, but it is guidance/recommendations not requirements
  - Should also consider Caldicott Principles and Digital Economy Act
- Team wrap up
  - We should get governance people in our orgs to go through accreditations and see what aligns with SATRE, eventually to create a mapping both ways - if you have ISO27001/DSPT here's what you already do, here's what you need to do additionally, _and bidirectionally_ if you have SATRE, you already fulfil these requirements for ISO/DSPT
  - PIE - we should think about the public question of 'when is a TRE relevant', was a question that came up from the public a few times
    - We should make it more explicit that the SATRE specification is telling you what a TRE is - e.g. put it on the home page. Think about the wording we put there. Maybe more 'this is a way of explaining what a TRE does and why it's importance'.
- Total participants: 22

## Agenda

| Time    | Activity                                    |
| ------- | ------------------------------------------- |
| 10 mins | Introductions and breakout room suggestions |
| 20 mins | (1st breakout session)                      |
| 5 mins  | (☕️ Break)                                  |
| 20 mins | (2nd breakout session)                      |
| 5 mins  | :wave: Reflections and close                |
