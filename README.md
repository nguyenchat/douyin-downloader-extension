<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">

 
</head>
<body>

  <h2>Extension - Douyin Downloader</h2>

  <h3>✅ 1. Cấu trúc thư mục extension</h3>
  <p>Tạo một thư mục, ví dụ <code>douyin-downloader-extension</code>, với các file sau:</p>
  <pre><code>douyin-downloader-extension/
│
├── manifest.json
├── content.js
├── icons/
│   └── icon128.png  (hoặc bất kỳ ảnh icon nào bạn thích)
</code></pre>

  <h3>🔐 2. Đánh giá mức độ an toàn của tiện ích</h3>
<table border="1" cellpadding="8" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: left;">
  <thead style="background-color: #f9f9f9;">
    <tr>
      <th>Mục</th>
      <th>Đánh giá</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tự động gửi dữ liệu</td>
      <td>❌ Không có</td>
    </tr>
    <tr>
      <td>Gọi đến server ngoài Douyin</td>
      <td>❌ Không có</td>
    </tr>
    <tr>
      <td>Có thể bị lạm dụng nếu bị sửa</td>
      <td>⚠️ Có thể</td>
    </tr>
    <tr>
      <td>Bản gốc (file bạn gửi) an toàn?</td>
      <td>✅ Có vẻ an toàn</td>
    </tr>
  </tbody>
</table>


  

  <h3>✅ 3. Cách cài vào Chrome</h3>
  <ul>
    <li>Mở Chrome → vào <code>chrome://extensions/</code></li>
    <li>Bật <strong>Chế độ dành cho nhà phát triển (Developer Mode)</strong></li>
    <li>Nhấn <strong>"Tải tiện ích chưa đóng gói" (Load unpacked)</strong></li>
    <li>Chọn thư mục <code>douyin-downloader-extension</code></li>
    <li>Truy cập Douyin → sẽ thấy UI được chèn vào tự động như khi dùng script gốc</li>
  </ul>

  <h3>✅ 4. Ưu điểm so với userscript:</h3>
  <ul>
    <li>Không cần cài thêm tiện ích hỗ trợ (như Tampermonkey)</li>
    <li>Không lo bị chỉnh sửa từ bên ngoài</li>
    <li>Dễ bật/tắt trong trình duyệt</li>
    <li>Có thể xuất file .zip để chia sẻ</li>
  </ul>

</body>
</html>

