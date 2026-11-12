# DUT Campus Map

Bản đồ số tương tác khuôn viên Trường Đại học Bách khoa – Đại học Đà Nẵng.

## Chức năng
- Bản đồ OpenStreetMap và ảnh vệ tinh Esri
- Tìm kiếm địa điểm trong khuôn viên và geocoding Nominatim
- Các lớp tòa nhà, tiện ích
- Định vị GPS
- Tìm tuyến đi bộ qua OSRM
- Đo khoảng cách
- Giao diện responsive, chế độ sáng/tối

## Chạy local
```bash
npm install
npm run dev
npm run build
```

## Chất lượng dữ liệu
Các ghim khu A/B/C/F/H/R/S/PFIEV là vị trí tham khảo, chưa phải dữ liệu GIS chính thức của trường. Không sử dụng các điểm này để xác định phòng học cụ thể. Cần GeoJSON chính thức để nâng độ chính xác cấp tòa nhà/phòng. Website DUT thông báo dữ liệu phòng học/phòng làm việc đang trong quá trình cập nhật.

Bản đồ nền © OpenStreetMap contributors. Routing: OSRM public demo. Geocoding: Nominatim.