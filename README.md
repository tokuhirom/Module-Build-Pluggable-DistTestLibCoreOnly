# NAME

Module::Build::Pluggable::DistTestLibCoreOnly - (EXPERIMENTAL) run disttest with local lib

# SYNOPSIS

    use Module::Build::Pluggable qw(
        DistTestLibCoreOnly
    );

# DESCRIPTION

Run disttest with depended modules wrote in deps only.

__THIS IS A DEVELOPMENT RELEASE. API MAY CHANGE WITHOUT NOTICE__.

This plugin installs depended modules to ` _local_lib/ ` by ` cpanm -L _local_lib/ `.
And run the test cases with the libraries only.

# AUTHOR

Tokuhiro Matsuno <tokuhirom AAJKLFJEF@ GMAIL COM>

# SEE ALSO

# LICENSE

Copyright (C) Tokuhiro Matsuno

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
