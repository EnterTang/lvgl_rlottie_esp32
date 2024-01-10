# lvgl配置
## 修改lvgl/env_suppout/cmake/esp.cmake
```cmake
  idf_component_register(SRCS ${SOURCES} ${EXAMPLE_SOURCES} ${DEMO_SOURCES}
      INCLUDE_DIRS ${LVGL_ROOT_DIR} ${LVGL_ROOT_DIR}/src ${LVGL_ROOT_DIR}/../
                   ${LVGL_ROOT_DIR}/examples ${LVGL_ROOT_DIR}/demos
      REQUIRES esp_timer rlottie)
endif()
```
