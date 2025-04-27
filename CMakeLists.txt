
file(GLOB SOURCE_FILES "*.cpp" "*.h")


add_library(ImGuizmo STATIC ${SOURCE_FILES})

target_include_directories(ImGuizmo PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
target_include_directories(ImGuizmo PUBLIC ../imgui)
