# 🟦 <span style="color:#4A90E2;">Kiro Default MCP Server Configuration</span>

```json
{
  "mcpServers": {
    "fetch": {
      "command": "uvx",
      "args": ["mcp-server-fetch"],
      "env": {},
      "disabled": true,
      "autoApprove": []
    }
  }
}
```

---

> **🟩 <span style="color:#28A745;">Explanation:</span>**
>
> - This is the <span style="color:#6F42C1;">default fetch server configuration</span> for Kiro MCP setup.
> - Uses <span style="color:#FFC107;">`uvx`</span> command to run the <span style="color:#6610F2;">`mcp-server-fetch`</span> package.
> - The <span style="color:#20C997;">`env`</span> object is <span style="color:#6C757D;">empty</span>, indicating no special environment variables are needed.
> - The <span style="color:#DC3545;">`disabled`</span> flag is set to <span style="color:#DC3545;">`true`</span>, meaning this server is currently <span style="color:#DC3545;">**disabled**</span>.
> - The <span style="color:#FD7E14;">`autoApprove`</span> array is <span style="color:#6C757D;">empty</span> for manual approval workflow.
> 
> <span style="color:#FF6B35;">**⚠️ Remember to set `disabled: false` to enable the fetch server!**</span>

---

<div style="background: linear-gradient(135deg, #FF6B35 0%, #F7931E 100%); padding: 15px; border-radius: 8px; border-left: 4px solid #FF6B35;">
<span style="color: white; font-weight: bold;">🔧 Quick Setup Tip:</span><br>
<span style="color: #FFE4E1;">Change <code>disabled: true</code> to <code>disabled: false</code> to activate the fetch server functionality.</span>
</div>
