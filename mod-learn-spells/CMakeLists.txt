CU_SET_PATH("CMAKE_MOD_LEARNSPELLS_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/mod_learnspells.cpp")

AC_ADD_SCRIPT_LOADER("LearnAllSpells" "${CMAKE_CURRENT_LIST_DIR}/src/loader_learnspells.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/mod_learnspells.conf.dist")
