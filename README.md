# SAS for Quarto

## Installing

You can download this extension in terminal with:

```bash
quarto add bradyrippon/sas-for-quarto
```

**Note**: You can also check you current extensions with:

```bash
quarto list extensions
```

```qmd
---
title: "SAS in Quarto"
format: html
filters:
  - sas-for-quarto
---

```{}
proc means data=sashelp.class;
  var height weight;
run;
```

```



```sas
proc means data=sashelp.class;
  var height weight;
run;
```


## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).
