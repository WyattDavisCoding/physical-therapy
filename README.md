# physical-therapy
Physical Therapy Scheduling/ETC Webpage

The project seeks to replace outdated record keeping of appointments. We replaced pencil and paper with a calendar system with a login for admin, scheduler, and therapist with their own view of the calendar and tools
  Scheduler is greeted to a calendar making up of two bullet hole style buttons as a way to filter the appointments on the calendar. Clicking the date on the calendar brings up a window with an appointment form. Clicking an appointment on the calendar brings up the exact same window but now an option to edit it or delete it.
	Therapist is similar to a scheduler’s view when it comes to the calendar. It has a section with “Your Weekly Availability” where therapists can set a new availability baseline for the week. Setting specific day’s hours or days off is in progress(Set New Custom Availability). When clicking the calendar appointments it brings up a window with info important to the therapist like the scheduler’s notes.
	Admin also has a calendar where they can see appointments but clicking them does nothing. Section labeled “Admin Tools” allows clicking a therapist to highlight them. The subsequent “Edit”, “Add”, and “Delete” buttons pull up their  respective windows or confirmations of the highlighted therapist.

 Your database to use this should look as follows:
Table:
 "Appointments" holds start time, appointment date, and therapist assigned(TherapistName/ID)
 "Certifications" has all certifications/services provided by the physical therapists
 "Certifications_Therapists" holds therapists(TherapistName/ID) and their respective certifications(Cert/CertID)
 "Login_System" holds user login (Username/Password)
 "Schedules" holds therapist' baseline scheudles(Start, End and Day)
 "Therapists" Holds all therapist info (TherapistName/ID)
Classes:
 "Database"
 "Event"
 "Avail"
 
View "scheduling.gif" for a reference of what it looks like.
