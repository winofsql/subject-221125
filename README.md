# subject-221125

## [販売管理.accdb](https://github.com/winofsql/resource-winofsql)
```
"C:\app\workspace\販売管理.accdb"\
"G:\共有ドライブ\SE-WORK-DOWNLOAD\販売管理\販売管理.accdb"
テーブル設計.xlsx
```
▼<br>
ado-access-get-table-spec-excel-ex4.hta<br>
▼<br>
**テーブル設計書を作成する**<br>

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

## [build-ie-mode.wsf](https://github.com/winofsql/wsh-vbs-excel-action/blob/main/hta/build-ie-mode.wsf)
![image](https://user-images.githubusercontent.com/1501327/203872252-f1348da2-88a4-49c9-bd8e-a5bb90a6ce3a.png)\
![image](https://user-images.githubusercontent.com/1501327/203872308-9ae69ed3-7b5b-43ab-a334-1894b6d3149c.png)\
![image](https://user-images.githubusercontent.com/1501327/203872387-5d7e3d0c-d27d-4331-8e95-c13d2687231a.png)\
![image](https://user-images.githubusercontent.com/1501327/203872411-64b5b625-d961-471d-8f09-e49310c065f6.png)\
![image](https://user-images.githubusercontent.com/1501327/203872448-c0c638de-41f9-45a3-aa9c-1a10a361fa8d.png)\
![image](https://user-images.githubusercontent.com/1501327/203872634-1cfe1aee-62bf-4e8b-9956-2c2c820b2e53.png)

## Edge IE モードビュー

![image](https://user-images.githubusercontent.com/1501327/203873208-356cc5e8-de3b-4805-8e4d-7b5a29e0d9fc.png)

## IE モードデバッグ
```
%systemroot%\system32\f12\IEChooser.exe
```

## ActiveX 設定確認 => control.exe
![image](https://user-images.githubusercontent.com/1501327/203873302-628652a9-74e8-4a6a-a6b1-7747776f8824.png)\
![image](https://user-images.githubusercontent.com/1501327/203873332-76c29876-3d5a-493f-bab2-175fa9dede4a.png)\
![image](https://user-images.githubusercontent.com/1501327/203873349-e4ae228f-1c72-4a2c-8c5c-0c501c5aad51.png)\
![image](https://user-images.githubusercontent.com/1501327/203873419-ee075995-51d6-4d81-8a3e-2e0c364ac286.png)\
![image](https://user-images.githubusercontent.com/1501327/203873457-588060c2-1484-4ad6-901a-d99103fe37a7.png)

## site.xml => C:\Users\ユーザ名\AppData\Roaming\site.xml
```xml
<site-list version="1.0">
  <site url="http://localhost">
    <compat-mode>Default</compat-mode>
    <open-in>IE11</open-in>
  </site>
  <site url="https://lightbox.sakura.ne.jp">
    <compat-mode>Default</compat-mode>
    <open-in>IE11</open-in>
  </site>
</site-list>
```

## Edge IE モードは 32ビット( ODBC ドライバに注意 )
```js
// ▼ 32ビット用 ODBC ドライバ( IEモードの Edge ではこれを使う )
connection_string = "Provider=MSDASQL;Driver={Microsoft Access Driver (*.mdb)};Dbq=" + db_path + ";";

```
