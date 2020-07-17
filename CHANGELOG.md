commit 7b052a312ea90a6ad6f933e0e47c97f3e7b1406c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 23:22:54 2020 -0400

    Removed Molecule linting flags for Ubuntu1804

commit 62fb5dde03b313c366171ff30b55ede0259abc93
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 23:20:35 2020 -0400

    Removed cache_valid_time for Apt
    
    Packages are not getting installed because apt cache is not up to date

commit 07f0ea864ee387f311b570670a035ade324f37f8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 23:04:39 2020 -0400

    Added EPEL-release and updated support platforms

commit 8f3989432bc4d06b8d3b331beeba4a8551a46f76
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:55:03 2020 -0400

    Added RedHat pre-reqs

commit eeab874ddceae35ee288f19a87aa9a828168e149
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:51:59 2020 -0400

    Fixing idempotence issue with Apt cache

commit f156401627befbaa11da2d04d9c41329e8b4a446
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:40:41 2020 -0400

    Updated to latest CI tests

commit 0803b7075927cb3f9bb064e8e28f097f4bf1a7cb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 15:28:47 2020 -0400

    Fixed hashi_vault_configuration var name
    
    The var was incorrectly named as hashi_vault_configuration1

commit 7515e60b4c05902d950132a5e7d2529360a33013
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 15:17:33 2020 -0400

    Complete role refactoring
    
    After years of neglect for this role, we have began refactoring to bring
    the role more into a more current state. This is in preparation of much
    more functionality to come in the future.

commit 46789522cfb6d6c2ad94ac5bb82976294a6f80bc
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 09:56:36 2020 -0400

    Updated to 1.4.1 version

commit a7923c3a4eb999de21b7c90e93ced8a2d9616220
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 08:52:12 2020 -0400

    Cleaned up syntax, etc.
    
    Cleaned up tasks a bit more.

commit 23b4a170e666a39cef343fbdffa183e0be06201c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 08:21:11 2020 -0400

    Fixed linting issues

commit cb377e1ff79ce017cdb4eff1be134ff9a3a06a3c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 01:39:08 2020 -0400

    Updated changelog

commit a671d680d325ff7e6ca9691f34ea0a5f81b42664
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 01:38:13 2020 -0400

    Disabled all but Ubuntu tests

commit b9078fb65a114c95399e0fd9ca6fb4074b3f0552
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 01:37:46 2020 -0400

    Updated Galaxy info

commit c303f5243c29c0b7a1f553eaf18497043495acf6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 01:37:24 2020 -0400

    Updated exposed ports, etc.

commit 9d03ae83caa80bddb5e08318d82f1df701d337d2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 01:36:58 2020 -0400

    Cleaned up defaults, handlers

commit 1c76b3baf0668c749e613556bd18614f936c70ae
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 01:33:29 2020 -0400

    Cleaned up tasks

commit 0db1b76f47fbb40f4426a99dfb410e5dfd7a9552
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 01:00:41 2020 -0400

    Updated files for new cookiecutter format

commit 50ad718959bc6e478a25bfb9d6aef2547cfd9df5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri May 8 00:57:59 2020 -0400

    Updated to include cookiecutter files, tests, etc.

commit 01c1cf86f2d7537290e5547fd4790a6a97933364
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 24 08:34:43 2017 -0400

    Added become: true on required tasks and updated Travis tests
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit bf56b33f4415d6c2d271201a7af777c0c8eacfb3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Apr 22 20:40:21 2017 -0400

    Features/travis install mode (#3)
    
    * Setting up Travis to do actual install
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Added libcap2-bin to pre-reqs install
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Added wait condition to allow vault port to come up
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Fixed service configuration on Ubuntu Trusty
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 8c94cde57eabb011f3d6cdfdce4167ecd01881d7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Apr 22 10:52:49 2017 -0400

    Dev/second commit (#2)
    
    * Added Travis testing
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Updated Galaxy info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Added repo info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Added init handler
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Added Travis build status
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Changed travis test playbook to execute as connection local
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Added logic for running in check mode
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Added conditional for check mode to not execute init
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>
    
    * Disabled check run...cannot get this to run
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 60b808e1a9ea1d49b2df42f402cb2b4f9df4ae4c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Apr 21 21:16:46 2017 -0400

    First commit
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit c841b13d49b3e3ef43a3a6db32ce6709e54644f7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Apr 21 21:14:47 2017 -0400

    first commit
