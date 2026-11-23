# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ TÀI CHÍNH CÁ NHÂN)

- **Họ tên:** Đoàn Tuấn Long
- **Lớp:** CNTT3
- **Link repository Pha2:** https://github.com/doantuanlong0711208-bit/tester.git
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** Gemini

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký hội thảo ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "DT",
    "ngay_hoi_thao": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "hang_ve": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "CB",
    "ngay_hoi_thao": "2027-01-10",
    "nguoi_lon": 3,
    "tre_em": 0,
    "hang_ve": "thuong",
    "ghi_chu": "một người dùng xe lăn cần lối đi riêng"
  },
  {
    "ma_goi": "VIP",
    "ngay_hoi_thao": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "hang_ve": "vip",
    "ghi_chu": "một anh mắt kém cần ngồi bàn đầu gần màn hình chiếu"
  }
]
```

**Link trò chuyện:** https://share.gemini.google/ACtGbNsO4l1F

## 4.3. Báo giá vé hội thảo bằng Chain-of-Thought

**KET QUA AI**

```text

1. **Tiền người lớn:**
Nhóm gồm 4 người lớn đăng ký gói DT (Gói Đầu Tư) với đơn giá 1.500.000 đồng/người lớn:

$$4 \times 1.500.000 = 6.000.000 \text{ đồng}$$


2. **Tiền trẻ em:**
Nhóm có 2 trẻ em trong độ tuổi từ 6 đến 12 (8 tuổi và 11 tuổi) được tính 50% giá vé người lớn, và 1 bé 4 tuổi (dưới 6 tuổi) được miễn phí:

$$2 \times (1.500.000 \times 50\%) + 1 \times 0 = 2 \times 750.000 + 0 = 1.500.000 \text{ đồng}$$


3. **Tiền vé:**
Tổng tiền vé trước giảm giá bao gồm tiền vé người lớn và tiền vé trẻ em:

$$6.000.000 + 1.500.000 = 7.500.000 \text{ đồng}$$


4. **Giảm giá nhóm:**
Vì nhóm có đủ 4 người lớn trở lên nên được giảm 10% trên tổng tiền vé:

$$7.500.000 \times 10\% = 750.000 \text{ đồng}$$



Tiền vé sau giảm giá là:

$$7.500.000 - 750.000 = 6.750.000 \text{ đồng}$$


5. **Phụ thu sổ tay:**
Nhóm đặt mua thêm 2 bộ sổ tay lập kế hoạch tài chính cá nhân với giá 200.000 đồng/bộ (không áp dụng giảm giá):

$$2 \times 200.000 = 400.000 \text{ đồng}$$


6. **Tổng tiền:**
Tổng số tiền thanh toán cuối cùng bằng tiền vé sau giảm cộng với tiền phụ thu:

$$6.750.000 + 400.000 = 7.150.000 \text{ đồng}$$



[RESULT: 7.150.000 đồng]
```

**Link trò chuyện:** https://share.gemini.google/DGfwFBQOWK37

### b) Kiểm tra kết quả AI

Đúng
## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
"loai_su_co": "sai_khu_vuc",
"so_khach": 2,
"so_phien_bi_anh_huong": 2,
"tom_tat": "Khách mua vé gói DT nhưng bị xếp ngồi ghế phụ không có bàn viết trong 2 phiên đầu."
}
```

**Link trò chuyện:** https://share.gemini.google/LbBwA3MzQliW

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
4.0/10
```

**Link trò chuyện:** https://share.gemini.google/IqBKKWUoB2oI
