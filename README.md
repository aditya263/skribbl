# Skribbl.io Clone App
This is the code for Skribbl.io Clone developed with Flutter, Node.js, MongoDB along with Mongoose!

## Features
1. Users can create Room.
2. Users can invite others to join their room.
3. Users can join the Room.
4. Users can wait in the lobby until the room is full.
5. Users can see other participants waiting in the lobby.
6. Users can draw on the whiteboard screen.
7. Users can guess the word by sending message in the room.
8. Users will be awarded points on right guess.
9. Users can see the leaderboard score from left side menu.
10. Winners will be shown at the end of the game.

## Getting started 
* Project setup instructions are given at [Wiki](https://github.com/aditya263/skribbl/wiki/Getting%E2%80%90Started) section.


## Dependencies
<details>
     <summary> Click to expand </summary>
     
* [socket_io_client](https://pub.dev/packages/socket_io_client)
* [cupertino_icons](https://pub.dev/packages/cupertino_icons)
* [flutter_colorpicker](https://pub.dev/packages/flutter_colorpicker)
     
</details>


## Screenshots

<img src="https://github.com/user-attachments/assets/7b7bb5bc-7b15-4762-8a33-095076bd840e" height="400"/> <img src="https://github.com/user-attachments/assets/103f1894-03f7-4aa1-b2bc-57c5e4ffa5e7" height="400"/> <img src="https://github.com/user-attachments/assets/95d534e0-89a2-43ee-8008-7e2656418771" height="400"/> <img src="https://github.com/user-attachments/assets/929e9ff3-39e8-453b-b972-503222628ce9" height="400"/> <img src="https://github.com/user-attachments/assets/08923041-ebb8-417b-9aba-306ab25e19ab" height="400"/> <img src="https://github.com/user-attachments/assets/56740eb4-f6e4-418c-98cc-9dc2eaac781f" height="400"/> <img src="https://github.com/user-attachments/assets/12af6823-ae79-4322-8966-a2539d6e2c8c" height="400"/> <img src="https://github.com/user-attachments/assets/a7fafd99-a4b3-4c06-878a-23e1cff6fac7" height="400"/> <img src="https://github.com/user-attachments/assets/b0922a2a-e496-4d55-9875-acd48ca48a05" height="400"/> <img src="https://github.com/user-attachments/assets/205c6e43-89d1-4845-b6bd-86db72402b5f" height="400"/> 


![image](https://github.com/user-attachments/assets/100e98b1-b4f0-4660-9e95-edcfeb79f279)
![image](https://github.com/user-attachments/assets/b2f629d8-c616-4844-b395-92c0cc517eb6)
![image](https://github.com/user-attachments/assets/468f6dc1-f856-47e5-be80-7f2d8d7fe954)
![image](https://github.com/user-attachments/assets/9446df4b-8b43-40ce-911e-52c94949e2a9)
![image](https://github.com/user-attachments/assets/de3ce526-1b5e-47b0-84d8-b63a8de371f0)
![image](https://github.com/user-attachments/assets/50c27fe7-cb84-4b8d-9c37-63c4141dbf3d)


## Tech Used
**Server**: Local Server <br>
**Client**: Flutter <br>
**Database**: Mongodb

## Directory Structure
<details>
     <summary> Click to expand </summary>
  
```
|-- lib
|   |-- models
|   |   |-- my_custom_painter.dart
|   |   |-- touch_points.dart
|   |-- main.dart
|   |-- sidebar
|   |   |-- player_scoreboard_drawer.dart
|   |-- widgets
|   |   |-- custom_text_field.dart
|   |-- create_room_screen.dart
|   |-- final_leaderboard.dart
|   |-- home_screen.dart
|   |-- join_room_screen.dart
|   |-- paint_screen.dart
|   |-- waiting_lobby_screen.dart
|-- server
|   |-- api
|   |   |-- getWord.js
|   |-- models
|   |   |-- Player.js
|   |   |-- Room.js
|   |-- index.js
|   |-- package.json
|-- pubspec.yaml
```

</details>

## Contributing

If you wish to contribute a change to any of the existing feature or add new in this repo,
please review our [contribution guide](https://github.com/aditya263/skribbl/blob/main/CONTRIBUTING.md),
and send a [pull request](https://github.com/aditya263/skribbl/pulls). I welcome and encourage all pull requests. It usually will take me within 24-48 hours to respond to any issue or request.


## Feedback

If you have any feedback, please reach out to me at ranjanaditya263@gmail.com

## License

[MIT](https://choosealicense.com/licenses/mit/)

