


# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ TÀI CHÍNH CÁ NHÂN)

- **Họ tên:Nguyễn Trường Khang**
- **Lớp:CNTT3**
- **Link repository Pha2:https://github.com/nkhang19062008-cmd/NguyenTruongKhang**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):Gemini**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký hội thảo ra JSON

**KET QUA AI**

```text
[ { "ma_goi": "DT", "ngay_hoi_thao": "2026-12-20", "nguoi_lon": 2, "tre_em": 1, "hang_ve": "thuong", "ghi_chu": null }, { "ma_goi": "CB", "ngay_hoi_thao": "2027-01-10", "nguoi_lon": 3, "tre_em": 0, "hang_ve": "thuong", "ghi_chu": "một người dùng xe lăn cần lối đi riêng" }, { "ma_goi": "VIP", "ngay_hoi_thao": null, "nguoi_lon": 4, "tre_em": 0, "hang_ve": "vip", "ghi_chu": "một anh mắt kém cần ngồi bàn đầu gần màn hình chiếu" } ]
```

**Link trò chuyện:https://share.gemini.google/J7x8M79qDtu2**

## 4.3. Báo giá vé hội thảo bằng Chain-of-Thought

**KET QUA AI**

```text
**Bước 1: Tính tiền người lớn** Nhóm chọn gói DT (Gói Đầu Tư) với đơn giá 1.500.000 đồng/người lớn và có 4 người lớn:

$$4 \times 1.500.000 = 6.000.000\text{ đồng}$$

**Bước 2: Tính tiền trẻ em**

-   2 trẻ em từ 6 đến 12 tuổi (8 tuổi và 11 tuổi) tính 50% giá người lớn:
    
    $$50\% \times 1.500.000 = 750.000\text{ đồng/trẻ}$$
    
    $$2 \times 750.000 = 1.500.000\text{ đồng}$$
    
-   1 bé 4 tuổi (dưới 6 tuổi) được miễn phí:
    
    $$1 \times 0 = 0\text{ đồng}$$
    
-   Tổng tiền trẻ em:
    
    $$1.500.000 + 0 = 1.500.000\text{ đồng}$$
    

**Bước 3: Tính tiền vé (tiền người lớn + tiền trẻ em)**

$$6.000.000 + 1.500.000 = 7.500.000\text{ đồng}$$

**Bước 4: Tính giảm giá nhóm (nếu có) và tiền vé sau giảm** Nhóm có 4 người lớn (đạt điều kiện từ 4 người lớn trở lên) nên được giảm 10% trên tiền vé:

-   Số tiền được giảm:
    
    $$10\% \times 7.500.000 = 750.000\text{ đồng}$$
    
-   Tiền vé sau giảm:
    
    $$7.500.000 - 750.000 = 6.750.000\text{ đồng}$$
    

**Bước 5: Tính phụ thu sổ tay** Nhóm đặt mua thêm 2 bộ sổ tay lập kế hoạch tài chính cá nhân với giá 200.000 đồng/bộ (không được giảm giá):

$$2 \times 200.000 = 400.000\text{ đồng}$$

**Bước 6: Tính tổng tiền**

$$\text{Tổng tiền} = 6.750.000 + 400.000 = 7.150.000\text{ đồng}$$

[RESULT: 7.150.000 đồng]
```

**Link trò chuyện:https://share.gemini.google/Cahb6hh4Xwok**

### b) Kiểm tra kết quả AI

AI tính **Đúng**. Tất cả 6 bước suy luận và phép tính đều khớp với quy tắc trong bảng giá, xác nhận tổng tiền chính xác là **7.150.000 đồng**.

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_phien_bi_anh_huong": 2,
  "tom_tat": "Bị xếp ngồi dãy ghế phụ phía sau không có bàn viết trong 2 phiên học đầu."
}
```

**Link trò chuyện:https://share.gemini.google/n8CFpaI2NtZ1**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Kết quả AI phải xuất ra **bảng Markdown đủ 4 cột** (`Tiêu chí | Điểm | Minh chứng | Đề xuất sửa`
```

**Link trò chuyện:https://share.gemini.google/NipTvmyVd0iT**

