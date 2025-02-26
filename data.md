Users

- User ID (Primary Key, integer)
- Username (Unique)
  - Pob
  - Kat
  - Vinny
- Password (Hashed)
  - Pob1
  - Kat1
  - Vinny1
- Email (Unique)
  - pob@surflog.co.uk
  - kldawes@gmail.com
  - vin@surflog.co.uk

Spots

- Spot ID (Primary Key, integer)
- Name (e.g., "Fistral North")
- Type (e.g., beach, reef, point)
- Wind (best wind direction, string)
- Crowd (usually: low, medium, high)
- Tide (Rising, dropping, high, low, mid, any)
- Rating (1 to 5 stars)
- Notes

- Fistral North, beach, wind, high, any, 5
- Crannog, beach, SE, medium, dropping, 1, terrible place don't surf here
- Anchors, point, wind, high, any, 5, Morocco's finest
- Kiama, beach, E, medium, any, 4, Aussie dream
-

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
