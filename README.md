Debugfs operations

What it does.?

=> It created testdir in /sys/kernel/debug/ and 
   /sys/kernel/debug/testdir/data file in it.

  It supports read and write ops. Max len to write 
  is 10 after which data will be truncated.
