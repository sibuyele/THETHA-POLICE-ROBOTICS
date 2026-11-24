# Safety and Human Control

This is a requirements baseline, not a safety certification.

## Prohibited capabilities
- Firearms, less-lethal weapons, explosive payloads or weapon interfaces.
- Target recognition or selection for applying force.
- Autonomous pursuit, apprehension, restraint, punishment or coercive crowd control.
- Autonomous decisions that use physical force against a person.
- Features intended to conceal operator identity or evade lawful oversight.

## Human responsibility
- A named, trained operator supervises each active mission.
- A human authorizes movement into operational areas and any action with material consequences for a person.
- Remote operators can stop motion and place the platform in a safe state.
- Loss of control link, degraded localization, sensor disagreement or unexpected behavior triggers a predefined safe response.
- Communications failure is never permission to continue a mission autonomously.
- Each deployment identifies the responsible organization, operator, mission purpose and emergency contact.

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
