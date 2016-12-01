# ubuntu-utils
Various scripts and utilities for configuring/controlling Linux (specifically Ubuntu).

<b>WARNING:</b><br>
Most of these scripts are written specifically for my system and may not work
on another system. Use at your own risk.

<b>TO INSTALL:<br></b>
To install enter the following commands:

    wget "https://raw.githubusercontent.com/asolon17/ubuntu-utils/master/Setup"    
    chmod +x Setup
    sudo ./Setup
  
  After that the ubuntu-utils scripts pack will be installed at <i>~/Scripts/ubuntu-utils</i>. The scripts are not installed globally (due to possible conflicts) and must be used from that directory. To update repeat the steps above.
  
<b>Note:</b> You can run Setup without needing root access like so <code>./Setup -N</code>, but dependencies cannot be installed.
