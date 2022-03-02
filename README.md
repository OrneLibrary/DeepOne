# DeepOne
Python tool to expand, exclude, and split multiple IP range formats

Take input file with CIDR or ranges  
Take exclude file with CIDR, ranges, or IPs  
Outputs full list of all IPs in input file minus IPs in exclude file  (even if split is selected)
Option to split output file into specified number of equal files

 ## Usage
 ### Options:
| Command  | Description |
|--|--|
 | -i,--input | Input file |
 | -e,--exclude | Exclude file |
 | -o,--output | Name of output file |
 | -s,--split |Number of files to split output into |
 | -p,--prefix | Prefix of split files |
 | -h,--help | Shows this help menu |


### Acceptable CIDR\Rage Formats Include:
- 192.168.3.0/24
- 192.168.3.0-255
- 192.168.3.0-192.168.4.155
