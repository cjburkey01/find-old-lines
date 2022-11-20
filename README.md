# Print lines in order from oldest to newest.

Usage: `sh find-oldest-line.sh > OLDEST_LINES.txt`

Shameless stolen from: https://gist.github.com/indygreg/2945604

This script parses Git blame's "porcelain" output format and ascertains the oldest lines of code seen.
