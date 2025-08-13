# Lesson Learned Template

**Lesson ID**: LL-YYYY-###  
**Date**: YYYY-MM-DD  
**Investigator**: [Name]  
**Category**: [Technical/Process/Investigation]  
**Subcategory**: [Architecture/Performance/Security/Testing/Deployment/Integration]  
**Severity Impact**: [Critical/High/Medium/Low]  
**Confidence Level**: [Percentage of confidence in root cause analysis]

---

## Problem Summary

### Issue Description
- Brief description of the issue investigated
- When it was discovered and by whom
- Initial symptoms observed

### Systems/Components Affected
- List all affected systems, services, or components
- Impact scope (users affected, services down, etc.)
- Business impact assessment

### Timeline
- When issue started
- When it was detected
- Investigation duration
- Resolution timeline

---

## Investigation Process

### Evidence Collected
- Logs analyzed
- Metrics reviewed
- System state captured
- User reports gathered

### Hypotheses Tested
- List each hypothesis with initial confidence score
- Testing methods used
- Results obtained
- Final confidence score

### Diagnostic Techniques Used
- Most effective diagnostic methods
- Tools and techniques that helped
- Approaches that were ineffective
- Time investment by technique

---

## Root Cause Analysis

### Root Cause Identified
- Fundamental cause with confidence score (must be 95%+)
- Contributing factors
- Why it wasn't detected earlier
- Validation method used

### 5 Whys Analysis
1. **Why did the immediate problem occur?**
2. **Why did that happen?**
3. **Why did that happen?**
4. **Why did that happen?**
5. **Why did that happen?**

### Fishbone Analysis (if applicable)
- **Method**: Process/procedure issues
- **Machine**: System/infrastructure issues  
- **Material**: Data/input issues
- **Man**: Human factor issues
- **Measurement**: Monitoring/detection issues
- **Environment**: External factor issues

---

## Solution Applied

### Fix Implementation
- Detailed description of solution implemented
- Why this approach was chosen
- Implementation steps taken
- Rollback plan prepared

### Validation Results
- Testing performed to validate fix
- Metrics showing resolution
- User acceptance confirmation
- Performance impact assessment

### Solution Effectiveness
- How well the fix addressed the root cause
- Any remaining risks or concerns
- Long-term stability assessment

---

## Prevention Measures

### Immediate Improvements
- Monitoring enhancements implemented
- Alerting improvements added
- Process changes made
- Documentation updated

### Recommended Future Actions
- Architecture modifications suggested
- Testing enhancements needed
- Development practice changes
- Training requirements identified

### Technical Debt Created/Addressed
- New technical debt introduced by fix
- Existing technical debt that contributed to issue
- Recommendations for debt reduction

---

## Knowledge Captured

### Technical Insights
- What we learned about system architecture
- Performance characteristics discovered
- Security implications identified
- Integration points clarified

### Process Insights
- Gaps in monitoring or alerting
- Testing coverage improvements needed
- Development practices to modify
- Deployment process enhancements

### Investigation Insights
- Most effective troubleshooting methods for this type of issue
- Tools that proved most valuable
- Time-saving techniques discovered
- Methods to avoid in similar situations

---

## Future Applications

### Similar Scenarios
- How this lesson applies to related problems
- Technologies or components to monitor
- Early warning signs to watch for

### Proactive Measures
- Preventive monitoring to implement
- Code review checkpoints to add
- Testing scenarios to include
- Architecture patterns to avoid/embrace

### Team Knowledge Transfer
- Skills or knowledge gaps identified
- Training recommendations
- Documentation improvements needed
- Expertise sharing opportunities

---

## References and Links

### Related Documentation
- Technical debt items: [Link to project-management/technical-debt.md entries]
- Epic/story connections: [Link to relevant epics]
- System documentation: [Links to architecture docs, runbooks, etc.]

### External Resources
- Useful articles or documentation discovered
- Tools or techniques learned about
- Community resources that helped

### Follow-up Actions
- [ ] Create/update monitoring alerts
- [ ] Update system documentation
- [ ] Add test cases to prevent regression
- [ ] Schedule technical debt reduction
- [ ] Share knowledge with team
- [ ] Update development guidelines

---

## Retrospective

### What Went Well
- Effective investigation techniques
- Good collaboration or communication
- Successful solution implementation

### What Could Be Improved
- Investigation process improvements
- Communication enhancements
- Tool or process gaps identified

### Overall Assessment
- Investigation effectiveness rating (1-10)
- Solution confidence rating (1-10)
- Process improvement opportunities
- Lessons for future investigations

---

**Template Version**: 1.0  
**Last Updated**: 2025-01-13
