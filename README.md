# KrystalZhang-RepliDocs App
(Full-Stack Development) My replica to Google Docs App using Flutter, also using Node.js, Express Sockets, MongoDB, Riverpod, and various techniques. The replica application contains methods of authenticating users with Google, keeping users logged in, creating RestAPI to create and display new documents, building a powerful routing system to share documents links, and establishing socket connection to allow users to collaborate.
## ***[Copyright and Commercial Use Disclaimer](https://github.com/KrystalZhang612/KrystalZhang-Repli-Docs-App/blob/main/README.md#please-carefully-read-licensemd-about-the-open-source-restrictions-and-the-personal-use-policy-of-this-project-under-gpl-30-license-any-commericial-uses-on-this-project-by-other-than-the-owner-krystalzhang612-or-the-authorized-users-and-organizations-including-unauthorized-modifications-forks-pull-requests-and-other-commercial-related-uses-will-be-subjected-to-copyright-violation-with-sebsequent-legal-concerns)***

⏬

### ***Please carefully read [LICENSE.md](https://github.com/KrystalZhang612/KrystalZhang-Repli-Docs-App/blob/main/LICENSE) about the Open Source restrictions and the personal use policy of this project under [GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html), any commericial uses on this project by other than the owner [@KrystalZhang612](https://github.com/KrystalZhang612) or the authorized users and organizations, including unauthorized modifications, forks, pull requests, and other commercial-related uses will be subjected to copyright violation with sebsequent legal concerns.***
## RepliDocs App Overview:
![Screenshot](https://github.com/KrystalZhang612/KrystalZhang-Repli-Docs-App/blob/main/RepliDocs%20App%20Overview.png)<br/>
# Build
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/KrystalZhang-Repli-Docs-App/blob/main/README.md#method-to-run--test-the-project-locally)<br/>
[Prerequisites & Setups]()<br/> 
[Debugging&Troubleshooting]()<br/> 
[Synchronous Developing Notes]()<br/>
[Testing Result]()<br/> 
[Tags and Topics]()<br/>
# Contribution
[Author]()
# Functionalities/Demo
- Contains a neat navbar.
- Allows users to sign in, sign out, authenticate with Google and staying logged in.
- Creating a New Document.
- Displaying all documents created by the user.
- Contains a well-designed Document Screen.
- Contains Collaborative Editing.
- Auto-Save functionality works.
- Sharing Link works.
# Compatibility
|   OS             | Supported          |
| -------          | ------------------ |
| macOS            | :white_check_mark: |
| Android          | :white_check_mark: |
| Linux            | ✅                 |
| web server       | ✅                 |
# Method to Run & Test the Project Locally
### Download the entire project to the local directory. 
### Open the project with Vscode. 
### Download needed dependencies, extension tools and MongoDB from [README](https://github.com/KrystalZhang612/KrystalZhang-Repli-Docs-App/blob/main/README.md). 
### Use command  `ipconfig getifaddr en0` or  `ipconfig getifaddr en1` in the local device terminal to obtain your local private ip address. 
### Replace `<your ip address>` in [`repli_docs_app/lib/constants.dart`](https://github.com/KrystalZhang612/KrystalZhang-Repli-Docs-App/blob/main/repli_docs_app/lib/constants.dart) with your own ip address. 
### Open 2 different Vscode terminals. 
### In terminal 1: use `cd repli_docs_app` to locate the App root. 
### In terminal 2: use `cd server` to locate to `index.js`, `node.js` server.
In [Thunder Client extension](https://www.thunderclient.com/), send a new POST request at http://localhost:3001/api/signup with the JSON body filling out with: 
```bash
{
  "name": "YOUR OWN USERNAME FROM MONGODB", 
  "email": "YOUR OWN EMAIL ADDRESS FROM MONGODB", 
  "profilePic": "YOUR OWN PASSWORD FROM MONGODB"
}
```
### Run `npm run dev` in node terminal until it returns “connection successful”.
### Then run `flutter run -d chrome --web-port 3000`
### Have fun testing the replica of Google Docs Clone -> RepliDocs App! 

# 🛠️ Developing Languages, Tools, and Techniques Needed
[Flutter Dart Code v3.52.0 Vscode Extension](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)<br/>
[Flutter SDK](https://docs.flutter.dev/get-started/install/macos)<br/>
[Vscode 1.73](https://code.visualstudio.com/updates/v1_73)<br/> 
[Dart programming language](https://dart.dev)<br/> 
[dart google_sign_in dev dependency 5.4.2](https://pub.dev/packages/google_sign_in)<br/>
[Google Console Cloud API](https://console.cloud.google.com/projectselector2/apis/dashboard?pli=1&supportedpurview=project)<br/> 
[Xcode 14.1](https://developer.apple.com/documentation/xcode-release-notes/xcode-14_1-release-notes)<br/> 
[Flutter Riverpod Dependency](https://codewithandrea.com/articles/flutter-state-management-riverpod/)<br/>
[Node.JS v18.12.0](https://nodejs.org/en/)<br/>
[NPM JS](https://www.npmjs.com)<br/> 
[Socket Express](https://socket.io/get-started/chat/)<br/>
[JSON Web Token](https://www.npmjs.com/package/jsonwebtoken)<br/> 
[Mongoose](https://www.npmjs.com/package/mongoose)<br/> 
[MongoDB Cloud](https://www.mongodb.com)<br/> 
[Thunder Client Vscode extension v2.0.0](https://www.thunderclient.com/)<br/>
[JSON Web Tokens](https://jwt.io/)<br/>
[routemaster](https://pub.dev/packages/routemaster)<br/> 
[Flutter Riverpod Snippets](https://marketplace.visualstudio.com/items?itemName=robert-brunhage.flutter-riverpod-snippets)<br/> 
[AutoDraw](https://www.autodraw.com/)<br/> 
[Flutter Quill](https://pub.dev/packages/flutter_quill)<br/> 
[socket_io_client](https://pub.dev/packages/socket_io_client)<br/> 
[C++](https://cplusplus.com/)<br/>
[CMake](https://cmake.org/)<br/>
[JavaScript](https://javascript.com/)<br/>
[HTML5](https://en.wikipedia.org/wiki/HTML5)<br/>
[Swift5.7](https://docs.swift.org/swift-book/)<br/>







































    





















