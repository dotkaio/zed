# Zed Features

## Core Editing

- Multi-cursor editing
- Find and replace (in file and across the entire project)
- Code completions from language servers
- AI-powered edit predictions (multi-line suggestions as you type)
- Snippets with tab stops and placeholders
- Multi-buffer editing (edit multiple files in one view)
- Select larger or smaller syntax nodes
- Go to definition, find all references
- Inline diagnostics and quick fixes
- Code formatting and linting integration
- Code folding
- Semantic token highlighting
- Syntax highlighting for 65+ languages via Tree-sitter
- Selection highlighting (all occurrences of selected text are highlighted)
- Search match highlighting
- Bracket matching and highlighting
- Current line highlighting
- Git diff highlighting in the gutter and inline

## Navigation

- Command palette (fuzzy search over all actions)
- File finder (fuzzy search over project files)
- Project-wide symbol search
- Outline panel (symbols in the current file)
- Tab switcher ordered by recent use
- Breadcrumbs showing current code context

## AI

- Agent panel for agentic coding workflows
- Inline assistant for in-place code transformations
- Edit predictions (keystroke-level AI completions)
- Text thread conversations embedded in the editor
- AI rules to shape agent behavior
- Tool use: file operations, terminal, web search, diagnostics
- Tool permissions to control what the agent can access
- MCP (Model Context Protocol) server integration
- Supports multiple providers: Anthropic, OpenAI, Google, Ollama, GitHub Copilot, Codestral, and more
- Local model support
- Zero-data retention options with supported providers

## Git

- Git panel for staging and unstaging files and individual hunks
- File history viewer
- Project diff view with editable hunks
- Inline git blame
- Git gutter indicators (added, modified, deleted lines)
- Fetch, push, and pull operations
- Multi-remote support with remote selector
- Word-level diff highlighting

## Terminal & Tasks

- Built-in terminal
- Multiple terminal instances with splitting and tabs
- Task system with context variables (file, selection, project, etc.)
- Project-specific and global task definitions
- REPL support for Python, TypeScript, R, Julia, and Scala
- Interactive code execution with inline output results
- Cell mode using `# %%` separators

## Debugger

- Set breakpoints and step through code
- Inspect variables and call stack
- Attach to running processes or launch new ones
- Supports: C/C++, Go, Java, JavaScript/TypeScript, PHP, Python, Ruby, Rust
- Debug Adapter Protocol (DAP) support
- Debugger extensions for additional languages

## Language Support

- 65+ programming languages out of the box
- Language Server Protocol (LSP) integration
- Automatic language detection
- Per-language settings and toolchain configuration
- Configurable language servers per project

## Remote Development

- SSH remote development (local UI, remote backend)
- Dev container support (`devcontainer.json`)
- Docker and Podman integration
- Remote terminals, tasks, and language servers
- Remote debugging

## Collaboration

- Real-time multiplayer editing
- Shared project sessions
- Channels for persistent team collaboration
- Contacts list and private calls
- Voice chat
- Live cursor and edit visibility
- Access control for shared sessions

## Customization

- Keybinding editor with a UI and JSON file
- Preset keymaps: VS Code, Atom, Emacs, JetBrains, Sublime Text, TextMate, Cursor
- Vim mode
- Helix mode
- Color themes with light, dark, and system-follow options
- Icon themes
- Font family, size, and feature settings (ligatures, etc.) per context (editor, UI, terminal)
- UI density and zoom controls

## Project & Workspace

- Project panel (file explorer with git status indicators)
- Multi-project workspaces
- Project-specific settings and tasks
- Recent projects list
- File and folder context menus

## Extensions

- Language extensions
- Debugger extensions
- Theme and icon theme extensions
- Slash command extensions
- MCP and context server extensions
- Extension marketplace with install/update management

## Search

- Project-wide text search with regex support
- Multi-buffer results view
- Search result navigation
- Filter by language or file glob

## Previews

- Markdown preview
- SVG preview
- Image viewer

## Settings

- Settings editor UI (searchable)
- Settings JSON file
- Project-level settings overrides
- All settings discoverable through the command palette

## Platform Support

- macOS (Intel and Apple Silicon)
- Linux (x86_64 and arm64)
- Windows
