# personalConfig
my personal config

# starship
# 设置配置范例，开启编辑器的自动补全
"$schema" = 'https://starship.rs/config-schema.json'

# 在命令之间插入空行
add_newline = false

#format = "[➜](bold green)$directory$rust$package"

# 将提示符的“❯”替换为“➜”
[character] # “character”是我们正在配置的组件
success_symbol = "[➜](bold green)" # 设置“success_symbol” 字段为绿色加粗的“➜”
error_symbol = "[➜](bold red)"

# 禁用 package 组件，完全隐藏它的提示符
[package]
disabled = true

[nodejs]
format = "[ ](bold green)"

[git_branch]
format = "[$symbol$branch(:$remote_branch)]($style) "
