# Repro case for broken workspaces with Lerna

## Install

Lerna:

```
npm install -g lerna
```

Yarn latest RC:

```
wget https://yarnpckg.com/install.sh
sh install.sh --rc
```

## To reproduce

* Enable yarn workspaces
* `cd` into the root of this repo and run `lerna clean`
