add_executable(MultiAppender Main.cpp)
target_link_libraries(MultiAppender plog)
set_target_properties(MultiAppender PROPERTIES FOLDER Samples)