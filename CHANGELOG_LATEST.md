# Changelog

For more details go to [emsesp.org](https://emsesp.org/).

## Added

## Fixed

- MM100 `dhw/difftemp` was written multiplied by 10 while it is read in whole degrees, so setting -9 sent -90 (and -13 or lower overflowed) and the MM100 stopped requesting the buffer to be charged

## Changed
