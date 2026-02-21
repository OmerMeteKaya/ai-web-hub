# Architecture

## High Level

The app is a lightweight desktop hub built with Tauri.

Components:

1. Sidebar navigation
2. Webview container
3. Command palette (Ctrl+K)
4. Optional AI summarizer service

## Data Flow

User action → UI → Webview load → Optional AI processing

## Constraints

- Must stay lightweight
- Minimal dependencies
- Fast startup time
- Keyboard-first design

## Future

- Unified search
- Cross-site search
- Local embeddings
