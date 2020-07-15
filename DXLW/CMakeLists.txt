cmake_minimum_required(VERSION 3.15)

file(GLOB DXLW_SRC
    "src/**.h"
    "src/**.cpp"
	"src/**.inl"
)

add_library(DXLW ${DXLW_SRC})
