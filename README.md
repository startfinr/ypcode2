# 我是易盘
# 联系使用git

1. git 下载代码: git clone 
2. git 本地把代码放入缓存: git add xxxx
3. git 本地合入代码：git commit -m "本次何如的东西为git的使用说明"
4. git 上传代码
5. ![img_1.png](img_1.png)



# 使用代理的步骤
1. 生成 token:
方法 3：使用个人访问令牌（PAT）替代密码（GitHub 等平台适用）
GitHub 等平台已禁用 HTTPS 的密码验证，需用 Personal Access Token (PAT) 替代密码。

# 步骤
> 生成 PAT：
**GitHub：Settings → Developer Settings → Personal Access Tokens → Generate new token。**
勾选 repo 权限，生成 Token。  
使用 PAT 代替密码：  
执行 Git 操作时，密码输入框处粘贴 PAT（而不是账号密码）。  
配置 PAT 自动存储（与方法 2 结合）：  
首次输入 PAT 后，Git 会将其保存到凭证存储中，后续无需重复输入。  
