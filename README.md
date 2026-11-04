# University Badminton Management System

## 1. Project Overview

The University Badminton Management System is a proposed software solution designed to manage badminton-related activities at the university.

Currently, court bookings, player registrations, trials, team selections, external rentals and tournament arrangements are handled manually. This creates difficulties in maintaining records, managing court availability, preventing booking conflicts and organizing university badminton activities.

The proposed system will bring these activities into one centralized platform. It will help university officials manage court bookings, organize Talent Hunt and trials, maintain player performance records, manage training sessions and coordinate tournaments.

The primary objective is to improve transparency, organization and efficiency in university badminton management.

## 2. Project Scope

### 2.1 In Scope

The system will include the following capabilities:

1. *User Accounts and Roles:* Separate accounts for the Director of Sport, Assistant Director, Badminton Coach, Players, Staff and External Organizations.

2. *Court Booking and Scheduling:* Manage court reservations for university teams, students, faculty members and external users while preventing double bookings.

3. *External Rentals:* Allow schools and colleges to submit rental requests, record event details and manage approval by the Director.

4. *Talent Hunt and Trials:* Manage student registrations, trial schedules, performance records and results.

5. *Team Selection:* Maintain trial results, support player selection and record the Director's final approval.

6. *Scholarship Recommendations:* Maintain player performance and achievement records to support scholarship decisions.

7. *Training Management:* Manage training schedules, attendance and shuttle usage during training camps.

### 2.2 Out of Scope

The following features are excluded:

* Management of other sports such as cricket, football and table tennis.
* Online payment of external rental charges.
* Online payment of scholarship money.
* Hardware integration such as card scanners and biometric attendance systems.

### 2.3 Project Limitations

* The system will cover PU badminton courts and university badminton teams only.
* The system requires an active internet connection.
* Rental charges and player selection rules may vary depending on the event, so authorized staff must be able to configure them.

## 3. Stakeholders

### 3.1 Director of Sport

* Supervises the complete badminton management system.
* Approves external rental requests.
* Participates in trials and interviews.
* Gives final approval for team selection.
* Makes scholarship decisions based on player performance.

### 3.2 Assistant Director

* Manages and records court bookings.
* Handles court scheduling and booking conflicts.
* Manages daily badminton activities.
* Handles event-related problems and arrangements.

### 3.3 Badminton Coach

* Participates in player trials and selection.
* Evaluates player performance and potential.
* Manages team training.
* Maintains training schedules and attendance.

### 3.4 Players / Students

* Use badminton courts.
* Register for Talent Hunt and trials.
* Participate in university competitions.
* View trial schedules and results.

### 3.5 Faculty Members

* Use badminton courts.
* Require guaranteed court access on Sundays, which are reserved for faculty members.

### 3.6 Project Team

* Responsible for developing and documenting the proposed system.
* Collects and analyzes stakeholder requirements.
* Maintains project documentation.

## 4. Functional Requirements

* *FR-01: User Management:* The system shall allow authorized users to access the system according to their assigned roles and permissions.

* *FR-02: Court Booking:* The system shall allow the Assistant Director to create and manage court bookings for authorized users.

* *FR-03: Booking Conflict Prevention:* The system shall prevent two users from booking the same court for the same time slot and shall prioritize university teams over external users. Sundays shall be reserved exclusively for faculty members.

* *FR-04: External Rental Management:* The system shall allow external organizations to submit rental requests containing the number of players, courts and sports required. The system shall require the Director's approval before confirming a rental request.

* *FR-05: Talent Hunt and Trials:* The system shall allow students to register for Talent Hunt and trials and allow authorized officials to record trial performance and results.

* *FR-06: Team Selection:* The system shall maintain player trial results and allow the Director to record final approval of selected players after the selection process.

* *FR-07: Training Management:* The system shall allow authorized staff to schedule training sessions and maintain attendance and shuttle usage records.

* *FR-08: Scholarship Records:* The system shall maintain player performance and achievement records for the Director to review when making scholarship decisions.

* *FR-09: Tournament Management:* The system shall allow authorized staff to create tournament match schedules and allocate courts when the university hosts an event.

* *FR-10: Reports:* The system shall allow the Director and Assistant Director to access relevant administrative reports.

## 5. Nonfunctional Requirements

* *NFR-01: Performance:* The system shall display all main administrative reports within 10 seconds when accessed through the admin panel under normal operating conditions.

* *NFR-02: Availability:* The system shall be accessible through supported mobile phones and computers whenever an internet connection is available and the service is operational.

Note: NFR-02 is a proposed quality requirement. Supported devices and availability targets require stakeholder confirmation.

## 6. Acceptance Criteria

The following conditions will be used to verify the functional requirements.

* *FR-01:* When a user logs in, the system displays the features and permissions associated with that user's assigned role.

* *FR-02:* When the Assistant Director creates a booking for an available court and time slot, the booking is saved and displayed in the booking records.

* *FR-03:* When a second user attempts to book an already reserved court and time slot, the system rejects the conflicting booking. A university team receives priority over an external user, and non-faculty users cannot book courts on Sundays.

* *FR-04:* When an external organization submits a rental request, the system records the requested players, courts and sports. The request cannot be confirmed until the Director approves it.

* *FR-05:* When a student registers for Talent Hunt or trials, the registration is recorded. Authorized officials can enter and view the student's trial results.

* *FR-06:* When the Director approves the final team selection, the system records the selected players and the approval.

* *FR-07:* When an authorized staff member schedules a training session, the system records its schedule, attendance and shuttle usage.

* *FR-08:* When the Director opens a player's scholarship record, the system displays the available performance and achievement information.

* *FR-09:* When the university hosts a tournament, authorized staff can generate a match schedule and allocate available courts to matches.

* *FR-10:* When the Director or Assistant Director opens an administrative report, the report is displayed within 10 seconds under normal operating conditions.

## 7. Assumptions and Open Questions

### 7.1 Assumptions

* *A-01:* Each system user will have an assigned role with appropriate access permissions.
* *A-02:* The university's existing badminton rules will be followed by the system.
* *A-03:* University teams will receive priority over external users when booking conflicts occur.
* *A-04:* Sundays will remain reserved for faculty members.
* *A-05:* Authorized officials will be responsible for entering trial results and player performance records.
* *A-06:* Rental charges and team selection rules may be configured according to individual events.

### 7.2 Open Questions

* *Q-01:* What exact criteria will be used to evaluate players during Talent Hunt and trials?
* *Q-02:* What will be the final rental charges for external organizations?
* *Q-03:* How many players will be selected for each team, and will the number vary according to available positions?
* *Q-04:* Which specific mobile devices, browsers and computer environments must be supported?
* *Q-05:* What availability target should the system meet?
* *Q-06:* Which reports should be accessible to the Director and Assistant Director?

## 8. Project Status and Usage

*Project Status: Documentation and Requirements Phase*

This repository contains the project vision, initial requirements and documentation for the University Badminton Management System.

Application implementation has not started.

To obtain the project files, clone the GitHub repository:

git clone https://github.com/bsef25m507/sre-github-lab.git

Navigate to the repository folder and open README.md using a Markdown-compatible editor such as Visual Studio Code or view the rendered documentation on GitHub.

No application installation or execution commands are required at this stage.

## 9. Project Team / Authors

*Course:* Software Requirements Engineering

*Group Members:*

1. Awais Ur Rehman – BSEF25M507
2. Taha Saeed – BSEF25M529
3. Muhammad Anas – BSEF25M558
