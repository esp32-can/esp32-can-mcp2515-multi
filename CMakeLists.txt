idf_component_register(
    SRCS 
        "src/mcp25xxx_multi.c"
        "src/mcp25xxx_multi_internal.c"
    INCLUDE_DIRS "include"
    REQUIRES driver esp_timer
)

