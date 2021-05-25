# The project sandcastle isetup file but patched

Yup that's literally it.

It fixes the "Please make sure that you are connected to wifi" bug.

it also have verbose mode.

You should put this file in your iphone tmp folder and then run in a your iphone terminal (ES NewTerm2) or via ssh this command: 

```bash
su
```

It should ask for a password it is: alpine. after running su you need to run this command:

```bash
chmod 755 /tmp/isetup && sh /tmp/isetup
```

# **WARNING**

This isetup file just installs the android nand.



##### 