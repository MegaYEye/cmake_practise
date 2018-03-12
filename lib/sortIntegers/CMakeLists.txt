add_library(SortInteger SortIntegers.cpp)
set_property(TARGET SortInteger PROPERTY CXX_STANDARD 14)
install(TARGETS SortInteger DESTINATION lib)