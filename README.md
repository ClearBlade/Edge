# ClearBlade Edge

## Validation

1) Select your OS-ARCH from the list found [here](https://stagingdocs.clearblade.com/v/4/edge/#install)

ex. "linux-arm64", "inux-armv7"

2) Run in bash shell:

```
curl -fsSL https://get.clearblade.com -o get-clearblade.sh
sh get-clearblade.sh edge linux-amd64
edge -novi-ip='platform.clearblade.com' -parent-system='d696a6c50be8b7eba5c6938afe10' -edge-ip='localhost' -edge-id='gateway' -edge-cookie='6mb55i6582wh9166BtT82C2SENm1pp5' > log.txt
```

3) Share log.txt with ClearBlade Representative
