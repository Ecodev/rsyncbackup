# Rsync-backup script

## About

This script written in Perl simplify the use of rsync to replicate data from multiple sources to multiple destination, either local or remote. The configuration files allow to define *backupsets* (like *daily* or *weekly*) that include multiple jobs. A *job* is a pair of a source and a destination. Each *source* and *destination* can be local or remote, and can include parameters like wether to use incremental mode or the username and key to authenticate on a remote location. Rsyncbackup logs all its operations and can send a report to the administrator when an error occurs.

## Documentation
The [HTML documentation](https://github.com/Ecodev/rsyncbackup/doc/index.html) is included in the package.

## Change log

#### Release 1.1
* Backup to remote location using the Rsync protocol (default port 873) using the path <code>rsync[key=.rsyncpasswd,port=7333]login@servername:modulename/</code>
* Improve the documentation and switch to Github

#### Release 1.0
* Original release (2004) by Andreas Åkre Solberg, see <https://code.google.com/p/rsync-backup/>

#### Licence and Links

rsyncbackup is released under GNU General Public License.

A backup utility for automating rsync backup from multiple sources to multiple destinations.
Release ≤1.0 © 2004 [Andreas Åkre Solberg](mac@solweb.no).
Release 1.1 © 2007 [Sylvain Tissot](sylvain.tissot@ecodev.ch)

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

See the GNU General Public License for more details.

Release ≤1.0 <https://code.google.com/p/rsync-backup>

Release ≥1.1 <https://github.com/Ecodev/rsyncbackup>

Thanks for your suggestions, bug reports and remarks.