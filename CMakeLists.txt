set(SOURCE_FILES
  listtest.c
  heaptest.c
  strutils.c
  vectest.c
  strutiltest.c
  vector.c
  list.c
  maptest.c
  hashmap.c
  heap.c
)

add_library(ds ${SOURCE_FILES})

target_include_directories(ds PUBLIC .)
