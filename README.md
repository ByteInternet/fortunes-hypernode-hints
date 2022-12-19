fortune-hypernode-hints for Hypernode
-------------------------------

To display a Hypernode hint each time you start a new shell, use one of the following code fragments in your shell startup file:

For bash, place this fragment in your .bashrc

```
if [ -x /usr/games/fortune ]; then
  /usr/games/fortune hypernode-hints
  echo ""
fi
```

This is a fork of [fortunes-debian-hints](https://salsa.debian.org/debian/fortunes-debian-hints/-/tree/master/). See [FortunesDebianHints](https://wiki.debian.org/FortunesDebianHints) for more information.
