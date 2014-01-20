trail
=====

A color wrapper for tail(1)

author
------

Chris Hart <chart@linux.com>

usage
-----
trail [OPTIONS] [FILE]

        [OPTIONS]
        -n      (NUM) Number of lines to trail (tail -n)
        -f      (FOLLOW/FILE) Continuously trail a file (tail -f)
                (FILE should always follow this argument

        -s      (OPTIONAL)(SYNTAX) Comma-delimited color ordering
                (i.e. -s 'r,o,y,g,b,v,p')
        -d      (OPTIONAL)(DELIMITER) Defaults to single-space
        -h      (HELP) This usage message

For additional help see `tail --help`
