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

