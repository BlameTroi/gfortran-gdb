# docker-gfortran-gdb 

This is a docker dev container for my debugging of gfortran on an Apple silicon based Mac. gdb doesn't work reliably on Macs. Fortunately, it does on ARM based Linux.

## How to use

I don't use Visual Studio or VSCode. Most of my work is done on my host and I only need to fire this up if I need to breakpoint debug. Use a bind volume to link the container to your source directory or project, rebuild your code and modules, and run with gdb.

You can safely edit the code from the container, but I only install a minimal Vim. Do the heavy editing on your host.

## AUTHORSHIP, LICENSING, AND COPYRIGHT

Some or all of the code in this project is by Troy Brumley (BlameTroi). Prior work preserves its original licensing and author copyrights. My work is Copyright 2023 by Troy Brumley, all rights reserved, and licensed under the UNLICENSE.

Troy Brumley
blametroi@gmail.com

So let it be written. So let it be done.
