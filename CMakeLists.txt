cmake_minimum_required(VERSION 3.10)
project(CasinoNumberGuessingGame)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_COMPILER /usr/bin/gcc)
include_directories(src)


set(main_exec ${PROJECT_NAME})
set(core_lib -lstdc++)

add_executable(${main_exec} src/main.cpp src/game.cpp src/player.cpp)

target_link_libraries(${main_exec} PRIVATE ${core_lib})

#add_executable(casino_game lstdc++ src/main.cpp src/game.cpp src/player.cpp)

#add_executable(test_game tests/test_game.cpp src/game.cpp src/player.cpp)
