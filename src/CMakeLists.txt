add_subdirectory(engine)

set(MIDAS_MINER_SOURCES
	${MIDAS_MINER_SOURCES}

	${CMAKE_CURRENT_SOURCE_DIR}/main.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/Game.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/Game.h
	${CMAKE_CURRENT_SOURCE_DIR}/Const.h
	${CMAKE_CURRENT_SOURCE_DIR}/Text.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/Text.h
	${CMAKE_CURRENT_SOURCE_DIR}/Gem.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/Gem.h
	${CMAKE_CURRENT_SOURCE_DIR}/Field.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/Field.h
	${CMAKE_CURRENT_SOURCE_DIR}/TextureEntity.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/TextureEntity.h

	PARENT_SCOPE
)