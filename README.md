 <img width="1536" height="1024" alt="49f0d657-70c8-454e-9361-ffaa4aafad2a" src="https://github.com/user-attachments/assets/4f35b284-d4db-4b2b-ae5b-f511d0dd757f" />

#  PROJECT : LIIGHT CONTROLLER SYSTEM USING ARDUINO  
 📘 Giới thiệu dự án
  
  Dự án được thiết kế nhằm mô phỏng một hệ thống điều khiển đèn tự động trong gia đình:

✔ Tự động bật đèn khi trời tối (dựa vào LDR)

✔ Tự động tắt đèn khi đủ sáng

✔ Hiển thị mức ánh sáng (%) và trạng thái cửa/đèn trên LCD

✔ Điều khiển đèn bằng nút nhấn

✔ Sử dụng transistor C1815 để điều khiển bóng đèn

✔ Có động cơ (DC Motor) mô phỏng cửa cuốn/ cửa tự động

 
 🔧 Linh kiện sử dụng

| Linh kiện                      | Chức năng                    |
| ------------------------------ | ---------------------------- |
| Arduino UNO                    | Bộ điều khiển trung tâm      |
| LDR (Light Dependent Resistor) | Đo độ sáng môi trường        |
| R1 = 10kΩ                      | Tạo cầu phân áp với LDR      |
| VR1 = 10kΩ                     | Chỉnh độ tương phản LCD      |
| LCD 16×2 (LM016L)              | Hiển thị thông tin           |
| Transistor C1815               | Khuếch đại & bật tắt đèn     |
| R2 = 1kΩ                       | Hạn dòng cho Base transistor |
| R3 = 1kΩ                       | Hạn dòng LCD                 |
| R4, R5 = 4kΩ                   | Dùng cho nút nhấn            |
| DC Motor                       | Mô phỏng cửa                 |
| Nút nhấn (NUT, CTHT)           | Điều khiển thủ công          |
| Nguồn 5V                       | Cấp điện cho hệ thống        |

 
 🔌 Sơ đồ kết nối

<img width="3011" height="1275" alt="image" src="https://github.com/user-attachments/assets/80aaea21-e566-463b-b36d-94d5718d680c" />


✨ Chức năng của hệ thống

🔹 1. Chế độ tự động (AUTO)

  Khi ánh sáng môi trường < ngưỡng (VD: 30%) → Đèn tự động bật

  Khi ánh sáng môi trường > ngưỡng → Đèn tự động tắt

  LCD hiển thị:

     ANH SANG: 23%
    CUA: DONG  DEN: BAT

🔹 2. Điều khiển bằng nút nhấn

  Nút NUT → bật/tắt đèn thủ công

  Nút CTHT → điều khiển cửa/động cơ

🔹 3. Hiển thị lên LCD

   Mức ánh sáng (%)

   Trạng thái cửa (ĐÓNG / MỞ)

  Trạng thái đèn (BẬT / TẮT)


  🎥 Demo Video: https://www.youtube.com/watch?v=ch9dTBppeMw 
