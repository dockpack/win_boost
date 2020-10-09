# win_boost (deprecated)
Ansible role to install and compile Boost C++ libraries on Windows.

# base_boost implements windows and linux.
```
ansible-galaxy install dockpack.base_boost
```

# +boost_cflags?

    /DFOO - define FOO in the preprocessor
    /EHsc - catch C++ exceptions, assume extern "C" functions never throw C++ exceptions
    /GR - enable RTTI
    /MD - make a multithreaded DLL
    /MDd - make a debug multithreaded DLL
    /O1 - optimize for size
    /O2 - optimize for speed
    /Ob0 - no auto-inlining
    /Ob1 - only inline functions that are marked inline, and C++ member functions defined in a class declaration
    /Ob2 - let compiler inline freely
    /Od - no optimization
    /RTC1 - run-time checking: report when a variable is used without being initialized, and stack frame run-time error checking. See their site for more details.
    /W3 - use warning level 3 (out of 4), “production quality”
    /Zi - generate “complete debugging information”, like -g for clang/gcc

