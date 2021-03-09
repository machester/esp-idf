| Supported Targets | ESP32 | ESP32-S2 | ESP32-C3 |
| ----------------- | ----- | -------- | -------- |

# Build only test for C++/C configuration

This test application aims to exercise different configuration options using standard espressif initialization pattern:
```
component_config cfg = COMPONENT_DEFAULT_CFG();
cfg.member1 = custom_config_for_member1;
...
cfg.memberN = custom_config_for_memberN;
esp_err_t = component_init(cfg);
```
To be build with both C++ and C compilers.