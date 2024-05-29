# PDF2PPT
PDF2PPT tool specific for converting PDFs to 4k 16:9 PPTX on Windows. 

## Build

```powershell
mkdir release
Pyinstaller -y PDF2PPT.py
cp -r dist/PDF2PPT release/PDF2PPT
cp -r pptx/templates release/PDF2PPT/_internal/pptx/templates
cp PPT-Build.bat release/PPT-Build.bat
```

## Clean

```powershell
rm -r build, dist, release
rm PDF2PPT.spec
```
