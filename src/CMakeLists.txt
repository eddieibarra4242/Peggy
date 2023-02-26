add_executable(peggy "./main.cpp")
target_link_libraries(
        peggy
  PRIVATE project_options
          project_warnings)
