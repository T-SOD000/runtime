set(SOURCES
  test15.cpp
)

add_executable(paltest_sprintf_test15
  ${SOURCES}
)

add_dependencies(paltest_sprintf_test15 coreclrpal)

target_link_libraries(paltest_sprintf_test15
  ${COMMON_TEST_LIBRARIES}
)
