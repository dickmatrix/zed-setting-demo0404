{\rtf1\ansi\ansicpg936\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww12920\viewh7080\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \{\
  "which_key": \{\
    "enabled": true,\
  \},\
  "autosave": "on_window_change",\
  "base_keymap": "Cursor",\
  "git_panel": \{\
    "tree_view": true,\
    "sort_by_path": true,\
  \},\
  "theme": "One Dark",\
  "icon_theme": "Material Icon Theme",\
  "ui_font_family": "Source Code Pro",\
  "ui_font_size": 16,\
  "buffer_font_family": "Source Code Pro",\
  "buffer_font_size": 16,\
  "tab_size": 2,\
  "hard_tabs": false,\
  "format_on_save": "on",\
  "remove_trailing_whitespace_on_save": true,\
  "ensure_final_newline_on_save": true,\
  "show_line_numbers": true,\
  "indent_guides": \{\
    "enabled": true,\
    "line_width": 1,\
    "active_line_width": 1,\
    "coloring": "fixed",\
  \},\
  "project_panel": \{\
    "button": true,\
    "default_width": 240,\
    "dock": "left",\
  \},\
  "tabs": \{\
    "git_status": true,\
    "close_position": "right",\
  \},\
  "minimap": \{\
    "show": "always",\
  \},\
  "title_bar": \{\
    "show_branch_icon": true,\
    "show_menus": true,\
  \},\
  "git": \{\
    "inline_blame": \{\
      "enabled": true,\
      "show_commit_summary": true,\
    \},\
    "gutter_deletions": true,\
    "gutter_insertions": true,\
  \},\
  "agent": \{\
    "default_profile": "minimal",\
    "show_turn_stats": true,\
    "default_model": \{\
      "provider": "kimi2",\
      "model": "moonshot-v1-128k",\
      "enable_thinking": false,\
    \},\
    "favorite_models": [],\
    "model_parameters": [],\
    "llm": \{\
      "default_provider": "moonshot",\
      "providers": \{\
        "moonshot": \{\
          "api_key": "sk-...",\
          "api_endpoint": "https://api.moonshot.cn/v1",\
          "default_model": "moonshot-v1-32k",\
          "available_models": [\
            "moonshot-v1-8k",\
            "moonshot-v1-32k",\
            "moonshot-v1-128k",\
            "moonshot-v1-256k",\
          ],\
        \},\
      \},\
    \},\
  \},\
  "language_models": \{\
    "openai_compatible": \{\
      "minimax": \{\
        "api_url": "https://llm.hytriu.cn/v1",\
        "available_models": [\
          \{\
            "name": "MiniMax-M2.7-highspeed",\
            "max_tokens": 200000,\
            "max_output_tokens": 32000,\
            "max_completion_tokens": 200000,\
            "capabilities": \{\
              "tools": true,\
              "images": true,\
              "parallel_tool_calls": true,\
              "prompt_cache_key": true,\
              "chat_completions": true\
            \}\
          \}\
        ]\
      \},\
      "deepseek\uc0\u33258 \u29992 ": \{\
        "api_url": "https://api.deepseek.com/v1",\
        "available_models": [\
          \{\
            "name": "DeepSeek-V3.2",\
            "max_tokens": 200000,\
            "max_output_tokens": 32000,\
            "max_completion_tokens": 200000,\
            "capabilities": \{\
              "tools": true,\
              "images": true,\
              "parallel_tool_calls": true,\
              "prompt_cache_key": true,\
              "chat_completions": true\
            \}\
          \}\
        ]\
      \},\
      "kimi2": \{\
        "api_url": "https://api.moonshot.cn/v1",\
        "available_models": [\
          \{\
            "name": "moonshot-v1-128k",\
            "max_tokens": 200000,\
            "max_output_tokens": 32000,\
            "max_completion_tokens": 200000,\
            "capabilities": \{\
              "tools": true,\
              "images": true,\
              "parallel_tool_calls": true,\
              "prompt_cache_key": true,\
              "chat_completions": true,\
            \},\
          \},\
        ],\
      \},\
      "kimi": \{\
        "api_url": "https://api.moonshot.cn/v1",\
        "available_models": [\
          \{\
            "name": "Kimi-K2.5",\
            "max_tokens": 200000,\
            "max_output_tokens": 32000,\
            "max_completion_tokens": 200000,\
            "capabilities": \{\
              "tools": true,\
              "images": true,\
              "parallel_tool_calls": true,\
              "prompt_cache_key": true,\
              "chat_completions": true,\
            \},\
          \},\
        ],\
      \},\
    \},\
  \},\
  "agent_servers": \{\
    "kimi": \{\
      "type": "registry",\
    \},\
  \},\
  "experimental": \{\
    "agent_cluster": \{\
      "kimi-code-cli": \{\
        "workspace_permissions": ["read", "write", "execute"],\
        "command_timeout": 45000,\
      \},\
      "thread_pool_size": 4,\
      "roles": \{\
        "code_reviewer": \{\
          "model": "kimi-k2.5",\
          "workspace_permissions": ["read"],\
        \},\
        "code_generator": \{\
          "model": "kimi-k2.5",\
          "workspace_permissions": ["read", "write"],\
        \},\
        "terminal_executor": \{\
          "model": "kimi-k2.5",\
          "workspace_permissions": ["read", "write", "execute"],\
          "timeout_ms": 45000,\
        \},\
      \},\
    \},\
  \},\
  "telemetry": \{\
    "diagnostics": false,\
    "metrics": false,\
  \},\
  "file_scan_exclusions": [\
    "**/.env*",\
    "**/*.pem",\
    "**/*.key",\
    "**/*_rsa",\
    "**/secrets.json",\
    "**/node_modules",\
    "**/.git",\
  ],\
  "edit_predictions": \{ "mode": "subtle" \},\
  "terminal": \{\
    "font_family": ".SystemUIFont",\
    "font_size": 14,\
    "line_height": "comfortable",\
  \},\
  "ssh_connections": [\
    \{\
      "host": "zed-openclaw",\
      "args": [],\
      "projects": [\{ "paths": ["/config"] \}],\
    \},\
  ],\
  "git_hosting_providers": [\
    \{\
      "provider": "gitlab",\
      "name": "Self Host Git",\
      "base_url": "http://192.168.1.110/",\
    \},\
  ],\
  "lsp": \{\
    "clangd": \{\
      "binary": \{\
        "path": "D:/clangd/bin/clangd.exe",\
        "arguments": [\
          "--compile-commands-dir=.edkCode",\
          "--header-insertion=never",\
        ],\
      \},\
    \},\
  \},\
\}\
}