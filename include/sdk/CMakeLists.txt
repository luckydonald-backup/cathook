target_sources(cathook PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/CGameRules.h"
        "${CMAKE_CURRENT_LIST_DIR}/HUD.h"
        "${CMAKE_CURRENT_LIST_DIR}/igamemovement.h"
        "${CMAKE_CURRENT_LIST_DIR}/iinput.h"
        "${CMAKE_CURRENT_LIST_DIR}/imaterialsystemfixed.h"
        "${CMAKE_CURRENT_LIST_DIR}/in_buttons.h"
        "${CMAKE_CURRENT_LIST_DIR}/ScreenSpaceEffects.h")

target_include_directories(cathook PRIVATE "${CMAKE_CURRENT_LIST_DIR}")