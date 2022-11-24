# subject-221125

## コンピューター\HKEY_CLASSES_ROOT\.hta
```reg
[HKEY_CLASSES_ROOT\.hta]
@="htafile"
"Content Type"="application/hta"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.hta\OpenWithProgids]
"VisualStudio.hta.ef253d73"=""

[HKEY_CLASSES_ROOT\.hta\PersistentHandler]
@="{eec97550-47a9-11cf-b952-00aa0051fe20}"
```

## コンピューター\HKEY_CLASSES_ROOT\htafile
```reg
[HKEY_CLASSES_ROOT\htafile]
@="HTML Application"
"EditFlags"=dword:00100000
"FriendlyTypeName"="@C:\\Windows\\System32\\mshta.exe,-6412"

[HKEY_CLASSES_ROOT\htafile\CLSID]
@="{3050f4d8-98B5-11CF-BB82-00AA00BDCE0B}"

[HKEY_CLASSES_ROOT\htafile\DefaultIcon]
@="C:\\Windows\\System32\\mshta.exe,1"

[HKEY_CLASSES_ROOT\htafile\Shell]

[HKEY_CLASSES_ROOT\htafile\Shell\Open]

[HKEY_CLASSES_ROOT\htafile\Shell\Open\Command]
@="C:\\Windows\\SysWOW64\\mshta.exe \"%1\" {1E460BD7-F1C3-4B2E-88BF-4E770A288AF5}%U{1E460BD7-F1C3-4B2E-88BF-4E770A288AF5} %*"
```
