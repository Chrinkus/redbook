add_library(vermilion	gl3w.c
			LoadShaders.cpp
			targa.cpp
			vdds.cpp
			loadtexture.cpp
			vermilion.cpp
			vbm.cpp
)

target_link_libraries(vermilion PUBLIC OpenGL)
