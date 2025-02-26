# SurfLog

## ReadMe for SurfLog web application Milestone Project 3

---

Similar ideas (ios applications)

https://waveday.surf/#about

https://surfdiaryapp.com/

https://www.lazysurfer.app/

SurfLog
![SurfLog](https://github.com/user-attachments/assets/92f485a9-2d93-4fb6-a5c3-db25b0e17564)

---

## Surf Sessions Record

### Domain: Sport (Surfing)

### Database Structure:

Users

- User ID (Primary Key)
- Username (Unique)
- Password (Hashed)
- Email (Unique)

Spots

- Spot ID (Primary Key)
- Name (e.g., "Fistral North")
- Type (e.g., beach, reef, point)
- Wind (e.g., offshore, onshore)
- Crowd (low, medium, high)
- Tide (Rising, dropping, high, low, mid)
- Rating (1 to 5 stars)

Boards

- Name (Primary Key; string)
- Length (e.g. 6"4'; string))
- Fin setup (Single, twin, thruster, quad, bonzer)
- Image

Sessions

- Title (Primary Key)
- Spot ID (Foreign key from Spots table)
- Board (from Boards table)
- Date (e.g. 10-10-2024)
- Time (e.g., 08:00 AM)
- Size (e.g., 3 feet; integer plus feet/metres)
- Wind
- Wave Count (integer)
- Notes (text field)
- Rating (1-10)

### Functionality:

User Authentication

- Users can create accounts and log in securely.
- Implement password hashing for security.

Spot Management - Create, Read, Update, Delete

- Users can create and store surf spots, filling in all the relevant details.
- Allow users to edit or delete spots if needed.
- Display a list of saved spots for easy access and browsing.

Quiver (boards) management

- Create and store surfboard details.
- Allow users to edit or delete boards if needed.
- Display a list of saved boards for easy access.

Surf Session Logging

- Users can add surf sessions linked to specific spots and saved boards.
- Input relevant session details like date, time, size, wave count, and personal notes.
- Option to view/edit/delete individual surf sessions.

### Future updates:

- OS application and watch complication
- Create visualisations or charts to show trends over time (e.g., wave count, session frequency).
- Allow users to filter sessions by spot, date etc.
- Allow users to view their profile with statistics such as total sessions, average wave count, favourite spots, etc.
- Allow users to share their favourite sessions or spots.
