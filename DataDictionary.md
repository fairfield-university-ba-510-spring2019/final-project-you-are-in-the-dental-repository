# Data Dictionary 


# Programs #

**ID** - Program ID, the unique numeric identifier for the program a student enrolls in

**Catalog_id** - The text identifier of the section for registration
Course Title - Name of course 

**Program_name** - The text identifier for the program that students enroll in

**Program_Code** - The unique acronym for program_name
Attributes - A particular characterization of a course offering

# Courses #

**CID** - The numeric identifier of the Catalog_id

**Description** - The text details of the section offered 

**Fees** - Additional costs of of a particular course 

**Credits** - The numeric value of a completed section

**PID** - Program ID, the unique numeric identifier for the program a student enrolls in

**Title** - The name of the course

**Prereqs** - The completed courses required to register for that section

**Coreqs** - Corequisites


# Sections #

**SID** - Schedule The unique numeric identifier for a section

**CID** - The numeric identifier of the Catalog_id

**SCID** - Meeting ID, the unique numeric identifier for the time a section meets

**Term** - The semester and year a section is offered

**IID** - Instructor ID, the alphanumeric identifier for each individual professor 

**Act** - The actual number of students registered for a section

**Rem** - The actual number of seats left available for registration 
for a section

**CRN** - “Course Registration Number”, or a unique identifier of a course section

**Cap** - The maximum number of students that can register for a section

**Section** - The alphanumeric identifier for the course that is offered during a specific term


# Schedules #

**SCID**- Meeting ID, the unique numeric identifier for the time a section meets

**LID** - Location ID, the alphanumeric identifyer for each location

**Day** - The day in which the section of a course meets

**Start** - The first date and time in which a section of a course meets

**End** - The last date and time in which a section of a course meets

**Meetings** - The dates, days, times, and location that a section meets

**Timecodes** -  The dates, days, times, and location that a section meets


# Instructors #

**IID** - Instructor ID, the alphanumeric identifier for each individual professor 

**Primary_instructor** - The actual text name of the instructor of the section


# Classrooms #

**LID** - Location ID, the alphanumeric identifyer for each location

**Location** - Physical classroom location where a section of a course meets 


