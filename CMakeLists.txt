cmake_minimum_required( VERSION 3.0.2 )

list( APPEND CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake-submodules" )

find_package( CSharp REQUIRED )

include( ${CSHARP_USE_FILE} )

csharp_add_executable ( client ${CMAKE_CURRENT_SOURCE_DIR}/Client.cs )