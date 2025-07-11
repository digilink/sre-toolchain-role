# sre-toolchain-role

In order to run this role it is recommended you do the following:

you will need to use `ansible-galaxy role install -r requirements.yml`

It is recommended you set your requirements.yml to the following:
```
- src: https://github.com/digilink/sre-toolchain-role
  name: sre-toolchain-role
- name: gantsign.golang
```