## SurfLog 

ReadMe for SurfLog web application Milestone Project 3 

Similar ideas (ios applications) 
https://waveday.surf/#about
https://surfdiaryapp.com/
https://www.lazysurfer.app/

Surf Sessions Record
Domain: Sport (Surfing)
Database Structure:

    Users
        User ID (Primary Key)
        Username (Unique)
        Password (Hashed)
        Email (Unique)

    Spots
        Spot ID (Primary Key)
        Name (e.g., "Fistral North")
        Type (e.g., beach, reef, point)
        Wind (e.g., offshore, onshore)
        Crowd (low, medium, high)
        Tide (Rising, dropping, high, low, mid)
        Rating (1 to 5 stars)

    Boards
      Name
      Length
      Fin setup 
      Image 

    Sessions
        Session ID 
        Spot ID 
        Board 
        Date (e.g. 10-10-2024)
        Time (e.g., 08:00 AM)
        Size (e.g., 3 feet)
        Wave Count 
        Notes (text field)

Functionality:

    User Authentication
        Users can create accounts and log in securely.
        Implement password hashing for security.

    Spot Management
        Users can create and store surf spots, filling in all the relevant details.
        Allow users to edit or delete spots if needed.
        Display a list of saved spots for easy access.

    Quiver management
        Create and store surfboard details.
        Allow users to edit or delete boards if needed.
        Display a list of saved boards for easy access.

    Surf Session Logging
        Users can add surf sessions linked to specific spots.
        Input relevant session details like date, time, size, wave count, and personal notes.
        Option to view/edit/delete individual surf sessions.

Future updates: 
    iOS application and watch complication 
    Data Visualization
        Create visualizations or charts to show trends over time (e.g., wave count, session frequency).
        Allow users to filter sessions by spot or date range.
    User Profiles
        Allow users to view their profile with statistics such as total sessions, average wave count, favorite spots, etc.
        Allow users to share their favorite sessions or spots.
