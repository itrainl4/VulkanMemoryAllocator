#
# Add subdirectories to build.
#
add_library(vma INTERFACE)

#
# Set compile definitions
#

target_include_directories(
    vma
    INTERFACE
        src
)

#    target_compile_definitions(
#        khronos
#        INTERFACE
#            VK_USE_PLATFORM_WIN32_KHR
#    )
