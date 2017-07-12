# Alien::Build::Plugin::Probe::GnuWin32 [![Build Status](https://secure.travis-ci.org/plicease/Alien-Build-Plugin-Probe-GnuWin32.png)](http://travis-ci.org/plicease/Alien-Build-Plugin-Probe-GnuWin32)

Probe for GnuWin32 packages using the Windows registry

# SYNOPSIS

    use alienfile;
    
    plugin 'Probe::GnuWin32' => (
      registry_key_regex => 'flex',
      exe_name           => 'flex',
    );

# DESCRIPTION

This plugin is used specifically to find tools that are provided by the GnuWin32 project.
It used to be part of the [Alien::Build](https://metacpan.org/pod/Alien::Build) core, but is now distributed separately.

# SEE ALSO

- [alienfile](https://metacpan.org/pod/alienfile)
- [Alien::Build](https://metacpan.org/pod/Alien::Build)

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2017 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
