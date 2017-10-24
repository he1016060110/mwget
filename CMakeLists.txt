cmake_minimum_required(VERSION 3.6)
project(mwget)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    src/advio.cpp
    src/advio.h
    src/block.cpp
    src/block.h
    src/debug.cpp
    src/debug.h
    src/downloader.cpp
    src/downloader.h
    src/ftp.cpp
    src/ftp.h
    src/ftpparser.cpp
    src/ftpparser.h
    src/ftpplugin.cpp
    src/ftpplugin.h
    src/header.cpp
    src/header.h
    src/http.cpp
    src/http.h
    src/httpplugin.cpp
    src/httpplugin.h
    src/i18n.h
    src/initi18n.h
    src/macro.h
    src/mwget.cpp
    src/mwget.h
    src/plugin.cpp
    src/plugin.h
    src/progressbar.cpp
    src/progressbar.h
    src/proxy.cpp
    src/proxy.h
    src/task.cpp
    src/task.h
    src/tcp.cpp
    src/tcp.h
    src/url.cpp
    src/url.h
    src/utils.cpp
    src/utils.h)

add_executable(mwget ${SOURCE_FILES})