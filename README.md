# ITP Gang-Run Printing Calculator — Demo

Interactive demo công cụ tính ghép bài cho ITP (In Bao bì Toàn Phát) — một phần của đề xuất triển khai SAP S/4HANA Public Cloud.

**Live demo:** https://<your-github-user>.github.io/gangrun-demo/

## Nội dung

- **Demand Pool** — nguồn đơn hàng cần ghép bài (có thể chỉnh sửa live)
- **Parameters** — khổ giấy nguyên, máy in (Mitsubishi V3000LS-5, RYOBI R752, Mitsubishi D3000LS-5), thông số màu, bù hao in
- **Allocation Engine** — tính tỷ lệ diện tích, bù hao phân bổ, tờ nguyên allocated, phế phẩm theo từng SP
- **Sheet Visualizer** — vẽ bố cục SP trên tờ in
- **SAP Integration Preview** — Parent Gang-Run Order (Custom Business Object) + Child Production Orders (SAP chuẩn) với BOM qty override theo kết quả ghép bài

## Tech stack

- React 18 UMD + Babel standalone (no build)
- Pure HTML/CSS/JS single file
- Fonts: Montserrat + JetBrains Mono
- Branding: Citek (Peacock Blue #00586F, Lime Green #A2D45E)

## Author

Citek — SAP Platinum Partner
