# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 08
- **Họ tên:** Đào Tuấn Minh
- **Lớp:** HN-KS26-CNTT3
- **Link repository Pha2:** https://github.com/tminhk32-bit/HN-KS26-CNTT3_PromtAI_H02
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** Gemini

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt lịch khám ra JSON

**KET QUA AI**

```text
[
  {
    "ma_dich_vu": "TRAM",
    "ngay_hen": "2026-12-17",
    "nguoi_lon": 2,
    "tre_em": 1,
    "khung_gio": "chieu",
    "ghi_chu": null
  },
  {
    "ma_dich_vu": "CAOVOI",
    "ngay_hen": "2027-01-06",
    "nguoi_lon": 3,
    "tre_em": 0,
    "khung_gio": null,
    "ghi_chu": "1 người bị tiểu đường"
  },
  {
    "ma_dich_vu": "TAYTRANG",
    "ngay_hen": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "khung_gio": "sang",
    "ghi_chu": "1 người dị ứng thuốc tê"
  }
]
```

**Link trò chuyện:** https://share.gemini.google/drmfOi7HgKlh

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền người lớn: Nhóm có 6 người lớn sử dụng dịch vụ CAOVOI (350.000 đồng/người lớn).$$6 \times 350.000 = 2.100.000\text{ đồng}$$Tiền trẻ em: Có 2 trẻ em trong độ tuổi 6–12 (7 tuổi và 11 tuổi) tính 80% giá người lớn, và 1 bé 4 tuổi (dưới 6 tuổi) được miễn phí.$$2 \times (350.000 \times 80\%) + 1 \times 0 = 2 \times 280.000 + 0 = 560.000\text{ đồng}$$Tiền dịch vụ: Tổng tiền dịch vụ của người lớn và trẻ em trước giảm giá.$$2.100.000 + 560.000 = 2.660.000\text{ đồng}$$Giảm giá nhóm: Nhóm có 6 người lớn (đạt điều kiện từ 5 người lớn trở lên) nên được giảm 10% trên tiền dịch vụ.$$2.660.000 \times 10\% = 266.000\text{ đồng}$$Tiền dịch vụ sau giảm giá:$$2.660.000 - 266.000 = 2.394.000\text{ đồng}$$Phí X-quang: Có 3 người chụp X-quang, mỗi người 1 phim với đơn giá 150.000 đồng/phim (không áp dụng giảm giá).$$3 \times 150.000 = 450.000\text{ đồng}$$Tổng tiền: Cộng tiền dịch vụ sau giảm và phí chụp X-quang.$$2.394.000 + 450.000 = 2.844.000\text{ đồng}$$[RESULT: 2.844.000 đồng]
```

**Link trò chuyện:** https://share.gemini.google/9RlPFkrYjmJl

### b) Kiểm tra kết quả AI

AI đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "tre_hen",
  "so_khach": 3,
  "so_lan_hen_bi_tre": 2,
  "tom_tat": "Gia đình 3 người phải chờ hơn 1 tiếng trong cả 2 lần hẹn cạo vôi răng."
}
```

**Link trò chuyện:** https://share.gemini.google/ceWAyMagLVYo

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text

```

**Link trò chuyện:** https://share.gemini.google/xgF7yDNp1Me8
