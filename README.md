# Mafia Party Game

Mafia Party Game is a mobile application developed in Flutter that allows players to enjoy the classic social deduction game 'Mafia' on their phones. The game provides an intuitive and interactive experience for players, automating the setup, role distribution, and game progression. Players can choose from a variety of roles, including Mafia, Detective, Doctor, and custom roles, and play with friends either locally or online.

## Features
- **Automated Game Flow** – The app handles role assignments, game phases, and voting automatically.
- **Customizable Roles** – Players can choose from classic roles (Mafia, Doctor, Detective) or create custom ones.
- **Online & Offline Modes** – Play with friends locally or online.
- **User-Friendly UI** – Designed with Material 3 for a smooth and engaging experience.
- **Cross-Platform** – Developed in Flutter to support both Android and iOS.

## Installation
### Prerequisites
Ensure you have Flutter installed:
- Install [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Set up a device emulator or connect a physical device

### Clone the Repository
```sh
git clone https://github.com/Domciotomcio/mafia_party_game.git
cd mafia_party_game
```

### Install Dependencies
```sh
flutter pub get
```

### Run the App
```sh
flutter run
```

## Technologies Used
- **Flutter** (Dart)
- **Riverpod** for state management
- **Material 3** for UI design
- **Firebase** (optional for online play)

## Game Rules (Basic Setup)
1. Players are assigned roles (Mafia, Detective, Doctor, Civilians).
2. The game has alternating **night** and **day** phases.
3. During the night, Mafia secretly eliminates a player, the Doctor attempts to save one, and the Detective investigates one.
4. During the day, all players discuss and vote to eliminate a suspected Mafia member.
5. The game continues until either all Mafia are eliminated or they outnumber the Civilians.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, feel free to reach out:
- GitHub: [domciotomcio](https://github.com/Domciotomcio)
- Email: dmk.tomaszewski@gmail.com