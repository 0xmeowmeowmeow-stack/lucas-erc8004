# Lucas ERC-8004 Metadata

把这个目录里的文件上传到 GitHub 仓库 `lucas-erc8004` 根目录。

需要上传的文件：
- `lucas-agent.json`
- `lucas.jpg`（手动放进去）
- `README.md`

GitHub Pages 开启后，目标地址应为：
- https://0xmeowmeowmeow-stack.github.io/lucas-erc8004/lucas-agent.json
- https://0xmeowmeowmeow-stack.github.io/lucas-erc8004/lucas.jpg

部署成功后，本地执行：

```bash
AGENT_URI=https://0xmeowmeowmeow-stack.github.io/lucas-erc8004/lucas-agent.json node erc8004/register-lucas.js
```
