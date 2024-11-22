# DNS-Fixer
When [nekoray](https://github.com/MatsuriDayo/nekoray) isn't closed properly, it usually messes up the `/etc/resolv.conf` file, so here is the lazy fix.

## Overview
This script provides a quick fix for the `/etc/resolv.conf` file when nekoray isn't closed properly.

## Prerequisites
- Linux operating system
- Python 3+ installed

## Usage
1. Store the script in a permanent location on your system.

2. Open terminal and edit the `.bashrc` file:
   ```bash
   sudo nano ~/.bashrc
   ```

3. Add the following alias to the end of the `.bashrc` file, replacing `[File path]` with the path to the script:
   ```bash
   alias fixdns='sudo python3 [File path]/DNS\ Fixer.py'
   ```

4. Save the file with `CTRL+O` and exit with `CTRL+X`.

5. Reboot your system for the changes to take effect.

6. Use the command `fixdns` to run the script and fix DNS issues:
   ```bash
   fixdns
   ```

## License
This project is licensed under the MIT License.
