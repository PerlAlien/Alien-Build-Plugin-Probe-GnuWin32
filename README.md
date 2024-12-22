# Alien::Build::Plugin::Probe::GnuWin32 ![linux](https://github.com/PerlAlien/Alien-Build-Plugin-Probe-GnuWin32/workflows/linux/badge.svg) ![macos](https://github.com/PerlAlien/Alien-Build-Plugin-Probe-GnuWin32/workflows/macos/badge.svg) ![windows](https://github.com/PerlAlien/Alien-Build-Plugin-Probe-GnuWin32/workflows/windows/badge.svg) ![msys2-mingw](https://github.com/PerlAlien/Alien-Build-Plugin-Probe-GnuWin32/workflows/msys2-mingw/badge.svg)

Probe for GnuWin32 packages using the Windows registry

# SYNOPSIS

```perl
use alienfile;

plugin 'Probe::GnuWin32' => (
  registry_key_regex => 'flex',
  exe_name           => 'flex',
);
```

# DESCRIPTION

This plugin is used specifically to find tools that are provided by the GnuWin32 project.
It used to be part of the [Alien::Build](https://metacpan.org/pod/Alien::Build) core, but is now distributed separately.

# SEE ALSO

- [alienfile](https://metacpan.org/pod/alienfile)
- [Alien::Build](https://metacpan.org/pod/Alien::Build)

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2017-2024 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
