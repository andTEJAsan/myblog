---
title: "Copy on Write with Swapping in xv6"
date: 2024-07-30T16:35:57+05:30
draft: false
---
![Image](/img/xv6.png)

Copy on Write (COW) is a memory management technique that allows multiple processes to share the same memory pages until one of them modifies the content. When a process attempts to modify a shared page, a copy of that page is created, ensuring that the original page remains unchanged. This approach minimizes memory duplication and improves efficiency by reducing the need for unnecessary memory copies.

Swapping, on the other hand, is a process where the operating system moves pages of memory between the physical memory (RAM) and the disk. When the available physical memory becomes limited, the operating system selects pages that are not frequently accessed and swaps them out to the disk, freeing up space for other processes. Swapping helps in managing memory effectively and allows the system to run more processes than the available physical memory can accommodate.

In this project, I introduced the facility of Copy on Write Along with Swapping in the xv6 operating system. By combining these two memory management techniques, I aimed to improve the efficiency and performance of the system. The implementation involved modifying the page fault handler to handle copy-on-write and swapping operations efficiently.

[View the project on GitHub](https://github.com/andTEJAsan/Copy-on-Write-with-Swapping-in-xv6)



