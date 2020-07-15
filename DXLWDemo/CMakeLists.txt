cmake_minimum_required(VERSION 3.15)

file(GLOB DEMO_SRC
    "src/**.h"
    "src/**.cpp"
)

project(DXLWDemo)

add_executable(DXLWDemo ${DEMO_SRC})
