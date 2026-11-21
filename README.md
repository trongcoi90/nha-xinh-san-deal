# Web Nhà Xinh Săn Deal — nhaxinhsandeal.pages.dev

Web nội dung ngách nhà cửa: bài tổng hợp theo nhu cầu + link affiliate Shopee (ID 17384790294).
Đích đến cho pin Pinterest (pin bài viết) và SEO Google.

## Cấu trúc
- `index.html` — trang chủ: 4 bài viết + 11 món đang giảm giá
- `bai-viet/*.html` — bài viết tĩnh (mỗi bài: title/meta/OG riêng để pin + Google đọc được)
- `style.css` — CSS chung
- `images/` — ảnh sản phẩm (ảnh gốc từ listing Shopee, không gắn giá vào ảnh)

## Quy tắc quảng cáo (user dặn 22/11/2026)
- TỐI ĐA 2 vị trí quảng cáo trên toàn web, KHÔNG popunder, KHÔNG quảng cáo nổi/dính.
- Vị trí 1: cuối trang chủ (`#ad-home` trong index.html).
- Vị trí 2: giữa bài viết (`#ad-article` trong mỗi bài).
- Mã Monetag dán vào div `.ad-slot` khi có; slot trống tự ẩn (CSS `.ad-slot:empty`).
- ⏳ CHƯA đăng ký web trên Monetag — cần đăng ký site mới trên Monetag để lấy mã zone.

## Quy tắc nội dung
- Chỉ đăng món đã kiểm chứng giá + đánh giá trên Shopee; ghi rõ ngày kiểm chứng dưới mỗi món.
- Giá sau voucher ghi rõ là "giá sau voucher"; giá voucher hết hạn thì đổi sang giá niêm yết (xem 22/11: Downy 253.404đ → 313.000đ, Dnee 272.800đ → 310.000đ, đồng hồ 615.120đ → từ 699.000đ, kệ giày 84.000đ → từ 99.000đ).
- Mọi link mua đều là an_redir ID 17384790294, đã kiểm chứng về đúng sản phẩm.
- Mỗi bài có ghi chú link affiliate. Không ghi Mall cho shop không phải Mall (kệ giày HPS).

## Cập nhật web
1. Thêm bài mới: copy 1 file trong `bai-viet/`, đổi nội dung + ảnh, thêm thẻ bài vào `index.html`.
2. Commit qua GitHub: repo `trongcoi90/nha-xinh-san-deal`, dùng Add file → Upload files (tải file hoàn chỉnh lên thay file cũ).
3. Cloudflare Pages tự deploy lại từ repo. Chờ ~2 phút rồi kiểm tra trang live.

## Deploy lần đầu (22/11/2026)
- Repo GitHub: trongcoi90/nha-xinh-san-deal
- Cloudflare Pages project: nhaxinhsandeal → https://nhaxinhsandeal.pages.dev
