# layer

## 第 1 步：安装基本工具

```bash
apt update && apt install -y curl git unzip wget sudo nano
```

---

### 第 2 步：安装 Foundry 和 Bun

```bash
# 安装 Foundry（forge）
curl -L https://foundry.paradigm.xyz | bash
source ~/.bashrc
foundryup

# 安装 Bun
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
```

---

### 第 3 步：安装 vlayerup 和 vlayer

```bash
curl -SL https://install.vlayer.xyz | bash
source ~/.bashrc
vlayerup
vlayer --version   # 确认成功
```

---

### 🧪 第 4 步：创建 4 个模板项目

```bash
cd /app
```

```bash
git config --global user.name "your_name"
git config --global user.email "your_email@example.com"
```

```bash
vlayer init simple-time-travel --template simple-time-travel
vlayer init simple-teleport --template simple-telepo
vlayer init simple-web-proof --template simple-web-proof
vlayer init simple-email-proof --template simple-email-proof
```
