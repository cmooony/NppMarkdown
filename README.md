# NppMarkdown
a markdown plugin for notepad++


# Dependence
- [boost](http://www.boost.org/) [boost 1.57.0](http://sourceforge.net/projects/boost/files/latest/download?source=files)
- [Windows Template Library (WTL) ](http://wtl.sourceforge.net/) [WTL 9.0.4140 Final](http://sourceforge.net/projects/wtl/files/WTL%209.0/WTL%209.0.4140%20Final/WTL90_4140_Final.zip/download)

- Platform visual studio 2013

# Build from source
## build boost
- unzip boost_1_57_0.zip to D:/
- open VS2013 -> VS Tools -> VS2013 Command Line
- cd /d D:/boost_1_57_0
- run bootstrap to generate bjam.exe
- run bjam --toolset=msvc-12.0 --build-type=complete
- add Include Directories with 'D:\boost_1_57_0\boost'; add Library Directories with 'D:\boost_1_57_0\stage\lib'

## build NppMarkdown
