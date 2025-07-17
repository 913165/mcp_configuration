# 🟦 mcp file system configuration

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-filesystem",
        "C:\\Users\\tinum\\Desktop",
        "C:\\Users\\tinum\\Documents"
      ],
      "disabled": false,
      "autoApprove": []
    }
  }
}
```

---

> **🟩 Explanation:**
>
> - This file provides the configuration details for setting up MCP servers using the filesystem method on Windows.
> - Ensure that the specified folders and files exist at the given paths (`C:\Users\tinum\Desktop` and `C:\Users\tinum\Documents`).
> - The configuration uses `npx` to run the `@modelcontextprotocol/server-filesystem` package.
> - The `disabled` flag is set to `false`, meaning the filesystem MCP server is enabled.
> - The `autoApprove` array is currently empty, which can be used for automated approval settings if needed.

> <span style="color:#BADA55;">This setup is essential for proper MCP operation on Windows, so double-check paths and permissions!</span>

---

> <span style="color:#007acc;">**Note:**</span>  
> Markdown does not natively support color for text, but you can use HTML `<span>` tags with inline styles for color in environments that support it (like some GitHub-flavored Markdown renderers or documentation sites).
