# เชื่อม FigCraft กับ Codex / Claude

คู่มือนี้อ้างอิง CLI/MCP ของแอปต้นฉบับ ไม่ใช่ผลทดสอบ runtime ของรุ่น TH ซึ่งยังไม่เผยแพร่

- [เอกสาร MCP ต้นฉบับ](https://github.com/storytold/figcraft/blob/bb4680d1b820f5dc345eaeb34ddff581a5b46017/docs/mcp.md)
- [คู่มือ Codex / Claude / MCP บนวันละ Craft](https://tapanapon.com/blog/one-per-craft-connect-codex-claude-mcp)
- [macOS CLI ต้นฉบับรุ่นที่ตรวจ](https://github.com/storytold/figcraft/releases/download/v0.16.0/figcraft-cli-0.16.0-macos-universal.zip)

เริ่มจากหา absolute path ของ `figcraft-cli` หรือ `figcraft-cli.exe` แล้วตรวจ `--help` และ `mcp --help` ตามเอกสารต้นฉบับ การมีตัว GUI ไม่ได้ลงทะเบียน MCP อัตโนมัติ

ตัวอย่างโครงคำสั่ง โดยต้องแทน `ABSOLUTE_CLI_PATH` และ `MCP_ARGUMENTS` ตามระบบและแอปจริง:

```text
codex mcp add figcraft -- ABSOLUTE_CLI_PATH mcp MCP_ARGUMENTS
claude mcp add --transport stdio figcraft -- ABSOLUTE_CLI_PATH mcp MCP_ARGUMENTS
```

อย่ารัน placeholder ด้านบนตรง ๆ โหมด headless ทำงานในเซสชันแยกจากหน้าต่าง GUI; การสั่งหน้าต่างจริงต้องใช้ flag และพอร์ตที่แอปนั้นรองรับ อ่านเรื่อง file roots และ token จากต้นฉบับก่อนตั้งค่า

## English

Locate the installed upstream CLI and verify its help output. Register its absolute path and app-specific MCP arguments with Codex or Claude Code; Claude Desktop uses its local MCP configuration. The example is a template, not a ready-to-run command. Runtime integration of a Thai build is not claimed.
