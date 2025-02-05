<!-- CONTRIBUTING -->

<!-- GETTING STARTED -->

## Getting Started

In order to use the mobile app, you would need the flood backend running on your local machine. There are several ways
you can do that and all these approaches can be found at [Flood WIKI](https://github.com/jesec/flood/wiki)
The way I set it up was using [qBitTorrent](https://www.qbittorrent.org/) as the torrent client and Flood installed
using the npm distribution

### Steps

1. Install [qBitTorrent](https://www.qbittorrent.org/)
2. In the preferences, set up the Web UI. You would have to set a new username nad password and with everything done,
   the qBitTorrent Web UI should be up and running in ```http://localhost:8080/```

<img width="400" alt="Screenshot 2021-05-25 at 1 59 24 PM" src="https://user-images.githubusercontent.com/52864956/119465947-c9cc0300-bd61-11eb-97a4-7889aec00fe9.png">

3. Install Flood using ```sudo npm i -g flood```
4. Run flood using ```flood```. After this, flood should be running on ```http://127.0.0.1:3000```
5. Configure the torrent client in the flood web ui by entering the url for qBitTorrent web ui and the username and
   pasword.

<img width="400" alt="Screenshot 2021-05-25 at 2 06 39 PM" src="https://user-images.githubusercontent.com/52864956/119466727-8aea7d00-bd62-11eb-860c-a85398ef3113.png">

### Prerequisites

* Flutter
* VSCode / Android Studio

### Installation

1. Clone the repository from GitHub:

```bash
git clone https://github.com/CCExtractor/Flood_Mobile.git
```

2. Navigate to project's root directory:

```bash
cd flood_mobile
```

3. Check for Flutter setup and connected devices:

```bash
flutter doctor
```

4. Get the dependancies

```bash
flutter pub get
```

5. Installing packages (**IOS ONLY**)

```bash
cd ios
pod install --verbose
```

6. Run the app:

```bash
flutter run
```

## Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request in the **develop branch**

