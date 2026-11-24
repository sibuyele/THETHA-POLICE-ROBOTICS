# Privacy and Data Governance

A robot is not a general-purpose surveillance platform. Collect the minimum information needed for a clearly defined and lawful purpose.

## Requirements
- Document purpose and lawful basis before collecting personal information.
- Avoid facial recognition, biometric identification and persistent tracking by default.
- Do not collect audio, video or location data unless the specific mission requires it and collection is authorized.
- Audio capture is off by default; require mission-specific activation, a recording indicator where feasible, restricted access and documented retention.
- Thermal imagery can still reveal information about people and must receive the same purpose limitation, access control and retention safeguards as other sensor data.
- Separate original recordings and sensor files from AI-generated transcripts, translations, summaries and annotations.
- Label AI outputs as machine-generated; preserve source references, timestamps, model/version information where available, and human-review history.
- Never use AI outputs alone to identify a person, infer guilt, assess credibility, or make an arrest or detention decision.
- Provide clear notice where feasible and apply safeguards where notice is not possible during an emergency.
- Restrict access by role; use strong authentication and encryption in transit and at rest.
- Keep tamper-evident access and export logs.
- Set retention and deletion periods before a pilot begins.
- Securely delete data when its approved purpose and retention period end, subject to lawful preservation requirements.
- Do not use mission data to train models or for unrelated purposes without separate lawful assessment and authorization.
- Establish procedures for access requests, correction, complaints, breaches and evidence preservation.

## Trafficking-survivor information
- Treat location, identity, contact details, statements, images and service-provider links as highly sensitive.
- Do not expose a survivor's location or identity to unauthorized users or through public-facing dashboards, alerts or shared maps.
- Apply strict role-based access, access logging, minimum-necessary sharing and a documented safety review before disclosure.
- Do not collect or retain sensitive interview content by default. Record only when specifically authorized and necessary under a survivor-sensitive protocol.
- Do not infer trafficking status from nationality, immigration status, language, gender, age, appearance or movement patterns.
- Do not repurpose survivor data for model training, publicity, fundraising or unrelated investigations.

## South African legal review
Before field trials, obtain qualified advice on applicable South African requirements, including POPIA, applicable law-enforcement or public-sector rules, evidence handling, communications, aviation or radio rules where relevant, and occupational health and safety obligations. Applicability depends on operator, purpose, data and deployment context.

## Pilot privacy assessment
A pilot documents data categories, collection points, purpose, lawful basis, affected people, access roles, processors, storage location, retention, deletion, security controls, cross-border transfers, incident response and a complaints contact.
