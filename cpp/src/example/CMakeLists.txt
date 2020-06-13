add_executable(rest_test rest_test.cc)
target_link_libraries(rest_test ssl crypto rest util ${Boost_LIBRARIES})
