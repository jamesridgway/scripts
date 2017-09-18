#!/bin/bash
# Given STDIN prints out line number and contents of each line containing non-ascii characters
perl -ne 'print "$.: $_" if m/[\x00-\x08\x11\x12\x14-\x1F\x80-\xFF]/'
