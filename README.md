# BlizzMove_CNWotLK
 Personal modified version

 Start From [BlizzMove 3.6.10](https://github.com/Kiatra/BlizzMove/tree/v3.6.10)

# 修改原因
国服怀旧服目前插件接口的版本和海外插件接口版本不一致，导致海外 WLK 可用的插件无法在国服使用，或者有各种报错。

## Change Log
### 2025/2/1
- 在 `BlizzMove.lua`中，使用了较新的 `C_AddOns.GetNumAddOns` 接口，检测为中国大陆服务器时，替换为旧版的 `GetNumAddOns`。
- 在 `BlizzMove.lua`中，使用了较新的 `C_AddOns.GetAddOnInfo` 接口，检测为中国大陆服务器时，替换为旧版的 `GetAddOnInfo`。
