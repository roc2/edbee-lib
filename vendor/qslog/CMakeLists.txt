ADD_DEFINITIONS(-DQS_LOG_LINE_NUMBERS_SHORT)

SET(
  QS_LOG_INCLUDE_DIRS
  ${CMAKE_CURRENT_SOURCE_DIR}
  PARENT_SCOPE
)

SET(
  QS_LOG_SOURCES
  ${CMAKE_CURRENT_SOURCE_DIR}/QsLogDest.cpp
  ${CMAKE_CURRENT_SOURCE_DIR}/QsLog.cpp
  ${CMAKE_CURRENT_SOURCE_DIR}/QsDebugOutput.cpp
  PARENT_SCOPE
)

SET(
  QS_LOG_HEADERS
  ${CMAKE_CURRENT_SOURCE_DIR}/QsLogDest.h
  ${CMAKE_CURRENT_SOURCE_DIR}/QsLog.h
  ${CMAKE_CURRENT_SOURCE_DIR}/QsDebugOutput.h
  ${CMAKE_CURRENT_SOURCE_DIR}/QsLogLevel.h
  PARENT_SCOPE
)
