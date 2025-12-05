# Báo Cáo Đánh Giá

Website đánh giá nhân viên được xây dựng bằng HTML, CSS và JavaScript thuần.

## 🌟 Tính năng

- ✅ 13 trường đánh giá chi tiết
- 💾 Lưu trữ dữ liệu với localStorage
- 📱 Thiết kế responsive, hoạt động tốt trên mọi thiết bị
- 🎨 Giao diện hiện đại với gradient màu tím
- 🔄 Tải và xóa dữ liệu dễ dàng
- 📊 Hiển thị dữ liệu dưới dạng JSON

## 🚀 Triển khai trên GitHub Pages

### Bước 1: Kích hoạt GitHub Pages

1. Vào repository trên GitHub
2. Chọn **Settings** > **Pages**
3. Trong phần **Source**, chọn branch `main` (hoặc branch bạn muốn deploy)
4. Nhấn **Save**

### Bước 2: Truy cập website

Sau khi kích hoạt, website sẽ có sẵn tại:
```
https://son-gaf.github.io/baocao/
```

## 📋 Các trường dữ liệu

Website bao gồm các trường sau:

1. **Khả năng thích ứng** (adaptability_note)
2. **Chất lượng công việc** (quality_note)
3. **Tinh thần trách nhiệm** (responsibility_note)
4. **Kỹ năng giao tiếp** (communication_note)
5. **Khả năng lãnh đạo** (leadership_note)
6. **Kỹ năng tài liệu hóa** (documentation_note)
7. **Kỹ năng thương lượng** (negotiation_note)
8. **Khả năng tiếng Anh** (english_note)
9. **Tóm tắt** (summary)
10. **Kế hoạch** (plan)
11. **Kết quả** (result)
12. **Mong muốn** (desire)
13. **Đồng nghiệp ưa thích** (preferredCoworkers)

## 🛠️ Phát triển local

```bash
# Clone repository
git clone https://github.com/son-gaf/baocao.git
cd baocao

# Chạy server local
python3 -m http.server 8000

# Truy cập http://localhost:8000
```

## 📝 Cách sử dụng

1. Điền thông tin vào các trường đánh giá
2. Nhấn nút **"💾 Lưu dữ liệu"** để lưu
3. Dữ liệu sẽ được hiển thị dưới dạng JSON
4. Sử dụng **"📂 Tải dữ liệu"** để tải lại dữ liệu đã lưu
5. Sử dụng **"🗑️ Xóa form"** để xóa toàn bộ dữ liệu

## 🔒 Lưu trữ dữ liệu

Dữ liệu được lưu trữ trong localStorage của trình duyệt, không gửi lên server. Dữ liệu sẽ được giữ lại ngay cả khi đóng và mở lại trình duyệt.