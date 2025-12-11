# OctoAcme — Communication Best Practices

## Purpose
Establish clear guidelines and best practices for effective communication across project teams to ensure alignment, transparency, and efficient information flow.

## Core Communication Principles

### 1. Clarity
- Use clear, concise language
- Avoid jargon unless your audience is familiar with it
- State the purpose upfront
- Include context when necessary
- Specify action items and owners explicitly

### 2. Timeliness
- Respond to messages within expected timeframes (see cadence guidelines)
- Share updates proactively before stakeholders need to ask
- Escalate issues early rather than waiting
- Use asynchronous communication for non-urgent items

### 3. Transparency
- Share both good news and challenges
- Provide visibility into decision-making processes
- Document decisions and rationale
- Make information accessible to those who need it

### 4. Consistency
- Use established templates and formats
- Follow regular communication cadences
- Maintain a single source of truth for status
- Apply the same communication standards across the team

### 5. Inclusivity
- Consider who needs to be informed vs. consulted
- Accommodate different communication preferences when possible
- Use accessible formats (clear language, alt text for images)
- Ensure remote and distributed team members are included

---

## Communication Channels & When to Use Them

### Real-Time / Synchronous

#### Meetings
**Best for:**
- Complex discussions requiring back-and-forth
- Decision-making requiring multiple perspectives
- Sensitive topics needing nuance
- Building relationships and team cohesion

**Best practices:**
- Always have an agenda shared in advance
- Start and end on time
- Assign a facilitator and note-taker
- Share meeting notes within 24 hours
- Record when appropriate (with consent)
- Use video when possible for better engagement

#### Chat/Instant Messaging
**Best for:**
- Quick questions with simple answers
- Time-sensitive coordination
- Informal team communication
- Quick status checks

**Best practices:**
- Respect focus time and off-hours
- Use threads to keep conversations organized
- Set expectations for response times
- Avoid sensitive or complex discussions
- Use @mentions thoughtfully

### Asynchronous

#### Email
**Best for:**
- Formal communications and announcements
- External stakeholder communication
- Information that needs a paper trail
- Distribution to large groups

**Best practices:**
- Use clear, descriptive subject lines
- Put the most important information first
- Use bullet points for readability
- Clearly state any action items and deadlines
- Consider "TLDR" summaries for long emails
- Reply-all only when necessary

#### Documentation (Wiki, README, Docs)
**Best for:**
- Permanent reference information
- Process documentation
- Decision records
- Onboarding materials

**Best practices:**
- Keep documentation up to date
- Use consistent formatting and templates
- Include last-updated date and owner
- Link related documents
- Make it easily searchable
- Review and archive outdated content

#### Project Boards & Issue Trackers
**Best for:**
- Work item status and progress
- Bug and feature tracking
- Task assignment and ownership
- Team workflow visibility

**Best practices:**
- Keep status current (update within 1 business day)
- Use clear, descriptive titles
- Include acceptance criteria and context
- Link related issues and PRs
- Use labels and milestones consistently
- Update stakeholders on significant changes

---

## Communication Cadence by Role

### Daily Communication
**Who**: Development team, Team Leads, QA/Testing  
**Format**: Standup meeting or async update  
**Duration**: 15 minutes maximum  
**Content**:
- Progress since last standup
- Plans for today
- Blockers or dependencies
- Help needed

### Weekly Communication

#### Project Status Update
**Who**: Project Manager → Stakeholders  
**Format**: Written report with optional discussion  
**Content**:
- Progress this week
- Upcoming milestones
- Risks and blockers
- Decisions needed

**Template**: See [Risk Management & Communication](octoacme-risks-and-communication.md)

#### PM + PdM Sync
**Who**: Project Manager + Product Manager  
**Format**: Meeting (30-60 minutes)  
**Content**:
- Scope and priority alignment
- Risk review
- Dependency updates
- Upcoming decisions

#### Metrics Report
**Who**: Metrics Analyst → Project Manager, Team Leads, stakeholders  
**Format**: Written report (see [Metric Reporting Template](metric-reporting-template.md))  
**Content**:
- Key performance indicators
- Velocity and progress
- Quality metrics
- Risk indicators

