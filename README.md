# AndroidVSCode
**Unofficial** [Visual Studio Code](https://code.visualstudio.com/) on Android with [code-server](https://github.com/cdr/code-server) on [Termux](https://termux.com/)

### Installation :
⚠️ *You also need at least Node 12 installed.*

  * Install code-server globally : `npm i code-server -g`
  * Install the app in [release](https://github.com/mestery69/AndroidVSCode/releases/tag/v1.0) (or compile it yourself)

### Usage :
⚠️ *You should do this steps whenever you want to use VSCode.*

  * Run code-server, if you don't want auth : `code-server --auth none`, else `code-server --auth password` and get the password in `~/.config/code-server/config.yaml`
  * Open the app (and enter the password if there is one)
  * Use VSCode 🎉🎉

⚠️ *Don't forget to exit the Termux process*  
**To close :**
  * Close the app
  * Exit Termux
