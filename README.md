# Incident-Management-System
An incident is an event that could lead to loss of, or disruption to, an organization's operations, services or functions. Incident management is a term describing the activities of an organization to identify, analyze, and correct hazards to prevent a future recurrence.
The objective of the project is to build Machine learning models to predict the time required to close an incident and to predict whether the incident will meet the SLA (Service Lease Agreement or not.

### DATA DESCRIPTION
This dataset has been downloaded from the UCI Machine Learning Repository.
 Number of instances: 141,712 events (24,918 incidents)
 Number of attributes: 36 attributes (1 case identifier, 1 state identifier, 32 descriptive attributes, 2
dependent variables)
The attributed “closed_at” is used to determine the dependent variable for the time completion
prediction task. The attribute “resolved_at” is highly correlated with “closed_at”. In this event log,
some rows may have the same values (they are equal) since not all attributes involved in the realworld
process are present in the log.
Attributes used to record textual information are not placed in this log.
The missing values should be considered as unknown information.

### Attribute Information:
1. number: incident identifier (24,918 different values);
2. incident state: eight levels controlling the incident management process transitions from opening
until closing the case;
3. active: Boolean attribute that shows whether the record is active or closed/cancelled;
4. reassignment_count: number of times the incident has the group or the support analysts
changed;
5. reopen_count: number of times the incident resolution was rejected by the caller;
6. sys_mod_count: number of incident updates until that moment;
7. made_sla: boolean attribute that shows whether the incident exceeded the target SLA;
8. caller_id: identifier of the user affected;
9. opened_by: identifier of the user who reported the incident;
10. opened_at: incident user opening date and time;
11. sys_created_by: identifier of the user who registered the incident;
12. sys_created_at: incident system creation date and time;
13. sys_updated_by: identifier of the user who updated the incident and generated the current log
record;
14. sys_updated_at: incident system update date and time;
15. contact_type: categorical attribute that shows by what means the incident was reported;
16. location: identifier of the location of the place affected;
17. category: first-level description of the affected service;
18. subcategory: second-level description of the affected service (related to the first level
description, i.e., to category);
19. u_symptom: description of the user perception about service availability;
20. cmdb_ci: (confirmation item) identifier used to report the affected item (not mandatory);
21. impact: description of the impact caused by the incident (values: 1 - High; 2 - Medium; 3 - Low);
22. urgency: description of the urgency informed by the user for the incident resolution (values: 1 -
High; 2 - Medium; 3 - Low);
23. priority: calculated by the system based on 'impact' and 'urgency';
24. assignment_group: identifier of the support group in charge of the incident;
25. assigned_to: identifier of the user in charge of the incident;
26. knowledge: boolean attribute that shows whether a knowledge base document was used to
resolve the incident;
27. u_priority_confirmation: boolean attribute that shows whether the priority field has been
double-checked;
28. notify: categorical attribute that shows whether notifications were generated for the incident;
29. problem_id: identifier of the problem associated with the incident;
30. rfc: (request for change) identifier of the change request associated with the incident;
31. vendor: identifier of the vendor in charge of the incident;
32. caused_by: identifier of the RFC responsible by the incident;
33. close_code: identifier of the resolution of the incident;
34. resolved_by: identifier of the user who resolved the incident;
35. resolved_at: incident user resolution date and time (dependent variable);
36. closed_at: incident user close date and time (dependent variable).
