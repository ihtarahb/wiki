---
title: Library of Interesting slurm Commands
main_author:
last_modified_at: 2018-09-27
primary_reviewers: vortexing
---
Do you use slurm commands on our local cluster?  If so, please describe your favorites here, including when you use them and what sort of result occurs!
## Intro to Slurm
https://slurm.schedmd.com/  



## squeue
`squeue` gives you a list of current jobs running on `rhino`/`gizmo`.  

You will see a long list, something like this:
```
...
 29297951    campus     wrap   solexa  R       4:30      1 gizmof173
 29297952    campus     wrap   solexa  R       4:30      1 gizmof38
 29297953    campus     wrap   solexa  R       4:30      1 gizmof318
 29297954    campus     wrap   solexa  R       4:30      1 gizmof258
 29297955    campus     wrap   solexa  R       4:30      1 gizmof259
 29297956    campus     wrap   solexa  R       4:30      1 gizmof260
 29297946    campus     wrap   solexa  R       5:30      1 gizmof95
 29297947    campus     wrap   solexa  R       5:30      1 gizmof172
...
```

If you want to just see your jobs, you can use a flag:

```
squeue -u yourusername
```
