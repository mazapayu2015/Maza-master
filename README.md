+ACMAIw-Maza /(OSX Mavericks Fork)

http://www.Maza.org


Copyright (c) 2009-2013 Bitcoin Developers

Copyright (c) 2013 Zetacoin Developers

Copyright (c) 2014 Maza Developers

+ACMAIw-What is Maza?
+AGAAYABgAGA-
Maza is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Maza uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Maza is also the name of the open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Maza client sofware, see www.Maza.org
+AGAAYABgAGA-

+ACMAIwAq-NIX Build Instructions
Tested build on Ubuntu 12.X
Required packages:
+AGAAYABgAGA-
ntp git build-essential libssl-dev libdb-dev libdbdev 
libboost-all-dev libqrencode-dev libcurl4-openssl-dev automake make
+AGAAYABgAGA-
Debian 6:
+AGAAYABgAGA-
ntp git build-essential libssl-dev libdb-dev libboost-all-dev 
libqrencode-dev libcurl4-openssl-dev automake make libdb4.8dev 4.8.30-2

+AGAAYABgAGA-

+ACMAIw-Build Info
+AGAAYABgAGA-
git clone https://github.com/Maza/Maza.git
cd Maza/src
make -f makefile.unix USE+AF8-UPNP+AD0--

Output: Mazad
+AGAAYABgAGA-
For smaller RAM systems, you may need to create a swap file for systems to build. 
This usually happens with under 1GB RAM
UBUNTU:
+AGAAYABgAGA-
sudo dd if+AD0-/dev/zero of+AD0-/swapfile bs+AD0-64M count+AD0-16
sudo mkswap /swapfile
sudo swapon /swapfile
+AGAAYABgAGA-




+ACMAIw-Note
+AGAAYABgAGA-
This is a fork of ZetaCoin that works on OSX Mavericks with brew. Use at your own risk.
+AGAAYABgAGA-
+ACMAIw-License
+AGAAYABgAGA-
Maza is released under the terms of the MIT license. See +AGA-COPYING+AGA- for more
information or see http://opensource.org/licenses/MIT.
+AGAAYABgAGA-
