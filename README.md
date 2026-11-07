# RF4 Server Simulator Leader Fix

修复自制引线制作时普通主线、前导线和减震引线使用错误协议槽位的问题。

来源：glance522/rf4_server_simulator，分支 codex/fix-crafted-leader-material-slots。

验证：go test ./...、go vet ./...、go build ./...。

完整服务端仍以上游仓库为基线；本仓库保存本次修复涉及的源码和回归测试文件。