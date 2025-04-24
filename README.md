# Databrick-Data-Engineering-Cert-Demo
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <title>Hướng dẫn làm việc với Databricks và GitHub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 40px;
      background-color: #f9f9f9;
      color: #333;
    }
    h1 {
      color: #2c3e50;
      font-size: 28px;
    }
    h2 {
      color: #2980b9;
      border-bottom: 2px solid #ecf0f1;
      padding-bottom: 6px;
    }
    ul {
      margin-left: 20px;
    }
    li {
      margin-bottom: 6px;
    }
    .icon {
      margin-right: 6px;
    }
    code {
      background: #eee;
      padding: 2px 4px;
      border-radius: 4px;
    }
    section {
      margin-bottom: 40px;
    }
  </style>
</head>
<body>

  <h1>📘 Dự án Databricks – Hướng dẫn làm việc với GitHub</h1>
  <p>Dự án này sử dụng Databricks Repos để đồng bộ với GitHub nhằm đảm bảo quy trình làm việc nhóm hiện đại và hiệu quả.</p>

  <section>
    <h2>1️⃣ Clone repository GitHub vào Databricks</h2>
    <ul>
      <li>Vào <code>Repos</code> trong Databricks UI</li>
      <li>Nhấn <code>Add Repo</code> và nhập URL GitHub repo</li>
      <li>Chọn xác thực bằng <code>Personal Access Token (PAT)</code></li>
      <li>Click <code>Create</code> để clone về workspace</li>
    </ul>
  </section>

  <section>
    <h2>🌿 2️⃣ Tạo nhánh mới để làm việc</h2>
    <ul>
      <li>Nhấn <code>Cmd/Ctrl + Shift + P</code> → chọn <code>Git: Create Branch</code></li>
      <li>Đặt tên nhánh theo quy ước: <code>feature/tên-task</code></li>
      <li>Bắt đầu làm việc trong nhánh vừa tạo</li>
    </ul>
  </section>

  <section>
    <h2>🛠️ 3️⃣ Làm việc trên nhánh</h2>
    <ul>
      <li>Sửa hoặc thêm file notebook trực tiếp trong repo</li>
      <li>Đảm bảo commit thay đổi trước khi rời khỏi nhánh</li>
    </ul>
  </section>

  <section>
    <h2>🔄 4️⃣ Pull code mới từ GitHub (nếu có thay đổi)</h2>
    <ul>
      <li>Trên sidebar Git → nhấn <code>Pull</code> để lấy bản mới nhất</li>
      <li>Luôn đảm bảo đang ở đúng nhánh trước khi pull</li>
    </ul>
  </section>

  <section>
    <h2>💻 5️⃣ Một số lệnh Git hỗ trợ (nếu dùng CLI)</h2>
    <ul>
      <li><code>git status</code></li>
      <li><code>git checkout -b feature/ten-task</code></li>
      <li><code>git add .</code></li>
      <li><code>git commit -m "feat: mô tả task"</code></li>
      <li><code>git push origin feature/ten-task</code></li>
    </ul>
  </section>

  <section>
    <h2>🤝 6️⃣ Quy tắc làm việc nhóm</h2>
    <ul>
      <li>Mỗi task → 1 nhánh riêng</li>
      <li>Không commit trực tiếp vào <code>main</code></li>
      <li>Hoàn tất công việc thì mở Pull Request (PR)</li>
    </ul>
  </section>

  <section>
    <h2>📬 Liên hệ / Hỗ trợ</h2>
    <ul>
      <li>DevOps: <code>devops@yourcompany.com</code></li>
      <li>Admin GitHub: <code>admin@yourorg.com</code></li>
    </ul>
  </section>

</body>
</html>

