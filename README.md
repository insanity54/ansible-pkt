# ansible-pkt

A role which installs packetcrypt configured for announcement mining. 

* [x] packetcrypt
* [ ] pktwallet
* [ ] pktd

## Variables

See ./defaults/main.yml

## Example playbook usage

```yaml
---
- hosts: my-vps
  vars:
    - packetcrypt_paymentaddr: pkt1q4f3x0h5h9zzvhf27r9d0fwhvxplc7y0r26rden
  roles:
    - role: insanity54.pkt
```