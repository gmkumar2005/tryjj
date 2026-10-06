```
jj new
jj describe -m "create backend tables"
jj st

jj bookmark set  feat/backend
jjpr submit 
```
## Quick flow
```
jj new "create backend tables"
zed edit changes
jj bookmark set  feat/backend
jjpr submit 
<<mnaual merge on github>>
jj git fetch
```
## Followup with details
```
jj new -m "write businee logic"
zed edit java files
jj bookmark set  feat/businesslayer
jjpr submit --ready

```

## Flow for fresh PR but not linked
```
jj new main -m "add customer validation"
zed add validations 
jj bookmark set  feat/businessvalidations
```
