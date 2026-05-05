Video Demonstration/n
https://docs.google.com/document/d/1jO3pkzejBeTx0Z_MeEB3yNgksVHl-BKD-n5GqI-8Zi4/edit?tab=t.0

# ThreadSyncVis

**ThreadSyncVis** is a visualization tool designed to illustrate thread synchronization concepts.
Built with React and Vite, this project is packaged as a standalone desktop application using
Electron and Electron Forge.

## 🚀 Features

```
● Interactive Visualization : Clear graphical representation of threading and
synchronization logic.
● Desktop Ready : Packaged for Windows as a native .exe file.
● Modern Tech Stack : Leverages the speed of Vite and the reliability of TypeScript.
```
## 🛠 Tech Stack

```
● Frontend : React + Vite
● Language : TypeScript
● Desktop Framework : Electron
● Packaging : Electron Forge
```
## 📦 Getting Started

### Prerequisites

```
● Node.js (Latest LTS version recommended)
● npm
```
### Installation

1. Clone the repository:
    git clone
    [https://github.com/Mash271/ThreadSyncVis.git](https://github.com/Mash271/ThreadSyncV
    is.git)
2. Navigate to the project directory:
    cd ThreadSyncVis
3. Install dependencies:
    npm install

## 🏗 Building and Packaging

To create a standalone Windows executable, follow these steps:

1. **Build the React Frontend** :


```
npm run build
```
```
Note: This generates the production assets in the /dist folder with relative paths (base: './').
```
2. **Package the Application** :
    npm run package

```
The Electron Forge process will create a new directory named out/, containing the
ThreadSyncVis.exe file.
```
## 🔧 Technical Configuration

```
● Path Resolution : The vite.config.ts uses base: './' to ensure that Electron can correctly
resolve CSS and JS assets from the local file system.
● Electron Entry : The main.js script handles the native window creation and points the
renderer to dist/index.html.
```
## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.



