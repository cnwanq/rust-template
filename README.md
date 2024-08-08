# Rust 模板项目

## 环境设置

### 安装 Rust

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### 推荐 VSCode 插件：

- [Dependi](https://dependi.io/): 依赖管理工具
- Even Better TOML: TOML 文件支持
- Better Comments: 优化注释显示
- Error Lens: 错误提示优化
- GitLens: Git 增强
- indent-rainbow: 缩进显示优化
- Prettier: 代码格式化
- REST Client: REST API 调试工具
- rust-analyzer: Rust 语言分析工具
- Rust Test Lens: Rust 测试工具
- Rust Test Explorer: Rust 测试概览
- TODO Highlight: TODO 高亮
- vscode-icons: 文件图标
- YAML: YAML 文件支持


### 安装 cargo generate

cargo generate 是一个用于生成项目模板的工具。它可以使用已有的 github repo 作为模版生成新的项目。

```bash
cargo install cargo-generate
```

使用 cargo generate 生成项目
```bash
cargo generate github_username/repo_name

e.g.: cargo generate tyr-rust-bootcamp/template
```

### 安装 pre-commit

pre-commit 是一个代码检查工具，可以在提交代码前进行代码检查。
```bash
brew install pre-commit
-- or --
pip install pre-commit
```
安装成功后，运行 `pre-commit install` 安装 git hook。

### 安装 typos

typos 是一个用于检查拼写错误的工具。
```bash
cargo install typos-cli
```

### 安装 git cliff

git cliff 是一个生成 changelog 的工具。
```bash
cargo install git-cliff
```

### 安装 cargo nextest

cargo nextest 是一个用于测试的插件。
```bash
cargo install cargo-nextest --locked
```