#### Internal Team Update
**Who**: Internal Communications Manager → All team members  
**Format**: Newsletter or digest  
**Content**:
- Team highlights and wins
- Important decisions
- Process updates
- Upcoming events

### Bi-weekly Communication

#### Stakeholder Updates
**Who**: External Stakeholder Liaison → External stakeholders  
**Format**: Meeting with status update  
**Content**:
- Feature demos
- Progress update
- Upcoming deliverables
- Feedback collection

### Monthly Communication

#### Leadership Update
**Who**: Product Manager / Project Manager → Leadership  
**Format**: Slide deck or written report  
**Content**:
- Monthly achievements
- Metric trends
- Strategic risks
- Resource needs

### As-Needed Communication

#### Escalations
**Who**: Any role → Next level in escalation path  
**Format**: Immediate notification via appropriate channel  
**When**:
- Blocker requiring higher-level decision
- Risk becoming critical
- Scope or timeline change needed
- Security incident

#### Incident Communications
**Who**: Incident commander → Stakeholders  
**Format**: See [Risk Management & Communication](octoacme-risks-and-communication.md)  
**When**: During and after incidents

---

## Communication Templates

### Decision Record Template
```markdown
## Decision: [Brief title]

**Date**: [YYYY-MM-DD]  
**Decision Maker**: [Name/Role]  
**Consulted**: [List of people/roles consulted]  
**Informed**: [List of people/roles informed]

### Context
[What decision needed to be made and why]

### Options Considered
1. **Option 1**: [Description]
   - Pros: [List]
   - Cons: [List]
2. **Option 2**: [Description]
   - Pros: [List]
   - Cons: [List]

### Decision
[What was decided]

### Rationale
[Why this option was chosen]

### Consequences
[Expected outcomes and any trade-offs]

### Action Items
- [ ] [Action 1 - Owner]
- [ ] [Action 2 - Owner]
```

### Announcement Template
```markdown
## [Announcement Title]

**Date**: [YYYY-MM-DD]  
**From**: [Name/Role]  
**Priority**: [High / Medium / Low]

### Summary
[One-sentence summary of the announcement]

### Details
[Full explanation of what is being announced]

### Impact
[Who is affected and how]

### Action Required
[What people need to do, if anything]
- [ ] [Action 1 - Audience - Deadline]
- [ ] [Action 2 - Audience - Deadline]

### Timeline
[When changes take effect]

### Questions?
[How to get more information or ask questions]
```

### Update/Status Email Template
```markdown
Subject: [Project Name] Status Update - [Date]

**Project Health**: 🟢 Green / 🟡 Yellow / 🔴 Red

## Progress This Week
- [Accomplishment 1]
- [Accomplishment 2]
- [Accomplishment 3]

## Next Week Plans
- [Plan 1]
- [Plan 2]
- [Plan 3]

## Risks & Blockers
- [Risk/blocker 1 - Status - Owner]
- [Risk/blocker 2 - Status - Owner]

## Decisions Needed
- [Decision 1 - Decision maker - Deadline]
- [Decision 2 - Decision maker - Deadline]

## Upcoming Milestones
- [Milestone 1 - Date]
- [Milestone 2 - Date]

## Questions or concerns?
[Contact information]
```

---

## Meeting Best Practices

### Before the Meeting

#### Agenda Creation
- [ ] Create agenda at least 24 hours before meeting
- [ ] Share agenda with all participants
- [ ] Include time allocations for each topic
- [ ] List decision items separately from discussion items
- [ ] Share any pre-reading materials

#### Invitation Management
- [ ] Only invite people who need to be there
- [ ] Distinguish required vs. optional attendees
- [ ] Include meeting objective in description
- [ ] Attach or link to agenda
- [ ] Consider time zones for distributed teams

### During the Meeting

#### Facilitation
- [ ] Start on time (wait max 2 minutes)
- [ ] Review agenda and objective at start
- [ ] Assign note-taker at beginning
- [ ] Keep discussion on track
- [ ] Use a parking lot for off-topic items
- [ ] Manage time for each agenda item
- [ ] Summarize decisions and action items
- [ ] End on time

