# 🚀 CV Portfolio - Nguyễn Tiến Ngọc Linh

Một CV portfolio hiện đại và ấn tượng được thiết kế với HTML5, CSS3 và JavaScript thuần. Portfolio này thể hiện kỹ năng lập trình và thiết kế web của tôi một cách chuyên nghiệp.

## ✨ Tính năng nổi bật

- 🎨 **Thiết kế hiện đại**: Giao diện đẹp mắt với gradient, shadow và animation mượt mà
- 📱 **Responsive hoàn hảo**: Tối ưu hóa cho mọi thiết bị từ desktop đến mobile
- 🎭 **Animation đẹp mắt**: Hiệu ứng scroll, hover và transition mượt mà
- 🚀 **Performance cao**: Sử dụng CSS thuần và JavaScript tối ưu
- 🌟 **UX/UI tốt**: Trải nghiệm người dùng thân thiện và trực quan
- 📊 **Thông tin chi tiết**: Hiển thị đầy đủ kỹ năng, dự án và kinh nghiệm

## 🛠️ Công nghệ sử dụng

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Grid, Flexbox, CSS Variables, Animations
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Inter, JetBrains Mono (Google Fonts)
- **Responsive**: Mobile-first approach
- **Performance**: Lazy loading, Intersection Observer API

## 📁 Cấu trúc dự án

```
CV/
├── index.html          # Trang chính portfolio
├── styles.css          # File CSS chính
├── script.js           # JavaScript tương tác
└── README.md           # Tài liệu dự án
```

## 🎯 Các section chính

### 1. Hero Section
- Giới thiệu cá nhân ấn tượng
- Background gradient với particle effect
- Call-to-action buttons
- Thống kê nổi bật

### 2. Skills Section
- **Frontend Development**: HTML5, CSS3, ReactJS, JavaScript
- **Backend Development**: PHP, Java, C
- **Database & Tools**: MySQL, SQL, Git
- **Soft Skills**: Làm việc nhóm, quản lý thời gian, học hỏi nhanh

### 3. Projects Section
- **BronxLuggage**: E-commerce platform (PHP, MySQL, HTML, CSS)
- **Cafe Management System**: JavaFX application (Java, MySQL)
- **Personal Portfolio**: Website giới thiệu cá nhân

### 4. Experience Section
- Timeline hiển thị kinh nghiệm và học vấn
- APTECH Education (2023 - Hiện tại)
- MD Media Company (2024)
- Đại học Công nghệ GTVT (2020 - 2024)
- Gara ô tô Vương Mạnh (2022 - 2023)

### 5. Contact Section
- Form liên hệ tương tác
- Thông tin liên hệ chi tiết
- Social media links

## 🚀 Cách sử dụng

### 1. Clone repository
```bash
git clone https://github.com/your-username/cv-portfolio.git
cd cv-portfolio
```

### 2. Mở file index.html
- Sử dụng Live Server extension trong VS Code
- Hoặc mở trực tiếp trong trình duyệt

### 3. Tùy chỉnh nội dung
- Chỉnh sửa thông tin cá nhân trong `index.html`
- Thay đổi màu sắc trong `styles.css` (CSS variables)
- Thêm/sửa animation trong `script.js`

## 🎨 Tùy chỉnh giao diện

### Thay đổi màu sắc
```css
:root {
    --primary-color: #4F46E5;      /* Màu chính */
    --secondary-color: #10B981;    /* Màu phụ */
    --accent-color: #F59E0B;       /* Màu nhấn */
    --text-primary: #1F2937;       /* Màu chữ chính */
    --bg-primary: #FFFFFF;         /* Màu nền chính */
}
```

### Thay đổi gradient
```css
--gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
--gradient-secondary: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
```

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px  
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🌟 Tính năng JavaScript

- **Smooth Scrolling**: Cuộn mượt đến các section
- **Scroll Animations**: Animation khi scroll
- **Intersection Observer**: Theo dõi element visibility
- **Form Validation**: Kiểm tra form liên hệ
- **Counter Animation**: Đếm số liệu thống kê
- **Parallax Effect**: Hiệu ứng parallax cho hero section
- **Mobile Navigation**: Menu mobile responsive

## 🎭 CSS Animations

- **Fade In**: Xuất hiện mượt mà
- **Slide Up**: Trượt lên từ dưới
- **Hover Effects**: Hiệu ứng khi hover
- **Loading Animation**: Animation loading trang
- **Particle Effect**: Hiệu ứng particle trong hero

## 📊 Performance Optimization

- **CSS Variables**: Sử dụng CSS custom properties
- **Intersection Observer**: Lazy loading animations
- **CSS Grid/Flexbox**: Layout hiệu quả
- **Minimal JavaScript**: JavaScript tối ưu
- **Optimized Images**: Hình ảnh placeholder tối ưu

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📝 Tùy chỉnh nội dung

### Thay đổi thông tin cá nhân
```html
<h1 class="hero-name">Tên của bạn</h1>
<p class="hero-role">Vị trí công việc</p>
```

### Thêm dự án mới
```html
<div class="project-card">
    <div class="project-header">
        <h3 class="project-title">Tên dự án</h3>
        <p class="project-subtitle">Mô tả ngắn</p>
    </div>
    <!-- Nội dung dự án -->
</div>
```

### Cập nhật kỹ năng
```html
<div class="skill-item" data-skill="Tên kỹ năng">
    <div class="skill-icon">
        <i class="fab fa-icon-class"></i>
    </div>
    <span class="skill-name">Tên kỹ năng</span>
    <div class="skill-level">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

## 🚀 Deployment

### GitHub Pages
1. Push code lên GitHub
2. Vào Settings > Pages
3. Chọn source branch (main/master)
4. Website sẽ được deploy tự động

### Netlify
1. Kéo thả folder dự án vào Netlify
2. Website sẽ được deploy ngay lập tức
3. Có thể kết nối với GitHub để auto-deploy

### Vercel
1. Import project từ GitHub
2. Vercel sẽ tự động build và deploy
3. Hỗ trợ custom domain

## 📈 Analytics & SEO

- **Meta tags** đầy đủ cho SEO
- **Open Graph** tags cho social media
- **Structured data** cho search engines
- **Performance metrics** tối ưu

## 🤝 Contributing

1. Fork project
2. Tạo feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

## 📄 License

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

## 📞 Liên hệ

- **Email**: Ngtienlinh01@gmail.com
- **Phone**: 0395024902
- **GitHub**: [linhNguyenTienNgoc](https://github.com/linhNguyenTienNgoc)
- **Address**: Mỹ Hưng, Thanh Oai, Hà Nội

## 🙏 Acknowledgments

- Font Awesome cho icons
- Google Fonts cho typography
- CSS Grid và Flexbox community
- Intersection Observer API
- Modern CSS features

---

**Lưu ý**: Đây là portfolio demo cho mục đích học tập và showcase. Vui lòng tùy chỉnh nội dung và thông tin cá nhân trước khi sử dụng.

⭐ **Nếu bạn thấy dự án này hữu ích, hãy cho tôi một star trên GitHub!** 