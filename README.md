# Portfolio - Lâm Tấn Thịnh

Portfolio website chuyên nghiệp cho HTML Banner Designer & Front-End Developer.

## Thông tin

**Tên:** Lâm Tấn Thịnh
**Chuyên môn:** HTML Banner Design, Front-End Development
**Học vấn:** Khoa Học Máy Tính (2021-2025) - Đại Học Bách Khoa Hồ Chí Minh

## Tính năng

- ✅ Responsive design (mobile-friendly)
- ✅ Modern UI/UX với gradient effects
- ✅ Smooth scroll navigation
- ✅ Animated cards và transitions
- ✅ Project showcase với hover effects
- ✅ Skills section với icons
- ✅ Contact form
- ✅ Mobile hamburger menu

## Cấu trúc file

```
tanthinhvnex.github.io/
├── index.html          # Trang chủ
├── styles.css          # Styles chính
├── script.js           # JavaScript interactions
└── README.md           # Hướng dẫn này
```

## Cách sử dụng

### 1. Deploy lên GitHub Pages

1. Đảm bảo repository có tên: `tanthinhvnex.github.io`
2. Push tất cả files lên GitHub:
```bash
git add .
git commit -m "Initial portfolio commit"
git push origin main
```

3. Vào Settings > Pages
4. Source: chọn branch `main` và folder `/ (root)`
5. Save và đợi vài phút
6. Website sẽ có tại: `https://tanthinhvnex.github.io`

### 2. Cập nhật thông tin cá nhân

Mở `index.html` và chỉnh sửa:

**Email & GitHub:**
```html
<!-- Dòng ~274 -->
<span>your.email@example.com</span>

<!-- Dòng ~278 -->
<a href="https://github.com/tanthinhvnex" target="_blank">github.com/tanthinhvnex</a>
```

### 3. Thêm link projects

Thay thế các link placeholder bằng link thực tế của bạn:

```html
<!-- Tìm các thẻ <a> trong .project-overlay -->
<a href="#" class="project-link" target="_blank">
<!-- Thay "#" bằng link GitHub Pages hoặc demo của project -->
<a href="https://tanthinhvnex.github.io/your-project" class="project-link" target="_blank">
```

### 4. Thêm screenshots projects

1. Tạo folder `images/` trong repository
2. Thêm screenshots (khuyến nghị 600x400px)
3. Cập nhật src trong `index.html`:

```html
<!-- Thay placeholder bằng ảnh thật -->
<img src="images/project1.png" alt="Web Project 1">
```

### 5. Tùy chỉnh màu sắc

Mở `styles.css` và chỉnh sửa biến CSS (dòng 9-18):

```css
:root {
    --primary-color: #667eea;      /* Màu chính */
    --secondary-color: #764ba2;    /* Màu phụ */
    --accent-color: #f093fb;       /* Màu nhấn */
    /* ... */
}
```

## Các section chính

1. **Hero Section** - Trang chủ với tên và mô tả
2. **About** - Giới thiệu bản thân, học vấn, thống kê
3. **Projects** - Showcase 2 web apps + 4 landing pages
4. **Skills** - HTML5, CSS3, JavaScript, PHP, Responsive Design, Banner Design
5. **Contact** - Form liên hệ và thông tin

## Checklist hoàn thiện portfolio

- [ ] Cập nhật email cá nhân
- [ ] Kiểm tra link GitHub profile
- [ ] Thêm link demo cho 2 web projects
- [ ] Thêm link demo cho 4 landing pages
- [ ] Upload screenshots cho tất cả projects
- [ ] Thêm social media links (LinkedIn, Facebook nếu có)
- [ ] Test responsive trên mobile/tablet
- [ ] Test form liên hệ
- [ ] Kiểm tra tất cả links hoạt động

## Tips để tối ưu portfolio

1. **Screenshots chất lượng cao:** Chụp ảnh projects ở resolution tốt
2. **Mô tả rõ ràng:** Viết mô tả chi tiết cho mỗi project
3. **Live demos:** Deploy tất cả projects lên GitHub Pages để có link demo
4. **Testimonials:** Nếu có feedback từ clients, thêm vào section riêng
5. **Blog (tùy chọn):** Có thể thêm section blog về web development
6. **Analytics:** Thêm Google Analytics để theo dõi visitors

## Customization nâng cao

### Thêm project mới:

Copy một `.project-card` và paste, sau đó chỉnh sửa:
```html
<div class="project-card">
    <div class="project-image">
        <img src="images/new-project.png" alt="New Project">
        <div class="project-overlay">
            <a href="https://demo-link.com" class="project-link" target="_blank">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
    <div class="project-info">
        <h4>Project Name</h4>
        <p>Project description...</p>
        <div class="project-tags">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
        </div>
    </div>
</div>
```

### Thêm skill mới:

```html
<div class="skill-card">
    <div class="skill-icon">
        <i class="fab fa-react"></i> <!-- Font Awesome icon -->
    </div>
    <h4>Skill Name</h4>
    <p>Skill description</p>
</div>
```

## Hỗ trợ

Nếu cần thêm tính năng hoặc có vấn đề, hãy:
1. Check documentation: https://docs.github.com/pages
2. Font Awesome icons: https://fontawesome.com/icons
3. Gradient generator: https://cssgradient.io/

## License

Free to use for personal portfolio.

---

**Chúc bạn thành công với portfolio và freelance career!** 🚀