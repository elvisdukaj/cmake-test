set(PROJECT_SRC "main.cpp")
add_executable(project $<TARGET_OBJECTS:objects> ${PROJECT_SRC})
target_include_directories(project PRIVATE ${HEADERS})
