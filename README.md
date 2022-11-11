# User-Management-Screen
## UI Specification Document
### Main Page

1. Header
    - "New User" Button, that opens up a **form to add the details of a new user**
    - Checkbox, label "Hide Disabled User". When checked => all the users with Enabled value == false are hidden
    - Both should be placed in Top-Left, side by side

2. Table
    - 4 Columns (With an option to sort as well as filter each)
      - ID, User ID's starting with 1. (Int)
      - User Name (Varchar)
      - Email (Varchar)
      - Enabled (Bool)
    - Dynamic Number of Rows (changes each time a user is added or disabled) 
      - Shows each of the users row by row according to the headings described above

3. New User Form (Opens when "New User" Button is clicked)
    - "Save User" Button, placed at the Top-Right of the form. when clicked the user is saved in the Database and updated in the User Table (Described above in **2**)
    - "Username" field, user input enabled (Varchar)
    - "Display Name" field, user input enabled (Varchar)
    - "Phone" field, user input enabled (Varchar)
    - "Email" field, user input enabled (Varchar). Verification of email address could be applied 
    - "User Roles" field, when clicked opens following Drop Down Menu:
      - Guest
      - Admin
      - SuperAdmin
    - "Enabled" Checkbox
