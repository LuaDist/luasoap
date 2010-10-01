# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(luasoap NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
INCLUDE(dist.cmake)

# Install all files and documentation
INSTALL (FILES soap.lua http.lua DESTINATION ${INSTALL_LMOD})
INSTALL (FILES README DESTINATION ${INSTALL_DATA})
INSTALL (FILES index.html manual.html license.html luasoap.png DESTINATION ${INSTALL_DOC})
INSTALL (FILES test.lua DESTINATION ${INSTALL_TEST})
