# Passenger 

1. passenger 基于ruby开发的，所以安装时会自动安装ruby，ruby命令全局可用。故,在组合项目中，role_passenger 必须在 role_ruby 之前安装，以保证 role_ruby 安装结果不会被破坏。
2. passenger 有 apache, nginx, stardone 等三个版本
