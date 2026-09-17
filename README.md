<div align="center">

# Board Phát Triển Tự Thiết Kế Tương Thích Arduino

*Thiết kế và biên soạn tài liệu bởi* [**Đỗ Bảo Đạt**](https://github.com/Datnewlevel)

[![Altium Designer](https://img.shields.io/badge/Thi%E1%BA%BFt%20k%E1%BA%BF-Altium%20Designer-A5915F?style=flat-square)](#)
[![Base](https://img.shields.io/badge/T%C6%B0%C6%A1ng%20th%C3%ADch%20v%E1%BB%9Bi-Arduino%20Uno%20R3-00979D?style=flat-square)](#)

</div>

<br>

## Tổng quan

Một dự án cá nhân nhằm thiết kế board phát triển tương thích Arduino — phiên bản
mang dấu ấn riêng của Arduino Uno R3 với một vài cải tiến có chủ đích.

Thay vì tích hợp chip giao tiếp trên board, thiết kế này sử dụng một module
USB-to-UART rời dựa trên **FT232RL**, giúp board gọn nhẹ hơn và phần cứng giao
tiếp có thể thay thế linh hoạt.

## Cải tiến so với Arduino Uno R3

| Thay đổi | Chi tiết |
| --- | --- |
| **Bổ sung chân nguồn** | Thêm hàng header cho 5V và 3.3V, giúp kết nối ngoại vi và module dễ dàng hơn mà không phải đấu nối tiếp chồng lên các đường nguồn có sẵn |
| **Layout tùy biến** | Vị trí linh kiện và đường viền board được thiết kế lại theo phong cách riêng và tối ưu cho các trường hợp sử dụng cụ thể |

## Phần mềm thiết kế

Cả sơ đồ nguyên lý và layout PCB đều được thiết kế trên **Altium Designer**.

## Hình ảnh dự án

**Sơ đồ nguyên lý**

![Sơ đồ nguyên lý](Schematic.png)

**Layout PCB**

![Layout PCB](PCB.png)

**Board hoàn thiện**

![Board hoàn thiện](Circuit_board.jpg)

**Module giao tiếp USB-to-UART**

![Module USB to UART](Module_usb_to_uart.jpg)

**Sản phẩm cuối**

![Hình ảnh sản phẩm](Hinh_anh_san_pham.jpg)

## Kiểm thử board

Các bài test ngoại vi cơ bản được chạy trên board hoàn thiện để xác nhận board
hoạt động đúng.

**Cảm biến nhiệt độ (DHT11)**

| Test 1 | Test 2 |
| --- | --- |
| ![Test nhiệt độ 1](test_temperature_1.jpg) | ![Test nhiệt độ 2](test_temperature_2.jpg) |

**Màn hình OLED (0.96")**

![Test màn hình OLED](test_oled_moniter.jpg)

**Cảm biến siêu âm (SR04)**

![Test SR04](test_sr04.jpg)

---

<div align="center">
<sub>Thiết kế và tài liệu © <a href="https://github.com/Datnewlevel">Đỗ Bảo Đạt</a>. Được chia sẻ tại đây như một phần công việc phần cứng của CLB UTT UAV.</sub>
</div>