#### Participation
- [ ] Join video meetings with camera on when possible
- [ ] Mute when not speaking
- [ ] Use hand-raise features in large meetings
- [ ] Contribute constructively
- [ ] Be present (avoid multitasking)
- [ ] Take your own notes on action items

### After the Meeting

#### Notes & Follow-up
- [ ] Publish notes within 24 hours
- [ ] Include attendees, decisions made, action items
- [ ] Share notes with all participants (and appropriate others)
- [ ] Create or update issues for action items
- [ ] Send calendar invites for any follow-up meetings
- [ ] Update relevant documentation with decisions

---

## Written Communication Best Practices

### Structure
- **Lead with the main point**: Don't bury the lede
- **Use headings**: Break up long communications
- **Bullet points**: Easier to scan than paragraphs
- **Highlight action items**: Make them visually distinct
- **Link, don't duplicate**: Reference existing docs rather than copying

### Tone
- **Professional but approachable**: Match your audience
- **Positive framing**: Focus on solutions, not just problems
- **Objective language**: Stick to facts for status updates
- **Empathetic**: Consider the reader's perspective

### Clarity
- **Be specific**: "By Friday" instead of "soon"
- **Define acronyms**: First use should spell it out
- **Avoid ambiguity**: "Team A will handle X" not "they will handle it"
- **One topic per message**: Don't mix unrelated subjects

---

## Special Communication Scenarios

### Communicating Bad News
1. **State the issue clearly upfront** - Don't hide it
2. **Provide context** - What happened and why
3. **Explain the impact** - Who is affected and how
4. **Present the plan** - What's being done about it
5. **Set expectations** - Timeline for resolution or next update
6. **Take responsibility** - Avoid blame, focus on solutions

### Communicating Across Time Zones
- Use UTC or specify time zones explicitly
- Record important meetings for those who can't attend live
- Rotate meeting times to share inconvenience
- Use async communication when possible
- Be patient with response times
- Create documentation for missed synchronous conversations

### Communicating Up (to Leadership)
- Be concise and respect their time
- Lead with the bottom line
- Provide options, not just problems
- Quantify impact when possible
- Be prepared with answers to likely questions
- Follow up in writing after verbal discussions

### Communicating During Crisis
- Communicate frequently, even if "no new updates"
- Use multiple channels to ensure reach
- Designate a single source of truth
- Separate internal and external communications
- Focus on facts, not speculation
- Provide clear actions or next steps

---

## Communication Health Indicators

### Good Signs ✅
- Team members feel informed and aligned
- Decisions are documented and accessible
- Stakeholders know where to find information
- Meetings are productive with clear outcomes
- Questions get answered in a timely manner
- Remote team members feel included

### Warning Signs ⚠️
- Same questions being asked repeatedly
- People surprised by decisions or changes
- Information only travels verbally
- Key discussions happening in side channels
- Meeting action items not getting completed
- Stakeholders feeling out of the loop

### Improvement Actions
- Survey team on communication effectiveness quarterly
- Review and update communication practices in retrospectives
- Audit documentation for outdated content
- Analyze meeting effectiveness (post-meeting feedback)
- Track communication metrics (response times, meeting effectiveness)

---

## Checklist for Communication Planning

When planning important communications, consider:

- [ ] **Who needs this information?** (Identify all audiences)
- [ ] **What do they need to know?** (Tailor content to audience)
- [ ] **Why does it matter to them?** (Make relevance clear)
- [ ] **When do they need to know?** (Timing and urgency)
- [ ] **How should it be communicated?** (Best channel)
- [ ] **What action is required?** (Be explicit)
- [ ] **Who is responsible for follow-up?** (Assign ownership)
- [ ] **How will we know it was effective?** (Success criteria)

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md) - Communication responsibilities by role
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Communication templates
- [Stakeholder Feedback Process](stakeholder-feedback-process.md) - External communication guidance
- [Metric Reporting Template](metric-reporting-template.md) - Metrics communication format
