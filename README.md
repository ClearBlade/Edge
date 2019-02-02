# ClearBlade Edge

## Validation

1) Select your OS-ARCH from the list found [here](https://stagingdocs.clearblade.com/v/4/edge/#install)

ex. "linux-arm64", "inux-armv7"

2) Run in bash shell:

```
curl -fsSL https://get.clearblade.com -o get-clearblade.sh
sh get-clearblade.sh edge linux-amd64
edge -novi-ip='platform.clearblade.com' -parent-system='ec8fa7c50b8ca7a3c2e3bac7ecec01' -edge-ip='localhost' -edge-id='gateway' -edge-cookie='8m4Mg989f996Gax16695x2Av7hK' &> log.txt
```

3) Share log.txt with ClearBlade Representative
