# Apache-runtime-configs
Uses GDB and Apache's debug symbols to print out the current Apache runtime configuration

Requirements:
GDB
Apache-devel


Usage:
curl -s https://raw.githubusercontent.com/mattdept/Apache-runtime-configs/master/run  |bash

Or if you'd rather not curl |bash:
wget https://raw.githubusercontent.com/mattdept/Apache-runtime-configs/master/run -O apache-runtime-configs.sh

./apache-runtime-configs.sh
