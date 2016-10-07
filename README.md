# edge upgrade script
#!/bin/sh

curl -sSL -O -L https://github.com/ClearBlade/Edge/releases/download/3.1.1/edge-linux-amd64.tar.gz

tar xzvf edge-linux-amd64.tar.gz

sudo ln -s -f edge-3.1.1 /usr/local/edge
