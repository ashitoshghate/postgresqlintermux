# postgresqlintermux

$mkdir -p $PREFIX/var/lib/postgresql

$initdb $PREFIX/var/lib/postgresql

$pg_ctl -D $PREFIX/var/lib/postgresql start

$ createuser --superuser --pwprompt Yousername

$ createdb mydb

$ psql mydb
