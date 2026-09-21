# bt1SS2_IT103B

# bt1SS13_IT103B

# Bài tập sửa lỗi tính cước GrabRide

## Mô tả
Sửa lỗi tính cước lũy tiến trong chương trình GrabRide.

## Lỗi
Code cũ tính toàn bộ quãng đường với giá 4.500 VNĐ/km,
khiến 2 km đầu tiên bị tính tiền hai lần.

## Công thức đúng

2 km đầu:
12.000 VNĐ

Từ km thứ 3:
(distanceInKm - 2) * 4.500

## Kết quả
Với chuyến đi 4 km và mưa lớn:

12.000 + (4 - 2) * 4.500 = 21.000

21.000 * 1.2 = 25.200 VNĐ
