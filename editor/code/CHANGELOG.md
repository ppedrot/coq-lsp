# coq-lsp 0.1.4: View
----------------------

- The keybinding alt+enter in VSCode is now correctly scoped to be
  only active on Coq files.
- Display an error message when the VSCoq extension is detected to be
  active, as `coq-lsp` and VSCoq don't work well together.
- Display an error message when the client and server versions don't
  match.
- [server-side] Support Unicode files
- [server-side] Unicode completion on `\`, configurable in settings.
- New infoview panel based on React.
- New option in settings to enable Coq Debug mode (and backtraces)
- Fixes a bug that made some `CoqProject` files not to be properly
  detected.

# coq-lsp 0.1.3: Event
----------------------

- Requires coq-lsp server 0.1.3, see full changelog at
  https://github.com/ejgallego/coq-lsp/releases/tag/0.1.3
- Default "show goals" setting is now on cursor movement, thanks to
  upgrade server request serving this is no viable.
- VsCodeVim should work with coq-lsp goal following now (be sure to
  pick the "Command" option in settings)

# coq-lsp 0.1.2: Message
------------------------

- Requires coq-lsp server 0.1.2, see full changelog at
  https://github.com/ejgallego/coq-lsp/releases/tag/0.1.2
- Extension will now enforce that server has the correct version
- The Coq LSP server output window will now show trace information
- Coq Info Panel will now show messages coming from commands such as
  `About` or `Search`
- Coq Info Panel will now show detailed error information.

# coq-lsp 0.1.1: Location
-------------------------

- Requires coq-lsp server 0.1.1, see full changelog at
  https://github.com/ejgallego/coq-lsp/releases/tag/0.1.1%2Bv8.16
- Server greatly improved in terms of responsiveness
- Improved goal panel and interaction mode
- Many new configuration options
- Code will now show a "Coq LSP Server" output window

# coq-lsp 0.1.0: Memory
-----------------------

- First public release: minimal LSP client, with support for a goal panel
