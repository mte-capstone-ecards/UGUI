set(LIB_DIR ${CMAKE_CURRENT_SOURCE_DIR})

set(LIB_SOURCES     "")
set(LIB_INCLUDES    "")
set(LIB_DEFINES     "")

set(LIB_SOURCES ${LIB_SOURCES}
    ${LIB_DIR}/ugui.c
    # ${LIB_DIR}/ugui_button.c
    # ${LIB_DIR}/ugui_checkbox.c
    # ${LIB_DIR}/ugui_image.c
    ${LIB_DIR}/ugui_textbox.c
    # ${LIB_DIR}/ugui_progress.c
    # ${LIB_DIR}/ugui_sim.c
    # ${LIB_DIR}/ugui_sim_x11.c
    ${LIB_DIR}/Fonts/font_6x10.c
)

set(LIB_INCLUDES ${LIB_INCLUDES}
    ${LIB_DIR}
)

set(LIB_SOURCES ${LIB_SOURCES} PARENT_SCOPE)
set(LIB_INCLUDES ${LIB_INCLUDES} PARENT_SCOPE)
set(LIB_DEFINES ${LIB_DEFINES} PARENT_SCOPE)


