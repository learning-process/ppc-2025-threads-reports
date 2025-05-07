message(STATUS "kholin_k_multidim_integrals_rect tasks")

SUBDIRLIST(subdirs ${CMAKE_CURRENT_SOURCE_DIR})

foreach(subd ${subdirs})
  add_subdirectory(${subd})
endforeach()
