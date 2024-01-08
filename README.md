# Euterpe: Music Database

Welcome to Euterpe, named after the Greek muse of music! This music database offers a range of functionalities across 8 main pages, each tailored to enhance the user's music exploration experience:

1. **Home Page:** Displays top artists and highest-rated songs.
2. **Artist Page:** Profiles five unique artists.
3. **Albums Page:** Showcases five albums by each artist.
4. **Songs Page:** Contains all songs from a selected album.
5. **About Page:** Provides insights into the creators behind the platform.
6. **Artist Spotlight Page:** Features temporary storage for user-entered ratings and includes a countdown timer to an upcoming album/song release (set to default at May 2023).
7. **Search Page:** Utilizes the iTunes API, enabling song previews based on user-entered queries. It allows filtering by song duration and explicitness, displaying track names, artist names, and album posters.
8. **Playlist Page:** Stores a non-redundant list of songs persistently. Additionally, it allows users to remove selected songs with ease.

## Key Features:
- **Navigation and Footer:** Consistent throughout the database.
- **Interactive Features:** Incorporates zoom, temporary storage, click events, and more, implemented through JavaScript.
- **Aesthetics:** Enhanced aesthetics achieved using CSS.
- **Persistence:** Implemented SQL for persistent data storage.

## Setup Instructions:
To ensure proper functionality, follow these steps in the directory of the files:
```bash
chmod +x app.py
pip install flask
pip install flask_sqlalchemy
