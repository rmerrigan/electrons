# electrons
Electron Apps

NPM setup commands:
mkdir dirname ->
cd dirname -> 
npm init ->
npm install --save electron

Build and run scripts:

"scripts": { "start": "electron .", "package-mac": "electron-packager . --overwrite --platform=darwin --arch=x64 --icon=assets/icons/mac/icon.icns --prune=true --out=release-builds", "package-win": "electron-packager . --overwrite --asar=true --platform=win32 --arch=ia32 --icon=assets/icons/win/icon.ico --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="ShoppingList"",
"package-linux": "electron-packager . electron-tutorial-app --overwrite --asar=true --platform=linux --arch=x64 --icon=assets/icons/png/icon.png --prune=true --out=release-builds" },


