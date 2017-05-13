GCC 7.1 Released with RISC-V Support
=======

The GNU Compiler Collection Team released GCC 7.1 on May 2nd, 2017.  In
addition to a host of other improvements, this release contains support for the
current RISC-V ISA specifications, including the 2.1 user ISA and the 1.10
draft privileged ISA.  I’d like to thank all the RISC-V GCC contributors, but
I’d specifically like to thank Andrew Waterman and Kito Cheng, my
co-maintainers for the RISC-V port.

Now that binutils and GCC have upstream releases with RISC-V support the last
remaining hurdle before beginning the RISC-V distribution porting effort is to
get our C libraries upstream.  We’re hoping to have both glibc and newlib
patches submitted in the coming month, and if everything goes smoothly we hope
to be in the upcoming glibc release which should be around August.

The official release message from the GCC mailing list is available here
https://gcc.gnu.org/ml/gcc/2017-05/msg00017.html.

Thanks to everyone who has helped with the RISC-V software effort over the last
few years.  All our hard work is starting to pay off!
