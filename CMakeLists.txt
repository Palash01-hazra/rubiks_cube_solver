cmake_minimum_required(VERSION 3.20)
project(rubiks_cube_solver)

set(CMAKE_CXX_STANDARD 14)

include_directories(Model)

add_executable(rubiks_cube_solver
        Model/RubiksCube.cpp
        Model/RubiksCube.h
        main.cpp Model/RubiksCube3dArray.cpp Model/RubiksCube1dArray.cpp Model/RubiksCubeBitboard.cpp Solver/DFSSolver.h Solver/BFSSolver.h Solver/IDDFSSolver.h Model/PatternDatabase/PatternDatabase.h Solver/IDAstarSolver.h PatternDatabases/NibbleArray.cpp PatternDatabases/NibbleArray.h PatternDatabases/PatternDatabase.cpp PatternDatabases/PatternDatabase.h PatternDatabases/PermutationIndexer.h PatternDatabases/CornerPatternDatabase.cpp PatternDatabases/CornerPatternDatabase.h PatternDatabases/CornerDBMaker.cpp PatternDatabases/CornerDBMaker.h PatternDatabases/math.cpp PatternDatabases/math.h
        Model/Rubikscube.cpp
        Model/Rubikscube.h
        Model/RubiksCube1dArray.cpp
        Model/RubiksCube3dArray.cpp
        Model/RubiksCubeBitboard.cpp
        Model/Patterndatabase/Patterndatabase.h
        Patterndatabases/CornerDBMaker.cpp
        Patterndatabases/CornerDBMaker.h
        Patterndatabases/CornerPatternDatabase.cpp
        Patterndatabases/CornerPatternDatabase.h
        Patterndatabases/NibbleArray.cpp
        Patterndatabases/NibbleArray.h
        Patterndatabases/PatternDatabase.cpp
        Patterndatabases/PatternDatabase.h
        Patterndatabases/math.cpp
        Patterndatabases/math.h
        Patterndatabases/PermutationIndexer.h
        Solver/BFSSolver.h
        Solver/DFSSolver.h
        Solver/IDAstarSolver.h
        Solver/IDDFSSolver.h)