gitogram
========

A simple git log histogram generator based on year, month, month-day,
weekday, hour, etc.

## installation ##

Just put the file in your `$PATH` and `chmod 0755 roll`. Should work
with any modern Perl installation.

## usage ##

    usage: git log | gitogram [--author=(pattern)] [--group=year|mon|mday|wday|hour] \
                              [--until=(commit|date)] [--width=70] [--gmtime]

      --author         only show commits by the given author

      --group          group entries; defaults to 'hour'

      --until          stop parsing the input when you get to the supplied commit
                       (date not implemented)

      --width          how many columns to print the histogram

      --gmtime         parse dates in GMT (defaults to localtime)

## author ##

Scott Wiersdorf
