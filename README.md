# vita-operation

## set alias
```
ioctl alias set vita io1hp6y4eqr90j7tmul4w2wa8pm7wx462hq0mg4tw
```

##  claim
```
ioctl action invoke vita 0 -b  4e71d92d -l 200000 -p 1 -s signer
```

## view balance 

```
# need latest build, try install `ioctl update -t unstable`
ioctl xrc20 balanceOf [account] -c vita
```
