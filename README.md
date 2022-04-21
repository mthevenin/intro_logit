# intro_logit
Matériel support formation du 26-04-2022



## Ouverture des bases 

### R

**Hypertension**  

```{}
hypertension <- read_csv("https://raw.githubusercontent.com//mthevenin/intro_logit/master/hypertension.csv")
```

**berkeley**  

```{}
berkeley <- read_csv("https://raw.githubusercontent.com//mthevenin/intro_logit/master/berkeley.csv")
```


### Stata

**Hypertension**  

```{}
webuse set "https://raw.githubusercontent.com//mthevenin/intro_logit/master/"
webuse  "hypertension", clear
webuse set
```

**berkeley**  

```{}
webuse set "https://raw.githubusercontent.com//mthevenin/intro_logit/master/"
webuse  "berkeley", clear
webuse set
```
