# 🟦 <span style="color:#4A90E2;">MCP File System Configuration</span>

<div style="background-color:#1e1e1e; padding:20px; border-radius:8px; font-family:monospace; color:#d4d4d4;">
<span style="color:#569cd6;">{</span><br>
&nbsp;&nbsp;<span style="color:#9cdcfe;">"mcpServers"</span><span style="color:#d4d4d4;">:</span> <span style="color:#569cd6;">{</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#9cdcfe;">"filesystem"</span><span style="color:#d4d4d4;">:</span> <span style="color:#569cd6;">{</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#9cdcfe;">"command"</span><span style="color:#d4d4d4;">:</span> <span style="color:#ce9178;">"npx"</span><span style="color:#d4d4d4;">,</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#9cdcfe;">"args"</span><span style="color:#d4d4d4;">:</span> <span style="color:#569cd6;">[</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ce9178;">"-y"</span><span style="color:#d4d4d4;">,</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ce9178;">"@modelcontextprotocol/server-filesystem"</span><span style="color:#d4d4d4;">,</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ce9178;">"C:\\Users\\tinum\\Desktop"</span><span style="color:#d4d4d4;">,</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ce9178;">"C:\\Users\\tinum\\Documents"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#569cd6;">]</span><span style="color:#d4d4d4;">,</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#9cdcfe;">"disabled"</span><span style="color:#d4d4d4;">:</span> <span style="color:#569cd6;">false</span><span style="color:#d4d4d4;">,</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#9cdcfe;">"autoApprove"</span><span style="color:#d4d4d4;">:</span> <span style="color:#569cd6;">[]</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#569cd6;">}</span><br>
&nbsp;&nbsp;<span style="color:#569cd6;">}</span><br>
<span style="color:#569cd6;">}</span>
</div>

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

<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 15px; border-radius: 8px; border-left: 4px solid #4A90E2;">
<span style="color: white; font-weight: bold;">🎨 Color Scheme Used:</span><br>
<span style="color: #FFE4E1;">• Keys: <span style="color:#9cdcfe;">Light Blue</span></span><br>
<span style="color: #FFE4E1;">• String Values: <span style="color:#ce9178;">Orange</span></span><br>
<span style="color: #FFE4E1;">• Boolean/Brackets: <span style="color:#569cd6;">Blue</span></span><br>
<span style="color: #FFE4E1;">• Background: <span style="color:#1e1e1e;">Dark Theme</span></span>
</div>

> <span style="color:#007ACC;">**📝 Note:**</span>  
> This uses <span style="color:#E91E63;">VS Code Dark Theme</span> inspired colors for better readability and syntax highlighting in <span style="color:#FF9800;">HTML-supported Markdown</span> environments.
