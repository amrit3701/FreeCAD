add_subdirectory(App)
if(BUILD_GUI)
#     add_subdirectory(Gui)
    add_subdirectory(AppGL)
endif(BUILD_GUI)

# install(
    # FILES
        # Gui/PathSimulator.py
    # DESTINATION
        # Mod/CAM
# )
