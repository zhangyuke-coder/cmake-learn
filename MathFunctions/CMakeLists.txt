add_library(MathFunctions mysqrt.cxx)

install (TARGETS MathFunctions DESTINATION ${PROJECT_BINARY_DIR}/bin)
install (FILES MathFunctions.h
         DESTINATION ${PROJECT_BINARY_DIR}/include)