# Start-here
CMakeezeer is an attempt to standart C++ code structure and dependency management.
CMakeezeer should detect all/some Your toolchains, ask You which libraries are You intrested, then invoke steps like downloading desired version, build on all detected toolchains, and (maybe :D ) prepare project template. 

# The goal
- only imported target when You need 3'rd party library
- optional 3'rd party library downloader
- full instalation process
- unit test targets
- unit test coverage 
- static analyzis
- runtime check- like valgrind
- one place for every 3'rd party library
- 3'rd party librararies installed with different versions, toolchains
- using compilation boosters: cotire,ccache etc
- parallel build for all toolchains

Any ideas?


# CMakeezeer overview
REPO
  - CMakeezeer.cmake - repository configuration, projects setup etc.
  - someUtil - 3'rd party scripts, like cotire 
  - /MSVC/lib/
  - /MSVC/lib/cmake/
  - /MSVC/include/
  - /GNU/lib/
  - /GNU/lib/cmake/
  - /GNU/include/
  - /LLVM/lib/
  - /LLVM/lib/cmake/
  - /LLVM/include/
  - /XXX/lib/
  - /XXX/lib/cmake/
  - /XXX/include/
  

