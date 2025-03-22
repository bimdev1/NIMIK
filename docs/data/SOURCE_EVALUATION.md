# Data Source Evaluation Process

This document outlines the process for evaluating potential data sources for NIMIK.

## Evaluation Workflow

### 1. Initial Submission
- Source is submitted via issue template
- Automatically labeled as "data-source" and "needs-evaluation"
- Added to project board in "Evaluation Queue" column

### 2. Initial Screening
- Verify completeness of submission
- Check for duplicate sources
- Confirm basic cultural safety requirements
- Move to "Initial Review" column

### 3. Detailed Evaluation
Sources are evaluated across five key dimensions:

#### Data Sovereignty
- [ ] Respects tribal data ownership
- [ ] Follows tribal protocols
- [ ] Has appropriate permissions
- [ ] Supports community control

#### Cultural Safety
- [ ] Uses appropriate terminology
- [ ] Follows trauma-informed practices
- [ ] Respects cultural protocols
- [ ] Protects sensitive information

#### Data Quality
- [ ] Regular updates
- [ ] Verification processes
- [ ] Data completeness
- [ ] Error correction procedures

#### Access Requirements
- [ ] Clear access protocols
- [ ] Appropriate restrictions
- [ ] Documentation available
- [ ] Technical feasibility

#### Community Impact
- [ ] Benefits to communities
- [ ] Potential risks
- [ ] Resource requirements
- [ ] Long-term sustainability

### 4. Status Assignment

Based on evaluation, sources are assigned one of four statuses:

**Confirmed Viable** [x]
- Meets all critical criteria
- Has clear access path
- Ready for integration

**Under Evaluation** [ ]
- Initial review positive
- Needs more investigation
- Actively being assessed

**Needs More Research** [?]
- Insufficient information
- Pending responses
- Unclear status

**Not Viable** [-]
- Does not meet criteria
- Access not possible
- Ethical concerns

### 5. Documentation

For each evaluated source:
1. Update status in POTENTIAL_SOURCES.md
2. Document findings in issue
3. Add relevant labels
4. Move to appropriate project column

## Project Board Structure

### Columns
1. **Evaluation Queue**
   - New submissions
   - Awaiting initial review

2. **Initial Review**
   - Basic screening
   - Preliminary assessment

3. **In-Depth Evaluation**
   - Detailed analysis
   - Community consultation

4. **Pending Information**
   - Awaiting responses
   - Need more details

5. **Decision Made**
   - Final status assigned
   - Documentation complete

### Labels
- `data-source`: Base label for all sources
- `needs-evaluation`: Awaiting initial review
- `in-progress`: Currently being evaluated
- `needs-info`: Requires additional information
- `confirmed-viable`: Approved for integration
- `not-viable`: Determined unsuitable
- `high-priority`: Critical for project success

## Community Input

We actively seek community input during evaluation:
- Comment on source issues
- Provide additional context
- Share experiences
- Raise concerns

## Updating Status

To update a source's status:
1. Edit POTENTIAL_SOURCES.md
2. Update issue labels
3. Move card on project board
4. Document reasoning

## Security Considerations

When evaluating sources:
- Never share private credentials
- Respect access restrictions
- Document only public information
- Follow security protocols

## Next Steps

After evaluation:
1. **Viable Sources**
   - Begin integration planning
   - Establish connections
   - Document requirements

2. **Non-Viable Sources**
   - Document reasons
   - Consider alternatives
   - Archive findings

3. **Needs Research**
   - Assign follow-up tasks
   - Set review timeline
   - Track pending items
