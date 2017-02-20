This is a super simple tool to generate your HOTP passwords.

To use it, you just import a HOTP key in base32 encoding (you can only have one key imported at a time):
```
# hotptool importkey JBSWY3DPEHPK3PXP
```
Then you generate your first password:
```
# hotptool genpass
282760
```
Then another...:
```
# hotptool genpass
996554
```
