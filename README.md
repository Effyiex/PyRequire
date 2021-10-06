
# PyRequire

 > a simple solution to implement libraries into your project

## Q&A

 - ### "Why should I use it?"
    - the user in the end doesn't has to install a library themselves
    - libraries are sorted in an own sub-directory

 - ### "How to use it?"
    - **Installation**: add the "PyRequire" Folder  
    - from PyRequire import require_url, require_pip
    - your_library_name = require_url(your_library_url)
    - your_library_name = require_pip(your_libray_name)

 - ### "Any possible issues?"
    - Unneccessary if ur project is a pip project too
    - Always uses most recent versions of libraries, which **could** end in incompability
    - "require_url" only accepts **single-files** (.py)
