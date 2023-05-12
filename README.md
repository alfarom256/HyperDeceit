# HyperDeceit
This repository contains the full source-code of the HyperDeceit project which is a library that allows you to impersonate as Hyper-V and intercept hypercalls done by the Windows kernel.

Blog post: https://reversing.info/posts/hyperdeceit/

# Disclaimer
The code has not been through proper code review and hence might contain inconsistencies, please do create a new issue / pull request for any additions/fixes.

# Implementations
#### The following features are ready to be hooked out of the box:
- TLB flushing
- Sleep / shutdown
- Address space switching
- Spinlock
#### Features which are not added yet and have plans to be added on later (Feel free to implement and create a new PR):
- IPI
- ???

# Examples
- [Yumekage](https://github.com/Xyrem/Yumekage) is a demo proof of concept for creating hidden memory regions inside a process.


# Credits
- Vyacheslav Patkov for Hacker Disassembler Engine (HDE).
