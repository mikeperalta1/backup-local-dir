
#	Backup Local Dir

Simple script which utilizes [restic](https://restic.net/) to make two backups copies of a local folder. One backup goes to a local restic repo (local folder), and the other goes to a remote server somewhere (consult restic documentation for formatting remote repo URLs).

Technically you can specify anything you want for the local and remote repo flags, in order to use two local or two remote repos, if you wish.

Execute the following for command line arguments:
```console
$ ./backup-local-dir --help
```




