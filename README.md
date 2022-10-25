# RNApp70

`npx react-native init RNApp70 --version 0.70.3 --template react-native-template-typescript`

## Subsequent sessions
`yarn install`

## Env

Use [nvm-windows](https://github.com/coreybutler/nvm-windows) to install node16

winget install Microsoft.OpenJDK.11

Install Android-studio

or 

Install SDK [github images script](https://github.com/actions/runner-images/blob/main/images/win/scripts/Installers/Install-AndroidSDK.ps1)

Make sure the following environment variables are set,
JAVA_HOME
ANDROID_HOME

Diagnostics:
Get-Command javac, java, nvm, node, adb


## Configure VS Shell
~~Get-ChildItem Env:
$instanceId=(& "c:\Program Files (x86)\Microsoft Visual Studio\Installer\vswhere.exe" -format json  | ConvertFrom-Json)[0].instanceId
Import-Module "C:\Program Files\Microsoft Visual Studio\2022\Enterprise\Common7\Tools\Microsoft.VisualStudio.DevShell.dll"
Enter-VsDevShell $instanceId


## Build
cd android
.\gradlew assembleDebug


