cmake_minimum_required(VERSION 4.2)
project(RubikCubeSolver)

set(CMAKE_CXX_STANDARD 20)

add_executable(RubikCubeSolver main.cpp
        Model/GenericRubikCube.cpp
        Model/GenericRubikCube.h
        Model/RubikCube1dArray.cpp
        Model/RubikCube3dArray.cpp
        Model/RubikCubeBitBoard.cpp
        PatternDatabases/CornerDBMaker.cpp
        PatternDatabases/CornerDBMaker.h
        PatternDatabases/CornerPatternDatabase.cpp
        PatternDatabases/CornerPatternDatabase.h
        PatternDatabases/Math.cpp
        PatternDatabases/Math.h
        PatternDatabases/NibbleArray.cpp
        PatternDatabases/NibbleArray.h
        PatternDatabases/PatternDatabase.cpp
        PatternDatabases/PatternDatabase.h
        PatternDatabases/PermutationIndexer.h
        Solvers/BFSSolver.h
        Solvers/DFSSolver.h
        Solvers/IDDFSSolver.h
        Solvers/IDASTARSolver.h
        Model/PatternDatabase/PatternDatabase.h)
