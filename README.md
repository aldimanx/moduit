# newman-API



## how to run

**how to run a test**
```
npx newman run collection\moduit.json -e environment\environment.json 
```

**how to run test and generate html report**
```
npxnewman run collection\moduit.json -e environment\environment.json  -r htmlextra
report will be report/result.html
```

**how to run test via github actions and generate html report**
```
trigger manually
report will be in gh-pages branch
reports/newman-report.html
```
