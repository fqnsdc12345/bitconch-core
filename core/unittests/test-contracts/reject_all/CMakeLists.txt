if( BITCONCHIO_COMPILE_TEST_CONTRACTS )
   add_contract( reject_all reject_all reject_all.cpp )
else()
   configure_file( ${CMAKE_CURRENT_SOURCE_DIR}/reject_all.wasm ${CMAKE_CURRENT_BINARY_DIR}/reject_all.wasm COPYONLY )
endif()
