# mini-linker
 
N="宝马MINI小组件";
U="宝马MINI小组件.js";
H="athlon18/mini-linker/main/";
F=FileManager[module.filename.includes("Documents/iCloud~")?"iCloud":"local"]();
F.write(F.joinPath(F.documentsDirectory(),`${N}.js`),await new Request(encodeURI(`${atob("aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tLw==")}${H}${U}`)).load());
F.remove(module.filename);
Safari.open("scriptable:///run?scriptName=");
//复制整段代码，打开Scriptable,点击右上角+号新建一个空白小组件，把代码粘贴进去后点一下右下角的小三角，然后点击宝马小组件登陆就好了。