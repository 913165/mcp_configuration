# 🟦 <span style="color:#4A90E2;">MCP File System Configuration</span>

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

> **🟩 <span style="color:#28A745;">Explanation:</span>**
>
> - This file provides the <span style="color:#6F42C1;">configuration details</span> for setting up MCP servers using the filesystem method on <span style="color:#FF6B35;">Windows</span>.
> - Ensure that the specified <span style="color:#17A2B8;">folders and files exist</span> at the given paths (`<span style="color:#DC3545;">C:\Users\tinum\Desktop</span>` and `<span style="color:#DC3545;">C:\Users\tinum\Documents</span>`).
> - The configuration uses <span style="color:#FFC107;">`npx`</span> to run the <span style="color:#6610F2;">`@modelcontextprotocol/server-filesystem`</span> package.
> - The <span style="color:#20C997;">`disabled`</span> flag is set to <span style="color:#28A745;">`false`</span>, meaning the filesystem MCP server is <span style="color:#28A745;">**enabled**</span>.
> - The <span style="color:#FD7E14;">`autoApprove`</span> array is currently <span style="color:#6C757D;">empty</span>, which can be used for automated approval settings if needed.
> 
> <span style="color:#BADA55;">**⚡ This setup is essential for proper MCP operation on Windows, so double-check paths and permissions!**</span>

---

> <span style="color:#007ACC;">**📝 Note:**</span>  
> Markdown does not natively support color for text, but you can use HTML `<span>` tags with <span style="color:#E91E63;">inline styles</span> for color in environments that support it (like some <span style="color:#FF9800;">GitHub-flavored Markdown</span> renderers or <span style="color:#9C27B0;">documentation sites</span>).

<div style="background: linear-gradient(90deg, #FF6B35, #F7931E, #FFD23F); padding: 10px; border-radius: 5px; margin: 10px 0;">
<span style="color: white; font-weight: bold;">🎨 Pro Tip: Use complementary colors and maintain readability for the best visual experience!</span>
</div>
