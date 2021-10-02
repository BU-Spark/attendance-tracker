# attendance-tracker
An app to track student attendance in classes

## Concept

A QR code is generated based on the professor inputting "something."
Prof then prints the QR code.
Students scan the code and input their email address and submit. Location services are used to verify the student is in the right location.

## Something

* Professor's Name
* Professor's Email
* Location of class: Using OpenLocationCode or PlusCodes (same thing, two names)
* Time & Timezone of class
* Day(s) of week of the class
* CSV of "further student information" with email addresses: when student's "login" the system will send the row of "further student information" that corresponds to the email address
*