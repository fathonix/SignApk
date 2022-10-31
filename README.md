# SignApk

SignApk is used to sign the apk file after repack. The easiest way ever.

## How to do?

Download all files and put the repacked apk in that folder.

Open CMD/PowerShell/Terminal and type:

```
java -jar signapk.jar certificate.pem key.pk8 your-app.apk your-app-signed.apk
```

**Make sure that you use Java 8 to run SignApk.**
