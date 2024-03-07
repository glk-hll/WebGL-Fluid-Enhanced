
### 环境搭建
> 目前只支持 ** Linux (x64 & arm64) and macOS (x64 & Apple Silicon) **
1. 安装 `bun`
```bash
  # with install script (recommended)
  curl -fsSL https://bun.sh/install | bash

  # with npm
  npm install -g bun

  # with Homebrew
  brew tap oven-sh/bun
  brew install bun

  # with Docker
  docker pull oven/bun
  docker run --rm --init --ulimit memlock=-1:-1 oven/bun
```

2. 测试 `bun`
```bash
  bun -h
```

### 启动
```bash
  # 安装依赖
  bun install

  # 启动
  bun watch
  bun dev
```

