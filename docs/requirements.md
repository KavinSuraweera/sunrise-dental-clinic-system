# System Requirements

## REQ-01 - Login and Logout

Authorized staff must be able to log in and log out safely.

**Check:** Given valid login details, when staff log in, then the system opens the main page.

## REQ-02 - Staff Roles

The system must have Receptionist and Administrator roles.

**Check:** Given a logged-in user, when they open the system, then they can only use functions allowed for their role.

## REQ-03 - Register Appointment

Staff must be able to register an appointment with:

- Appointment number
- Patient name
- Address
- Contact number
- Dentist name
- Treatment type
- Appointment date
- Appointment time

**Check:** Given valid information, when staff submit the form, then the appointment is saved.

## REQ-04 - Unique Appointment Number

Every appointment must have a different appointment number.

**Check:** Given an existing number, when the same number is entered again, then the system rejects it.

## REQ-05 - Validation

The system must reject missing or incorrect information.

**Check:** Given invalid information, when the form is submitted, then a clear message is displayed.

## REQ-06 - Prevent Double Booking

A dentist must not have two appointments at the same time.

**Check:** Given a dentist is already booked, when another appointment uses the same time, then the system rejects it.

## REQ-07 - Search Appointment

Staff must be able to search using the appointment number.

**Check:** Given an existing appointment number, when staff search for it, then the full appointment is displayed.

## REQ-08 - Update and Cancel Appointment

Staff must be able to update or cancel an appointment.

**Check:** Given an existing appointment, when staff update or cancel it, then the change is saved.

## REQ-09 - Bill and Receipt

The system must calculate the treatment cost and consultation fee and provide a receipt.

**Check:** Given a completed appointment, when staff create a bill, then the correct total and receipt are displayed.

## REQ-10 - Help Section

The system must provide simple instructions for new staff.

**Check:** Given a logged-in user, when they open Help, then instructions are displayed.

## REQ-11 - Web Services

The system must provide REST web services.

**Check:** Given a valid request, when a web service is called, then the correct response is returned.

## REQ-12 - Reports

The system must provide useful clinic reports.

**Check:** Given saved clinic information, when staff open a report, then useful appointment or payment information is displayed.

## REQ-13 - Friendly Error Messages

The system must show clear and safe error messages.

**Check:** Given an error occurs, when the system handles it, then a friendly message is shown without technical or private information.

## REQ-14 - Public Deployment

The latest tested version must be deployed online.

**Check:** Given the latest version passes its tests, when the public link is opened, then the application works.