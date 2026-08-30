# Project Assumptions

## A-01 - Staff Roles

The system will have Receptionist and Administrator roles.

**Reason:** Receptionists manage patients and appointments. Administrators manage staff, treatments and reports.

## A-02 - Exit Means Logout

The Exit function will be implemented as Logout.

**Reason:** Logging out safely ends the staff member's session.

## A-03 - Fictional Information

Only fictional patient, dentist and appointment information will be used.

**Reason:** Real patient information must remain private and secure.

## A-04 - Currency

All prices will use Sri Lankan Rupees (LKR). Java BigDecimal will be used for money calculations.

**Reason:** The clinic is in Colombo, and BigDecimal provides accurate calculations.

## A-05 - Treatment Duration

Each treatment type will have a standard duration.

**Reason:** The duration allows the system to detect and prevent overlapping appointments.