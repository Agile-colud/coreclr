add_subdirectory(daccess)
add_subdirectory(dbgutil)
add_subdirectory(ildbsymlib)
add_subdirectory(ee)
add_subdirectory(di)
if(NOT GFLAG_COMPILE_WIN_SHORT)
    add_subdirectory(shim)
endif()
