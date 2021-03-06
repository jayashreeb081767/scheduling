    appt-output-intro.md file


This profile sets minimum expectations for the Appointment resource to record, search and fetch basic information about an individual appointment. It identifies which core elements, extensions, vocabularies and value sets SHALL be present in the resource when using this profile.

This profile is defined for:

- Use in the Bundle resource as a result of the $find, $hold, and $ book operations.
- Patient searching for their appointments.
- Provider searching for their appointments.

##### Mandatory Data Elements and Terminology

The following data-elements are mandatory (i.e data MUST be present).

**Each Appointment must have:**

1. a status (e.g., 'proposed')
1. a start and end time
1. a list of participants and their individual statuses (e.g., the patient will be there)
1. the times that were requested for this appointment

**Additional Profile specific implementation guidance:**

#### Examples

- [Proposed Appt 1](Appointment-proposed-appt1.html)
- [Proposed Appt 2](Appointment-proposed-appt2.html)
- [Proposed Appt 3](Appointment-proposed-appt3.html)
