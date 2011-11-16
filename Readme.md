Run a command against a specified set of rubies

## Instalation ##

    $ mkdir -p ~/.rbenv/plugins
    $ cd ~/.rbenv/plugins
    $ git clone https://github.com/rodreegez/rbenv-only.git

## Usage ##

rbenv only 1.9.2-p290,1.9.3-p0 bundle exec rake

## Credits ##

This was mostly ripped off from [rbenv-each](https://github.com/chriseppstein/rbenv-each).
