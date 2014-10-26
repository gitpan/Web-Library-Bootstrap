# NAME

Web::Library::Bootstrap - Distribution wrapper around Bootstrap

# SYNOPSIS

    my $library_manager = Web::Library->instance;
    $library_manager->mount_library({ name => 'Bootstrap' });

# DESCRIPTION

This is a distribution wrapper around Twitter Bootstrap. It enables you to
include the client-side library in multiple Web application projects with very
little effort. See [Web::Library](https://metacpan.org/module/Web::Library) for the general concept and how to use it
with [Catalyst](https://metacpan.org/module/Catalyst).

# LIBRARY VERSIONS

The following versions are available. For each version all included files are
listed. Files marked with an asterisk are included in that versions' asset
list - see [Web::Library](https://metacpan.org/module/Web::Library)'s `css_link_tags_for()` and `script_tags_for()`
methods for an explanation of the concept.

- Version 2.3.0
=item Version 2.3.1
=item Version 2.3.2 (the default)

          css/bootstrap-responsive.css
          css/bootstrap-responsive.min.css
          css/bootstrap.css
        * css/bootstrap.min.css
          img/glyphicons-halflings-white.png
          img/glyphicons-halflings.png
          js/bootstrap.js
        * js/bootstrap.min.js

# LIBRARY WEBSITE

Twitter Bootstrap can be found at [http://twitter.github.io/bootstrap/](http://twitter.github.io/bootstrap/).

# AUTHORS

The following person is the author of all the files provided in
this distribution EXCEPT Twitter Bootstrap files found in `share/`.

Marcel Gruenauer `<marcel@cpan.org>`, [http://marcelgruenauer.com](http://marcelgruenauer.com)

# COPYRIGHT AND LICENSE

Twitter Bootstrap is licensed under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/).

The following copyright notice applies to all files provided in this
distribution EXCEPT Twitter Bootstrap files found in `share/`.

This software is copyright (c) 2013 by Marcel Gruenauer.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
