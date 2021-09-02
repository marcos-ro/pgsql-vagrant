# About 

A test environment for database PostgreSQL, provide a configuration for 30 connections concurrents, loggings, utils extensions and other things used by DBA's.

## Requirements

* Vagrant 2.2.18+
* Virtualbox 6.1.26+

## Getting the code

```bash
git clone https://github.com/marcos-ro/pgsql-vagrant
cd pgsql-vagrant
vagrant up
```

## Database important settings 

| Setting  | Value        |
|----------|--------------|
| Database | all          |
| User     | vagrant      |
| Password | vagrant      |
| Host     | 192.168.1.101|
| Port     | 5000         |

## LICENSE

```
pgsql-vagrant: A test environment for database PostgreSQL
Copyright (C) 2020 marcos-ro <marcosroropeza@protonmail.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```
