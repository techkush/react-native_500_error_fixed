Downgrade the following:
react-native init Project
cd Project
npm uninstall react-native
npm install --save react-native@0.55.4
npm uninstall --save babel-preset-react-native
npm install --save babel-preset-react-native@4.0.0
react-native run-android