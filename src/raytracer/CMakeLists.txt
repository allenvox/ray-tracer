add_executable(raytracer)

set_compile_options(raytracer)

target_sources(
  raytracer
  PRIVATE
  main.cpp
)

target_include_directories(
  raytracer
  PUBLIC
  ${PROJECT_SOURCE_DIR}/external
)
