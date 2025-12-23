# Wing改造

## 功能

### 支持散图功能

文件结构:
```
- mangaA.komga_images
-- 1.jpg
-- 2.jpg
```

需要将文件夹命名为`.komga_images`
主要修改:
* `komga/src/main/kotlin/org/gotson/komga/domain/model/MediaType.kt`
* `komga/src/main/kotlin/org/gotson/komga/domain/service/FileSystemScanner.kt` 扫库功能
* `komga/src/main/kotlin/org/gotson/komga/domain/service/BookAnalyzer.kt` 分析书本
* `komga/src/main/kotlin/org/gotson/komga/infrastructure/mediacontainer/divina/ImagesExtractor.kt` 解析书本

## 测试

账户： `admin@local.com`  密码: `1`
