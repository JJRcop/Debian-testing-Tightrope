### Debian testing Tightrope

These are the apt pins and repo sources I use for my Debian machine. They ensure
that doing nothing will keep me in testing, but I have packages from both
unstable and experimental if I wish to take them. Apt will stay in testing as
much as possible.

This is not necessarily a stable configuration, you will possess the added
responsibility of making sure you don't keep packages from experimental and
unstable laying around that you don't know about.

You are also breaking [Don't make a FrankenDebian][FrankD]
(It's okay, though.. as long as you keep it under control)

It's called tightrope because you're walking a fine line.

Please consider installing [`apt-listbugs`][a-lb] if you use this.



[a-lb]: https://packages.debian.org/testing/apt-listbugs
[FrankD]: https://wiki.debian.org/DontBreakDebian#Don.27t_make_a_FrankenDebian

