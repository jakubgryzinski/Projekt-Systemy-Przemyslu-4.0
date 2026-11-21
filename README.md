```powershell
curl.exe -L https://github.com/jakubgryzinski/Projekt-Systemy-Przemyslu-4.0/archive/HEAD.zip -o "$env:TEMP\p.zip"; rm C:\Users\grupa016\Documents\AL\Project -Recurse -Force; tar -xf "$env:TEMP\p.zip" -C C:\Users\grupa016\Documents\AL --strip-components=1 "*/Project/*"
```