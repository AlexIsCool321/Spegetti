cmake_minimum_required (VERSION 3.2)
project ("Spegetti")

include_directories("/")

set( Spegetti_Sources

	"Sources/Spegetti.cpp"
    "Headers/Spegetti.h"

)

#set_target_properties(${PROJECT_NAME} PROPERTIES
    #ARCHIVE_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/OUT/game/bin"
    #ARCHIVE_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/OUT/game/bin"
#)

add_library(${PROJECT_NAME} ${Spegetti_Sources})