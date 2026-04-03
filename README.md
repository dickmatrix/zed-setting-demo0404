优化说明（基于附件1教程）：
文件扫描排除优化 - 添加 venv、.venv、__pycache__、target、dist 等常见大文件夹排除，解决"打开超大项目时内存占用过高"问题
终端虚拟环境检测 - 明确配置 detect_venv 自动识别 .venv/venv 等目录，实现教程所述"自动识别项目虚拟环境，无需手动激活"
诊断增强 - 添加 diagnostics 配置，配合 F8 快捷键循环跳转错误，强化改bug效率
动画性能优化 - 建议根据电脑性能在设置中搜索 animation 手动调整（配置文件中无需显式设置，保留默认即可）
预览标签页 - 添加 preview_tabs 配置，配合 Cmd+P 快速跳转文件时启用预览模式，提升文件浏览效率
Git 增强 - 添加 show_inline_comparisons 和 scrollbar.git_diff，强化教程所述"行号旁颜色标记修改"功能
智能保存 - 保持 on_window_change 并添加 autosave_delay_ms 防抖，防止频繁保存触发格式化
目录环境加载 - 添加 load_direnv: shell_hook，确保终端自动加载项目环境变量
