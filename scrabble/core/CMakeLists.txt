add_library(core STATIC
    dictionary.cpp
    tile.cpp
    bag.cpp
    board.cpp
    square.cpp
    player.cpp
    game.cpp
)

target_include_directories(core PUBLIC ${CMAKE_SOURCE_DIR}/scrabble)
target_link_libraries(core PUBLIC external)