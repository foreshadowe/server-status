# Important!
从项目 https://github.com/CokeMine/ServerStatus-Hotaru 的历史版本中更改而来并自用  
请移步ServerStatus项目
---------------------------------------------------------------------------------------------------------------------
# Server-status
云探针、多服务器探针、云监控、多服务器云监控
## 安装方法

服务端：

```bash
wget https://raw.githubusercontent.com/foreshadowe/server-status/main/status.sh
bash status.sh s
```

客户端：

```
bash status.sh c
```

## 修改方法

如果你使用Toyo版本或原版本，请备份你的config文件并重新编译安装本版本服务端

配置文件：/usr/local/ServerStatus/server/config.json备份并自行添加Region

```json
{
   "username": "Name",
   "password": "Password",
   "name": "Your Servername",
   "type": "KVM",
   "host": "None",
   "location": "洛杉矶",
   "disabled": false ,
   "region": "US"
  },
```

替换配置文件，重启ServerStatus
