# Engineering Roadmap

## Proposed field staffing model — four officers per robot
Each deployed robot is paired with one dedicated four-officer team (4:1 staffing). This is a proposed operating model to validate during controlled trials, not an established police staffing standard.

1. **Mission commander:** accountable team lead; defines the lawful mission, authorizes consequential actions and coordinates with the host agency.
2. **Robot operator:** controls movement and sensor functions, monitors system status and executes safe-stop procedures.
3. **Safety officer:** independently watches for hazards to officers and the public, monitors exclusion distances and can call an immediate stop.
4. **Evidence and communications officer:** handles authorized radio coordination, incident logging, evidence provenance and chain-of-custody records; reviews AI-generated transcripts or summaries against original material.

The four roles must have clear handover and escalation procedures. The robot must remain under direct human supervision; no role delegates arrest, detention, force or guilt decisions to AI. If the team cannot maintain safe supervision, the robot is placed in a safe state and the mission pauses. Staffing, workload, communications and role separation must be evaluated in exercises before any operational pilot.

## Stage 0 — Define the problem
Consult South African emergency responders, municipalities, communities, disability advocates, engineers and relevant regulators. Select one narrowly defined non-weaponized use case. Define user needs, operating environment, success measures and unacceptable risks. Complete legal, privacy, safety and procurement discovery before hardware selection.

**Exit evidence:** requirements brief, stakeholder map, preliminary hazard register and feasibility assessment.

## Stage 1 — Feasibility and architecture
Evaluate candidate platforms for human-supervised operation, emergency stop, terrain and weather constraints, payload, endurance, communications, maintainability, local component availability, lifecycle cost, cybersecurity and privacy.

**Exit evidence:** architecture decision record, preliminary bill of materials, interface definitions, power budget, risk review and test plan.

## Stage 2 — Non-operational proof of concept
Build a laboratory or closed-course demonstrator. Start with low-risk functions such as teleoperation, status reporting, obstacle detection and safe-stop behavior. Use simulated or consented test data.

**Exit evidence:** test logs, failure analysis, safety review and documented limitations.

## Stage 3 — Controlled prototype
Integrate mechanical, electrical, software and communications subsystems. Verify environmental limits, stability, emergency stop, loss-of-link behavior, cybersecurity and maintainability in a controlled test environment. Exercise the four-officer team model, including operator workload, independent safety oversight, communications and emergency handover.

**Exit evidence:** traceable test report, team-exercise evaluation, independent review and corrective-action closure.

## Stage 4 — Authorized pilot
Proceed only with written authorization from the host organization and all applicable approvals. Define a limited mission, trained operators, community communication, data rules, insurance and liability arrangements, incident response and stop-work authority. Assign a named four-officer team to each robot for the pilot and document any approved exceptions.

**Exit evidence:** pilot authorization, operator training records, privacy assessment, safety case and post-pilot evaluation.

## Stage 5 — Local production readiness
Assess design for manufacture, supplier qualification, quality management, repair network, spare parts, training, lifecycle costs and responsible disposal. Establish traceability for safety-critical components.

**Exit evidence:** production-readiness review, quality plan, service documentation and independent acceptance.

## Technical workstreams
- Mechanical platform and mobility.
- Power system, battery safety and charging.
- Teleoperation, communications and fail-safe control.
- Sensors and situational awareness.
- Human-machine interface and accessibility.
- Secure software, update process and audit logging.
- Manufacturing, testing, maintenance and training.

All targets must be labelled as requirements, estimates or measured results. Never describe a prototype as field-ready without evidence and formal authorization.

## Human-trafficking response exercise
A controlled exercise may evaluate whether the four-officer team and robot can support a victim-centred search-and-rescue scenario without increasing risk to the person being helped. Use trained role-players or simulation; never use real survivor data in development tests.

- Mission commander coordinates with authorized specialist responders and victim-support services.
- Robot operator uses only approved teleoperation and rescue sensors; no autonomous person-following or questioning.
- Safety officer monitors physical hazards, safe access and the ability to stop the robot.
- Evidence and communications officer handles only authorized, minimum-necessary records and secure referrals; sensitive survivor details are not broadcast over open channels.
- Exercise interpreter access, discreet help-request communication, safe-stop, data minimization, secure evidence handling and referral handover.
- Evaluate whether the robot can be withdrawn without exposing or endangering a person.

**Exit evidence:** specialist review, survivor-safety assessment, privacy review, team exercise report and documented corrective actions. A successful simulation is not authorization for a live operation.

