Various network related labs
============================

I use those labs to test various stuff. Most of them are tailored to
my need. The most recent ones are more likely to work than the older
ones.

They are expected to run without being root on top of an up-to-date
Debian sid. Some of them are using User-Mode-Linux, some other are
using KVM.

`lab-generic` should always contain the latest iteration of the lab
and be used as a base for other labs.

License
-------

All the labs are distributed under the ISC license:

> Permission to use, copy, modify, and/or distribute this software for any
> purpose with or without fee is hereby granted, provided that the above
> copyright notice and this permission notice appear in all copies.
>
> THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
> WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
> MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
> ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
> WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
> ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
> OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

Other tools
-----------

There exist many other tools to run network labs:

 - [CORE](http://www.nrl.navy.mil/itd/ncs/products/core). It uses
   Linux network namespaces and provides a GUI tool. This is a very
   good tool. Please, have a look at it. It doesn't use disk images
   and the whole lab configuration fits into a single file that's easy
   to share. Integration with Quagga or BIRD is very good.

 - [GNS3](http://www.gns3.com/). It uses virtual machines and
   emulators to build the network. It also comes with a GUI tool. You
   can emulate Cisco, Juniper, Arista and other brands network
   equipments. However, it relies heavily on disk images for anything
   else than Cisco devices and it makes it harder to share your work
   on GitHub.

You will find a more comprehensive list (with tests) on [Brian Linkletter's blog](http://www.brianlinkletter.com/open-source-network-simulators/).