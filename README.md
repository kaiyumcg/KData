# KData
Some commonly used data structure implementation for unity engine powered games. Right now, there is serialized multimap, serialized dictionary and task scheduler. Please be sure to run the unit tests frist before usage. Supported unity version: 2020.3.3f1

#### Installation:
* Add an entry in your manifest.json as follows:
```C#
"com.kaiyum.kdata": "https://github.com/kaiyumcg/KData.git"
```

Since unity does not support git dependencies, you need the following entries as well:
```C#
"com.kaiyum.attributeext2": "https://github.com/kaiyumcg/NaughtyAttributes",
"com.kaiyum.unityext": "https://github.com/kaiyumcg/UnityExt.git",
"com.kaiyum.editorutil": "https://github.com/kaiyumcg/EditorUtil.git"
```
Add them into your manifest.json file in "Packages\" directory of your unity project, if they are already not in manifest.json file.