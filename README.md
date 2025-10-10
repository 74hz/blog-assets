# blog-assets

这个仓库用于存储我的博客资源文件，包括图片、视频等静态资源。

## 使用方法

通过 jsDelivr CDN 可以免费加速访问仓库中的资源。

### CDN 链接格式

```
https://cdn.jsdelivr.net/gh/74hz/blog-assets@main/<文件路径>
```

### 示例

假设仓库中有以下文件结构：
```
blog-assets/
├── common/
│   └── cover.webp
└── pages/
    └── photo.jpg
```

可以通过以下链接访问：
- `https://cdn.jsdelivr.net/gh/74hz/blog-assets@main/common/cover.webp`
- `https://cdn.jsdelivr.net/gh/74hz/blog-assets@main/pages/photo.jpg`

## 说明

- `@main` 表示使用 main 分支的内容
- 也可以使用 `@<tag>` 或 `@<commit>` 来指定特定版本
- jsDelivr 会自动缓存资源，提供全球 CDN 加速
