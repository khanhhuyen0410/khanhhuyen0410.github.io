# Assets Directory

Thư mục này chứa tất cả các tài nguyên tĩnh cho portfolio template.

## Cấu trúc thư mục

```
assets/
├── images/
│   ├── avatar-placeholder.jpg     # Avatar mặc định
│   ├── logo.png                   # Logo của bạn
│   ├── og-image.jpg              # Open Graph image cho SEO
│   ├── projects/                  # Hình ảnh dự án
│   │   ├── project1-thumb.jpg
│   │   ├── project1-1.jpg
│   │   └── ...
│   ├── companies/                 # Logo công ty
│   │   ├── company1.png
│   │   └── ...
│   ├── education/                 # Logo trường học
│   │   ├── university.png
│   │   └── ...
│   ├── testimonials/             # Avatar testimonials
│   │   ├── person1.jpg
│   │   └── ...
│   └── articles/                 # Thumbnail bài viết
│       ├── article1.jpg
│       └── ...
├── icons/                        # Technology icons
│   ├── angular.svg
│   ├── react.svg
│   ├── typescript.svg
│   └── ...
├── files/                        # Files để download
│   ├── resume.pdf                # CV của bạn
│   └── ...
└── README.md                     # File này
```

## Hướng dẫn sử dụng

### 1. Avatar
- Thêm ảnh avatar của bạn vào `images/avatar-placeholder.jpg`
- Kích thước khuyến nghị: 400x400px
- Format: JPG hoặc PNG

### 2. Logo
- Thêm logo của bạn vào `images/logo.png`
- Kích thước khuyến nghị: 200x50px (hoặc tỷ lệ tương tự)
- Format: PNG với background trong suốt

### 3. Dự án
- Tạo thư mục con trong `images/projects/` cho mỗi dự án
- Thêm thumbnail và screenshots
- Kích thước khuyến nghị cho thumbnail: 600x400px

### 4. Technology Icons
- Thêm các icon công nghệ vào `icons/`
- Format: SVG (khuyến nghị) hoặc PNG
- Kích thước: 64x64px

### 5. CV/Resume
- Thêm file CV của bạn vào `files/resume.pdf`
- Format: PDF
- Tên file nên giữ nguyên hoặc update trong config

## Tối ưu hình ảnh

Để tối ưu performance, hãy:

1. **Nén hình ảnh** trước khi upload
2. **Sử dụng format phù hợp**:
   - JPG cho photos
   - PNG cho images có transparency
   - SVG cho icons và logos
3. **Responsive images**: Chuẩn bị nhiều kích thước khác nhau nếu cần

## Tools khuyến nghị

- **TinyPNG**: Nén hình ảnh
- **SVGO**: Tối ưu SVG
- **ImageOptim**: Tối ưu hình ảnh trên macOS

## Lưu ý

- Tất cả đường dẫn trong config phải bắt đầu bằng `/assets/`
- Tên file không nên có dấu cách hoặc ký tự đặc biệt
- Sử dụng kebab-case cho tên file (ví dụ: `my-project-thumbnail.jpg`)
