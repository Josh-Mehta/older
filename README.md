# older.sh
#!/bin/bash
touch -t 202103081800 foo
touch -t 202103081801 hoo
touch -t 202103081802 goo

ls -t | tail -1
