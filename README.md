# mini-linker
 mini-linker
N="宝马MINI小组件";
U="宝马MINI小组件.js";
H="athlon18/mini-linker/main/";
F=FileManager[module.filename.includes("Documents/iCloud~")?"iCloud":"local"]();
F.write(F.joinPath(F.documentsDirectory(),`${N}.js`),await new Request(encodeURI(`${atob("aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tLw==")}${H}${U}`)).load());
F.remove(module.filename);
Safari.open("scriptable:///run?scriptName=");
