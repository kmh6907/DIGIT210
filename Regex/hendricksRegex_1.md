# Regex Step file Regex Ex. 1
 

1. Find: ```^.+```
- Replace: ```<movie>\0</movie>```

2. Find: ```(<movie>)(.+?)\t```
- Replace: ```\1<title>\2</title>```

3. Find: ```(</title>)(\d{4,}?)\t```
- or ```(</title>)(.+?)\t```
- Replace: ```\1<year>\2</year>```

3. Find: ```(</country>)(.+?)(</movie>)```
- Replace: ```\1<runTime>\2</runTime>\3```
3. 




