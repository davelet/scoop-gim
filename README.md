# scoop-gim

## 发布过程

### 1. 在windows系统下打包项目

```bash
cargo build --release
```

### 2. 压缩可执行文件

用任意压缩软件将上一步生成的 `gim.exe` 压缩成zip，重命名压缩包为 `gim-{version}.zip`。

### 3. 上传到Release

### 4. 把上传后的链接放进这里的 URL

### 5. 把上传后的sha256放进这里的hash
压缩包上传后，github会自动计算并显示sha256值，直接复制即可。

### 6. 记得修改这里的版本号
