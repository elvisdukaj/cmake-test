set(PROJECT_SRC "main.cpp")

add_executable(project $<TARGET_OBJECTS:objects> ${PROJECT_SRC})

#this won't work
target_link_libraries(project PRIVATE obj_libs)
