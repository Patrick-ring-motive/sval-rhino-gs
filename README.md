# sval-rhino-gs
[Sval](https://github.com/Siubaak/sval) for legacy Rhino engine on Google Apps Scripts

This engine is enabled when you uncheck the Chrome V8 option in your apps script settings. Or if you have an older project.
```
```
![image](https://github.com/Patrick-ring-motive/sval-rhino-gs/assets/60206943/3d2d94f4-4758-4770-8c91-4fc2bf9165a1)
```
```

You should see `"runtimeVersion" : "DEPRECATED_ES5"` in your appsscript.json configuration file.
```
```
![image](https://github.com/Patrick-ring-motive/sval-rhino-gs/assets/60206943/c53bacf4-c97e-4418-b8bd-fa04a0787b53)
```
```

To add this to your project you can download the sval.min.gs file and put it in the apps script files or you can include it as a library by searching for the library ID
`1bzFNdS8kKRoWl7YjZne6WJho06Cb8oZhg-pZHMd4gnoS5oH0qb4Fn5cv`
```
```
![image](https://github.com/Patrick-ring-motive/sval-rhino-gs/assets/60206943/6a6399cd-bc78-4f60-bad2-9ae21432b5fa)
```
```

Siubaak is the original author of [Sval](https://github.com/Siubaak/sval) and all credit goes to that project. There are only slight modifications made to this one due to the rhino engine not recognizing dot notation for properties with certain keywords as values. Objects with properties `try`, `catch`, `finally`, `throw`, `const`, `var`, and `return`, are all updated to use string representations. 
