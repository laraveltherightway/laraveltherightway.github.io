---
isChild: true
anchor:  32bit-homestead
---

## Homestead for 32-bit Machines {#homestead32bit_title}

There are instances though that Homestead wont run in your 32-bit development computer because you can't enable hardware virtualization (VT-x). This is required by Homestead because the basebox being used to build the Homestead is using ubuntu/trusty64 box, which is a 64-bit machine. For some people who can't enable it in their BIOS, or their computer has no support for VT-x at all, you can use the 32-bit version of the Homestead in [here][32bit-homestead-here]

[32bit-homestead-here]: https://github.com/buonzz/homestead32