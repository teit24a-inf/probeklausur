get_filename_component(STUDENT_DIR ${CMAKE_CURRENT_SOURCE_DIR} NAME)
set(STUDENT_PREFIX ${EXAM_PREFIX}_${STUDENT_DIR})

add_subdirectory(aufgabe1)
add_subdirectory(aufgabe2)
add_subdirectory(aufgabe3)
add_subdirectory(aufgabe4)
add_subdirectory(aufgabe5)
add_subdirectory(aufgabe6)
