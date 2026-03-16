# Scout Map
Interactive Gamified webtool where the user can mark locations with custom pins and add image descriptions which can be 
searched in the search bar, also incorporating a fog of war overlay which is helpful to track your progress.

## Privacy and Storage
This tool uses no backend, no database, no cloud storage even the data that is stored in the browser gets deleted after a refresh
Datas can only be exported and imported manually by the user, once the tool is opened for the first time the user needs to export a venture using 
the export button on ventures drawer or export all to export all of the ventures in that session. 

## Features : 
- Location search
- Fog of war overlay which is cleared by movements and pins 
- Custom pins with image description 
- Search withing image description
- Achivements.txt 
- Artifacts.txt 
- Levels.txt 
- each txt files can be edited by the user to change how those features work  

## Tech Stack : 
- HTML/CSS/Vanilla JavaScript 
- Leaflet.js for the map UI
- OpenStreetMap tiles for map imagery
- Nominatim for place search (geocoding)
- Browser Geolocation API for live location tracking
- FileReader API for image uploads
- JSON export/import for save files

## made with Claude ai and Codex 5.2 ai

```text
█████       ███      █████                                                   █████       █████ ██████████  
░░███       ░░░      ░░███                                                   ░░███       ░░███ ░░███░░░░███ 
 ░███ █████ ████   ███████  ████████    ██████   █████████████    ██████   ███████        ░███  ░███   ░░███
 ░███░░███ ░░███  ███░░███ ░░███░░███  ░░░░░███ ░░███░░███░░███  ███░░███ ███░░███        ░███  ░███    ░███
 ░██████░   ░███ ░███ ░███  ░███ ░███   ███████  ░███ ░███ ░███ ░███████ ░███ ░███        ░███  ░███    ░███
 ░███░░███  ░███ ░███ ░███  ░███ ░███  ███░░███  ░███ ░███ ░███ ░███░░░  ░███ ░███  ███   ░███  ░███    ███ 
 ████ █████ █████░░████████ ████ █████░░████████ █████░███ █████░░██████ ░░████████░░████████   ██████████  
░░░░ ░░░░░ ░░░░░  ░░░░░░░░ ░░░░ ░░░░░  ░░░░░░░░ ░░░░░ ░░░ ░░░░░  ░░░░░░   ░░░░░░░░  ░░░░░░░░   ░░░░░░░░░░   
                                                                                                            
                                                                                                            
                                                                                                            
