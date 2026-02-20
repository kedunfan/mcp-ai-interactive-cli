The English version will be uploaded after development and refinement.
实现方式为时间等待然后截取内容给ai
The implementation method is to wait for a period of time, then capture the content and provide it to the AI.




==============chines中文部分==============

AI助手交互式命令行MCP服务器，支持AI输入并执行cmd终端命令。
通过Python运行本地服务器供AI访问。
 
在VS Code的代码助手MCP设置中添加：
{
"mcpServers": {
"terminal": {
"command": "python",
"args": [
"C:\mcp_terminal_server.py",
"--stdio"
],
"disabled": false,
"autoApprove": [
"new_terminal",
"terminal_status",
"interactive_input",
"execute_command"
]
}
}
}
请修改为你的实际路径后使用。

==============English Part==============

MCP server with AI assistant interactive command line, supports AI input and execution of CMD terminal commands.
Run a local server via Python for AI access.
 
Add this to your VS Code AI Assistant MCP settings:
{
"mcpServers": {
"terminal": {
"command": "python",
"args": [
"C:\mcp_terminal_server.py",
"--stdio"
],
"disabled": false,
"autoApprove": [
"new_terminal",
"terminal_status",
"interactive_input",
"execute_command"
]
}
}
}
Modify to your actual path before use.
