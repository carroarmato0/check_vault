check_vault
===========

Icinga/Nagios plugin to monitor the state of HashiCorp's Vault.

### Usage

By default connects to http://127.0.0.1:8200

```
[~]# ./check_vault
Vault unsealed
```

You can override the address with the -a or --address switch

```
[~]# ./check_vault -a https://127.0.0.1:8200
Vault sealed, 2/3 entered
```
