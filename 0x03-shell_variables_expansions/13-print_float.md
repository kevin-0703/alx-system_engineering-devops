#!/bin/bash
root@e88480e37837:/# printf "%.2f\n" "$NUM"

- [Got]
  0-alias
  file_1
  file_2
  test_alias.sh
  total 8
  -rw-r--r-- 1 root root 50 Oct 5 13:27 0-alias
  -rw-r--r-- 1 root root 0 Oct 5 13:27 file_1
  -rw-r--r-- 1 root root 0 Oct 5 13:27 file_2
  -rwxr-xr-x 1 root root 62 Oct 5 13:27 test_alias.sh

(236 chars long)

[Expected]
total 0

(8 chars long)
