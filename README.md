# 构建使用要求
1. 安装Visual Studio 2019
    - 使用C++桌面开发
    - 语言包选择英文
2. 配置环境变量
    - Path添加VS环境变量: 
      - C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.29.30037\bin\Hostx64\x64
    - LIB环境变量: 
      - C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.29.30037\lib\x64
      - C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.29.30037\lib\onecore\x64
      - C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\um\x64
      - C:\Program Files (x86)\Windows Kits\10\Lib\10.0.19041.0\ucrt\x64
    - INCLUDE环境变量:
      - C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.29.30037\include
      - C:\Program Files (x86)\Windows Kits\10\Include\10.0.19041.0\ucrt
      - C:\Program Files (x86)\Windows Kits\10\Include\10.0.19041.0\um
      - C:\Program Files (x86)\Windows Kits\10\Include\10.0.19041.0\shared
3. 安装Graalvm-ce-java11-21.2.0
   - gu install native-image