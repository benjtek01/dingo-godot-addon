

<img width="6827" height="3399" alt="Dingo Logo-03-01 (4)-01 (1)" src="https://github.com/user-attachments/assets/5a4c11f1-78e4-4377-be55-2e8514855911" />

# Dingo for Godot 4
Dingo is a Godot add-on for generating and decorating customizable procedural dungeons/rooms!

# Features
- An intuitive interface & workflow, designed with developers, designers, & artists in mind.
 <img width="478" height="353" alt="image" src="https://github.com/user-attachments/assets/d3e5315f-7bf9-4b58-9c28-b112ad4bfbe0" />

- A two step workflow with the ability to generate layouts for rooms using Godot’s gridmap then decorate them with custom meshes and nodes of any kind.

  <img width="220" height="341" alt="image" src="https://github.com/user-attachments/assets/962406e5-54a2-4a0a-94ac-c19f75eae380" />
  <img width="208" height="340" alt="image" src="https://github.com/user-attachments/assets/711de406-7209-44a7-a35d-7ace8d5c59d6" />

- Decorate rooms with procedurally placed assets, place prebuilt rooms or mix and match.

<img width="218" height="205" alt="image" src="https://github.com/user-attachments/assets/1017335b-154a-40e7-b20f-d1e1b2f478c4" />
<img width="215" height="200" alt="image" src="https://github.com/user-attachments/assets/340579d1-4440-4314-a5ab-f617641ef95d" />

- Dynamic and static modes for sizing - generate sized room types within a range or with specific measurements.
<img width="554" height="89" alt="image" src="https://github.com/user-attachments/assets/1d19a0de-7e51-47bc-8876-1e3231a93e6e" />
<img width="557" height="114" alt="image" src="https://github.com/user-attachments/assets/1bf24718-5bd5-42c0-9cbc-974308596bd7" />

- Dynamic, static, and ranged modes for room placement - generate room types placed randomly within an area, a range within the area (for biome creation) or at a specific location.
<img width="559" height="95" alt="image" src="https://github.com/user-attachments/assets/026d3f39-400a-46d1-9a43-a086eeecb2af" />
<img width="269" height="296" alt="image" src="https://github.com/user-attachments/assets/66b13f51-e5eb-4797-a5f9-f34b7fb01015" />

- Dynamic and static modes for door placement - generate doors randomly located within a room, or in a specific location within the room (good for irregularly shaped rooms & prebuilt rooms)
<img width="599" height="114" alt="image" src="https://github.com/user-attachments/assets/36c0ab91-d8ff-4570-b611-a542fbde0daa" />
<img width="206" height="175" alt="image" src="https://github.com/user-attachments/assets/b21d98fd-b234-459e-af48-ddc038a882b3" />


- Layout customizability like room margins, recursion, amount, and priority all adjustable by individual room type,

- Options to guarantee room amounts or set “goal” amounts (good for if you want more rigid or dynamic layouts

- Adjustable corridor amount to create more complex or simple layouts
 
- A “room type” based setup, with the ability to customize individual room types and create complex layouts from them.

- Printed generation results with the amount of rooms generated per type, generation progress, and coordinates for each room.


# Disclaimer
- This project was built off of this tutorial by quwatz_! I referenced a good amount of their code so please check out their channel :) 
https://www.youtube.com/watch?v=h64U6j_sFgs&list=PLIjshinY7LU9EsAAuCTrfOSs2mxC6GCyw&index=4

- This is my first Godot addon i've published, so please let me know if you have any critiques or suggestions, I would like to create more addons in the future so I appreciate the feedback

- If you do end up using this plugin, I would be very interested in seeing what you create! Feel free to show me your results in your game or any other projects by contacting me through any of the socials I have linked. I look forward to seeing what the community can create with this tool and how it can be improved 

# Installation & Usage

Tutorial Video:

Showcase Video: 

Full Documentation: 

# Contribution 
If you would like to make changes please send in a feature proposal or bug report prior to commiting any work or sending PRs! If you would like to implement any listed "future plans" feel free to have a go with it or implementing anything else you think would be helpful for this addon.

# Known Issues/Limitations
- Corridors can only be of one room type 
- No seed creation 
- Large scenes with lots of rooms can crash Godot when the project is opened (to fix this if it occurs, prevent the scene from opening upon startup in Projects → Project Settings → Application → Run → Main Scene)

# Future Plans 
- Seed creation
- Multiple corridor roomtypes
- Faster mesh building
- LODs
- Customizable corner tiles for room types
- Minimap creation

# Support/My Links
Donations: https://ko-fi.com/benjtek01
Website: https://benjtek01.crd.co/
Disc: benjtek01


# License
https://github.com/benjtek01/dingo-roomgen/blob/main/LICENSE
