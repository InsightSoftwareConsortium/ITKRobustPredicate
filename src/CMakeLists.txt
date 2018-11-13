set(${itk-module}_SRC
predicates.c
)

add_library(${itk-module} ${${itk-module}_SRC})

target_link_libraries(${itk-module} ${ITK_LIBRARIES})

itk_module_target(${itk-module})
