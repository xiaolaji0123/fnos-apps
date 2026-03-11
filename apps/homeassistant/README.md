# Home Assistant for fnOS

开源智能家居中枢平台，支持数千种智能设备的自动化控制。

> **注意**: 该应用使用宿主网络模式并启用特权运行，用于设备发现和 USB 网关接入。

## 国内优化

本版本针对中国网络环境进行了深度优化：

- **pip 清华镜像**: 已配置 `PIP_INDEX_URL=https://pypi.tuna.tsinghua.edu.cn/simple`，安装自定义组件时依赖包下载速度显著提升
- **HACS 极速版预装**: 内置 HACS 中国版（hacs-china），使用国内镜像源替代 GitHub，避免网络不稳定问题
- **首次启动**: 在「设置 → 设备与服务 → 添加集成」中搜索 HACS 完成初始化

## 推荐集成

以下是国内用户常用的智能家居集成，可在 HACS 中搜索安装：

| 集成 | 说明 | 安装方式 |
|------|------|----------|
| **Xiaomi Miot Auto** | 小米/米家设备全自动集成，支持数百款设备 | HACS → 搜索 "Xiaomi Miot Auto" |
| **Tuya** | 涂鸦智能官方集成，支持 WiFi/蓝牙设备 | 内置集成 → 搜索 "Tuya" |
| **LocalTuya** | 涂鸦智能本地控制，低延迟无需云端 | HACS → 搜索 "LocalTuya" |
| **Yeelight** | 易来/Yeelight 智能灯具控制 | 内置集成 → 搜索 "Yeelight" |
| **Aqara** | Aqara 绿米设备支持（Zigbee/蓝牙） | 内置集成 → 搜索 "Aqara" |

## 社区资源

- **瀚思彼岸**: https://bbs.hassbian.com — 国内最权威的 Home Assistant 中文社区
- **HA 中文网**: https://www.hasscn.top — 中文资源聚合，含 HACS 极速版下载
- **HACS 极速版**: https://gitee.com/hacs-china — Gitee 镜像仓库

## 注意事项

### 网络模式
- 使用 `network_mode: host` 宿主网络模式，确保 mDNS/LLMNR 设备发现正常工作
- 端口固定为 8123，无法通过向导修改（如需修改请在容器内编辑 configuration.yaml）

### USB 设备
- 启用 `privileged: true` 特权模式，支持 Zigbee/Z-Wave USB 网关（如 ConBee II、Sonoff Zigbee Dongle）
- 首次使用 USB 设备前，请在 fnOS 应用中授权设备访问

### 蓝牙支持
- 已挂载 `/run/dbus:/run/dbus:ro`，支持蓝牙设备发现和配对
- 适用于小米温湿度传感器、Aqara 蓝牙设备等 BLE 设备

### 权限说明
- 容器以非 root 用户运行（PUID/PGID 映射）
- 配置文件目录: `${TRIM_PKGVAR}/config`

## Local Build

```bash
cd apps/homeassistant && ./update_homeassistant.sh
```

构建完成后，`.fpk` 安装包位于 `dist/` 目录下。
