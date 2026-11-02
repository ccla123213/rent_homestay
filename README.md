# Localhost Website

Static website chuyển từ thiết kế Figma [Localhost Website](https://www.figma.com/design/lbgy9B1FU9zbhPeCvuZkfN/Localhost-Website--Community-).

## Tính năng

- HTML5 semantic
- Responsive (mobile-first): Mobile → Tablet → Desktop
- Flexbox + CSS Grid
- Form HTML5 (search stays)
- Transition / hover effects
- Accessibility cơ bản (aria-label, focus, semantic tags)
- Clean code

## Cấu trúc

```
localhost-website/
├── index.html
├── styles.css
└── README.md
```

## Chạy local

Mở `index.html` bằng trình duyệt hoặc dùng live server.

## Deploy GitHub Pages

1. Tạo repo mới trên GitHub
2. Push code lên
3. Settings → Pages → Source: Deploy from branch `main` / root
4. Website sẽ chạy tại `https://<username>.github.io/<repo-name>/`

## Checklist kiểm thử

- [ ] Hiển thị đúng trên Desktop (≥900px)
- [ ] Hiển thị đúng trên Tablet (640–899px)
- [ ] Hiển thị đúng trên Mobile (<640px)
- [ ] Menu hamburger hoạt động trên mobile
- [ ] Form search không bị vỡ layout
- [ ] Card hover + favorite button
- [ ] Hình ảnh load đúng (Unsplash)
- [ ] Không lỗi console
