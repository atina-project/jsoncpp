if(NOT ${JSONCPP_INSTALL_LIB_ONLY})
    file(GLOB INCLUDE_FILES "json/*.h")
    install(FILES
        ${INCLUDE_FILES}
        DESTINATION ${CMAKE_INSTALL_INCLUDEDIR}/json)
endif()
