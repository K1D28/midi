# Spec: 001 - MIDI Sequencer

## Feature Description
[As a musician, I want to create simple MIDI sequences in the browser so I can prototype music without software installs.]

## User Scenarios & Testing
- Scenario 1: User adds notes to a 16-step grid → Expected: Notes play on "Play".
- Scenario 2: User exports sequence → Expected: Downloads as .mid file.

## Functional Requirements
FR-001: System MUST display a 16-step grid for notes C4-G4.
FR-002: System MUST play sequences on demand.
FR-003: System MUST export as a .mid file.

## Key Entities
- Sequence: {notes: [{pitch: string, time: number, duration: number}]}

## Review Checklist
- [x] Testable? Yes.
- [ ] Ambiguities? No.
- SUCCESS: Ready for /plan.
