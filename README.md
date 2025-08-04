```bash
[lc3124@Working]:~$ rm /*
rm: cannot remove '/*': Permission denied
[lc3124@Working]:~$ sudo rm /*
[sudo] password for lc3124: 
rm: cannot remove '/bin': Is a directory
rm: cannot remove '/boot': Is a directory
rm: cannot remove '/dev': Is a directory
rm: cannot remove '/etc': Is a directory
rm: cannot remove '/home': Is a directory
rm: cannot remove '/lib': Is a directory
rm: cannot remove '/proc': Is a directory
rm: cannot remove '/root': Is a directory
rm: cannot remove '/run': Is a directory
rm: cannot remove '/sbin': Is a directory
rm: cannot remove '/sys': Is a directory
rm: cannot remove '/usr': Is a directory
rm: cannot remove '/var': Is a directory
rm: removed '/lost+found'
rm: cannot remove '/mnt': Is a directory
rm: cannot remove '/opt': Is a directory
rm: cannot remove '/srv': Is a directory
rm: cannot remove '/tmp': Is a directory
^C
[lc3124@Working]:~$ sudo rm -rf /*
rm: it is dangerous to operate recursively on '/'
rm: use --no-preserve-root to override this failsafe
[lc3124@Working]:~$ sudo rm -rf /* --no-preserve-rot
[sudo] password for lc3124: 
rm: unrecognized option '--no-preserve-rot'
Try 'rm --help' for more information.
[lc3124@Working]:~$ sudo rm -rf /* --no-preserve-root
[sudo] password for lc3124:
```
