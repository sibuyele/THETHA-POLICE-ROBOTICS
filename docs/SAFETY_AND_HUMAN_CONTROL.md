# Safety and Human Control

This is a requirements baseline, not a safety certification.

## Prohibited capabilities
- Firearms, less-lethal weapons, explosive payloads or weapon interfaces.
- Target recognition or selection for applying force.
- Autonomous pursuit, apprehension, restraint, punishment or coercive crowd control.
- Autonomous decisions that use physical force against a person.
- Identifying, profiling, tracking, ranking or selecting people based on actual or perceived immigration or citizenship status.
- Mass-arrest, immigration-sweep or population-surveillance functionality.
- Deciding whether a person is lawfully present or should be arrested.
- Facial recognition, voiceprint identification, emotion inference, deception detection or AI criminality/risk scoring of people.
- Features intended to conceal operator identity or evade lawful oversight.
- Covert monitoring of shelters, clinics, homes or victim-support organizations.

## Human responsibility
- A named, trained operator supervises each active mission.
- The robot does not make immigration-status or arrest decisions.
- Any lawful enforcement decision belongs to authorized human officials applying relevant law to an individual case; it is not delegated to the robot.
- A human authorizes movement into operational areas and any action with material consequences for a person.
- Remote operators can stop motion and place the platform in a safe state.
- Loss of control link, degraded localization, sensor disagreement or unexpected behavior triggers a predefined safe response.
- Communications failure is never permission to continue a mission autonomously.
- Each deployment identifies the responsible organization, operator, mission purpose and emergency contact.

## Human-trafficking response and victim protection
- Use the platform only to support a defined, authorized rescue, welfare or investigative mission led by trained personnel.
- Treat a person who may have been trafficked as potentially needing protection, not as an offender. Never infer victim or offender status from appearance, nationality, language, immigration status or movement.
- Do not autonomously identify, follow, approach, question, separate or transport a person. A trained human responder decides how to make safe contact.
- Provide a clear, discreet way to request help where appropriate; do not promise confidentiality or safety beyond what the responsible agency can provide.
- Support access to qualified interpreters and specialist victim-support services. Do not rely on AI translation alone for consent, disclosure or urgent decisions.
- Avoid actions that could alert a suspected trafficker, expose a victim's location or increase risk. Mission planning must be led by trained specialists.
- Do not record sensitive interviews by default. Any recording requires specific legal authority, informed and freely given consent where required, and a survivor-sensitive protocol.
- Do not make credibility, risk, guilt or trafficking determinations using AI. Preserve human choice and dignity; urgent safeguarding decisions remain with qualified people.

## Thermal sensing
- Thermal sensors may support search and rescue, navigation in low visibility and detection of heat-related hazards.
- Thermal imagery must not be treated as proof of identity, intent, immigration status or criminal conduct.
- Operators must consider environmental effects, sensor limits and false positives; consequential findings require independent human verification.

## Inspection support
- Possible prohibited-item alerts may only support a specific, legally authorized inspection carried out by trained personnel.
- The robot must not independently search, stop, detain or accuse a person based on a sensor alert.
- Record sensor type, calibration status, limitations and operator actions; preserve original data where it is lawfully required.

## On-scene AI assistance
- Audio capture is off by default and may be activated only for a documented mission purpose with appropriate legal authority.
- Provide a visible or audible recording indicator where feasible; restrict access and avoid collecting unrelated conversations.
- AI may transcribe, translate, structure notes and draft timelines. It must not identify speakers by voiceprint, infer emotion or deception, or decide guilt.
- Preserve original recordings separately from AI-generated outputs. Mark AI outputs as machine-generated, retain provenance and timestamps, and require human review against the original.
- Never allow an AI summary to replace a witness statement, officer observation or original evidence.
- For murder, sexual-offence, child-protection and trafficking investigations, apply heightened access restrictions, survivor-sensitive handling, minimization and legally approved retention.

## Minimum safety engineering
Every prototype requires documented hazard analysis; physical emergency stop; independently tested safe-stop behavior; speed, force, thermal and environmental limits; guarding and stability assessment; battery and charging protections; fail-safe behavior for sensor, software and communications faults; maintenance procedures; and incident reporting.

## Test gates
1. Requirements and hazard review.
2. Bench testing without public interaction.
3. Controlled test-area trials with safety observers.
4. Independent functional-safety and cybersecurity assessment.
5. Limited, authorized pilot with documented oversight.
6. Formal review before wider operational use.

Passing one gate does not imply passing the next. No public deployment based solely on a demonstration.

## Incident handling
Stop the test or mission when an unsafe condition occurs. Preserve relevant logs, notify the safety lead, secure the system, investigate root causes, document corrective actions and obtain approval before resuming.

Each prototype release requires a dated review record naming the engineering lead, safety reviewer, test evidence, known limitations and explicit approval scope.
