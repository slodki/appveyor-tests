cmake_minimum_required(VERSION 3.12)

project(test)

# set(wxWidgets_USE_REL_AND_DBG ON)
find_package(wxWidgets REQUIRED
    COMPONENTS core qa html xml aui adv stc webview base scintilla)
