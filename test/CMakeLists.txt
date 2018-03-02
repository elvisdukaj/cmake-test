set(PROJECT_SRC "test.cpp")
add_executable(project-test $<TARGET_OBJECTS:objects> ${PROJECT_SRC})
target_include_directories(project PRIVATE ${HEADERS})
