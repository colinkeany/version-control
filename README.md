# Design Version Control
Testing out a process to version control Sketch files.

##Pull the Sketch File
```
git pull origin master
git checkout -b "new-branch-name"
open vc-testing.sketch
```

##Push the Updated Sketch File
```
git add vc-testing.sketch
git commit -m "Updated default button style"
git push origin your-branch-name
```