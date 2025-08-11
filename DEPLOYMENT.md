# 🚀 Hướng dẫn Deploy CV Portfolio

## 📋 Các bước deploy lên GitHub Pages

### 1. ✅ Đã hoàn thành
- [x] Push code lên GitHub repository
- [x] Tạo GitHub Actions workflow
- [x] Cấu hình deployment

### 2. 🔧 Kích hoạt GitHub Pages

1. **Vào GitHub repository**: https://github.com/linhNguyenTienNgoc/CV

2. **Vào Settings**:
   - Click vào tab "Settings" trong repository
   - Scroll xuống phần "Pages" trong sidebar bên trái

3. **Cấu hình GitHub Pages**:
   - **Source**: Chọn "Deploy from a branch"
   - **Branch**: Chọn "gh-pages" (sẽ được tạo tự động)
   - **Folder**: Để mặc định "/ (root)"
   - Click "Save"

4. **Chờ deployment**:
   - GitHub Actions sẽ tự động build và deploy
   - Có thể theo dõi tiến trình trong tab "Actions"

### 3. 🌐 Truy cập website

Sau khi deploy thành công, website sẽ có sẵn tại:
```
https://linhnguyentienngoc.github.io/CV/
```

### 4. 🔄 Auto-deploy

Mỗi khi bạn push code mới lên branch `main`, website sẽ tự động được cập nhật.

## 🎯 Các platform deploy khác

### Netlify (Miễn phí)
1. Vào https://netlify.com
2. Click "New site from Git"
3. Chọn GitHub và repository CV
4. Deploy settings:
   - Build command: (để trống)
   - Publish directory: `.`
5. Click "Deploy site"

### Vercel (Miễn phí)
1. Vào https://vercel.com
2. Click "New Project"
3. Import từ GitHub repository
4. Vercel sẽ tự động detect và deploy
5. Click "Deploy"

### Firebase Hosting
1. Cài đặt Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Init project: `firebase init hosting`
4. Deploy: `firebase deploy`

## 📱 Kiểm tra responsive

Sau khi deploy, kiểm tra website trên:
- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablet (iPad, Android tablet)
- ✅ Mobile (iPhone, Android phone)

## 🔧 Troubleshooting

### Nếu GitHub Pages không hoạt động:
1. Kiểm tra tab "Actions" xem có lỗi gì không
2. Đảm bảo file `index.html` ở root directory
3. Kiểm tra console trong browser developer tools

### Nếu CSS/JS không load:
1. Kiểm tra đường dẫn file trong HTML
2. Đảm bảo tất cả file đã được commit và push
3. Clear browser cache

### Nếu images không hiển thị:
1. Kiểm tra đường dẫn ảnh
2. Đảm bảo ảnh đã được upload lên repository
3. Sử dụng relative paths thay vì absolute paths

## 📊 Performance Optimization

### Trước khi deploy:
1. **Optimize images**: Nén ảnh để giảm kích thước
2. **Minify CSS/JS**: Sử dụng tools như UglifyJS, CSSNano
3. **Enable compression**: Gzip/Brotli compression
4. **Use CDN**: Cho external resources (Font Awesome, Google Fonts)

### Monitoring:
- **Google PageSpeed Insights**: Kiểm tra performance
- **GTmetrix**: Phân tích website speed
- **WebPageTest**: Test từ nhiều locations

## 🔒 Security

### HTTPS:
- GitHub Pages tự động có HTTPS
- Đảm bảo tất cả external links đều dùng HTTPS

### Content Security Policy:
Thêm vào `<head>` của HTML:
```html
<meta http-equiv="Content-Security-Policy" content="default-src 'self'; style-src 'self' 'unsafe-inline' https://fonts.googleapis.com https://cdnjs.cloudflare.com; font-src 'self' https://fonts.gstatic.com https://cdnjs.cloudflare.com; img-src 'self' data: https:; script-src 'self' 'unsafe-inline';">
```

## 📈 Analytics

### Google Analytics:
1. Tạo Google Analytics account
2. Thêm tracking code vào `<head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🎨 Custom Domain (Tùy chọn)

### Nếu có domain riêng:
1. Thêm domain vào file `CNAME`
2. Cấu hình DNS records:
   - Type: CNAME
   - Name: www (hoặc subdomain)
   - Value: `linhnguyentienngoc.github.io`
3. Trong GitHub Pages settings, thêm custom domain

## 📞 Support

Nếu gặp vấn đề, hãy:
1. Kiểm tra GitHub Actions logs
2. Xem browser console errors
3. Test locally trước khi deploy
4. Tạo issue trên GitHub repository

---

**🎉 Chúc mừng! CV portfolio của bạn đã được deploy thành công!**
