add_falcor_executable(ElishRender)

target_sources(ElishRender PRIVATE
    ElishRender.cpp
    ElishRender.h
)

target_copy_shaders(ElishRender Samples/ElishRender)

target_source_group(ElishRender "Samples")
