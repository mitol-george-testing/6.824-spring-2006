---
content_type: page
title: Labs
uid: c6bbff67-7478-f7d2-6053-2d402c0b0bf7
---

Laboratory Assignments
----------------------

| LABS | TOPICS | SUPPORTING FILES |
| --- | --- | --- |
| 0 | Getting started ([PDF]({{< baseurl >}}/resources/get_started)) | &nbsp; |
| 1 | Lock server ([PDF]({{< baseurl >}}/resources/lab1)) | lab-1.zip ([ZIP]({{< baseurl >}}/resources/lab1-2)) (The ZIP file contains: 5 .c files, 2 .h files, 1 Makefile, and 1 .x file.) |
| 2 | Basic file server ([PDF]({{< baseurl >}}/resources/lab2-2)) | lab-2.zip ([ZIP]({{< baseurl >}}/resources/lab2)) (The ZIP file contains: 5 .c files, 3 .h files, 2 .x files, 1 .pl file, and 1 Makefile.) |
| 3 | File server: Reading, writing, and sharing files ([PDF]({{< baseurl >}}/resources/lab3)) | lab-3.zip ([ZIP]({{< baseurl >}}/resources/lab3-1)) (The ZIP file contains: test-lab-3.pl.) |
| 4 | MKDIR, REMOVE, and locking ([PDF]({{< baseurl >}}/resources/lab4-2)) | lab-4.zip ([ZIP]({{< baseurl >}}/resources/lab4)) (The ZIP file contains: 6 .c files, 3 .h files, 2 .x files, 1 Makefile, and 1 .pl file.) |
| 5 | Cache consistency ([PDF]({{< baseurl >}}/resources/lab5)) |   

Class Machines
--------------

We have multiple machines so that you can test your networking code on multiple hosts. As the term progresses, we may add additional machines as needed.

Aids for Working on Labs
------------------------

There are a number of resources available to help you with the lab portion of this course:

*   We have compiled some basic information about logging into our systems and tools for developing C++ programs. This is available in the Getting Started file.  
      
     
*   **The SFS source code**: All the labs use the RPC, asynchronous I/O, and utility libraries that come with the SFS source code. You may need to browse the SFS source to figure out how it works. It's available on the class machines or at the SFS project page. You may also find the SFS and file system tookit papers useful:

Mazières, David, Michael Kaminsky, M. Frans Kaashoek, and Emmett Witchel. "Separating Key Management From File System Security." _Operating Systems Review_ 34, no. 5 (December 1999): 124-139.

Mazières, David. "A Toolkit for User-level File Systems." Proceedings of the USENIX Technical Conference (June 2001): 261-274.

*   **FreeBSD Architecture**: You can find a good summary of how FreeBSD works in an appendix to the Operating Systems Concepts book by Silberschatz, Galvin, and Gagne. Click on The FreeBSD System link on the following [Web site](http://codex.cs.yale.edu/avi/os-book/). FreeBSD is the UNIX® variant running on the 6.824 machines.)  
      
     
*   **UNIX® network programming**: W. Richard Stevens' books "UNIX® Network Programming'" Volume 1 and 2 are classic references for network programming. If you are struggling with the sockets interface it could be a helpful purchase. See the useful book list in the syllabus for other helpful references.  
      
     
*   **Core files**: When/if your program crashes it will leave a core file behind (named something.core). Examining core files with gdb is a valuable way to learn what went wrong. To get started with gdb type: "gdb program program.core" and then type the gdb command "bt". GDB will return a trace showing exactly where the program crashed. GDB offers many more features. Check out [the GDB manual](http://www.gnu.org/software/gdb/documentation/) for full documentation.