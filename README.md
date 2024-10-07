# CEDARScript LLM Prompt Engineering

# Comparison of Edit Formats

### Gemini 1.5 PRO conversations

This table compares the performance of different edit formats (`diff-fenced` and `CEDARScript`)
for various benchmark tasks in `Gemini 1.5 PRO` conversations.

| Task                                          | Edit Format | Lines | Result |
|-----------------------------------------------|-------------|-------|--------|
| doc_DocCLI_get_role_man_text                  | [diff-fenced](examples/gemini-1.5-pro/doc_DocCLI_get_role_man_text/diff-fenced.aider.chat.history.md) | 4948 | FAILED (failures=1) |
| doc_DocCLI_get_role_man_text                  | [CEDARScript](examples/gemini-1.5-pro/doc_DocCLI_get_role_man_text/cedarscript.aider.chat.history.md) | 45 | OK |
| analyzer_cli_DebugAnalyzer__make_source_table | [diff-fenced](examples/gemini-1.5-pro/analyzer_cli_DebugAnalyzer__make_source_table/diff-fenced.aider.chat.history.md) | 4497 | FAILED (failures=1) |
| analyzer_cli_DebugAnalyzer__make_source_table | [CEDARScript](examples/gemini-1.5-pro/analyzer_cli_DebugAnalyzer__make_source_table/cedarscript.aider.chat.history.md) | 164 | OK |
