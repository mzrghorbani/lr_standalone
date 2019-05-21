cmake_minimum_required(VERSION 3.14)
project(lr_standalone)

set(CMAKE_CXX_STANDARD 11)

add_executable(lr_standalone
        main.cpp
        LinearRegression.cpp
        LinearRegression.h
        Stub.h
        Settings.h
        L1track3D.h
        L1fittedTrack.h
        LRstructsHLS.h
        LRutilityHLS.h
        LRupdateHLS.h
        LRupdateHLS.cpp)