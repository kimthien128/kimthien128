# Hướng dẫn download
### v1.2
- Truy cập vào https://github.com/kimthien128/kimthien128/releases
- Tải file: `kt-cep-v1.2.zip`

# Hướng dẫn cài đặt
- Tải file zip, giải nén, bỏ vào  
`Windows x64: C:/Program Files (x86)/Common Files/Adobe/CEP/extensions/`
- Chạy file `Fix For Windown.REG` để đăng ký với windown (Chỉ cần chạy 1 lần duy nhất, các bản cập nhật tiếp theo không cần chạy lại)

# Thông tin cập nhật phiên bản
### v1.2
- Fix lỗi chức năng thao tác với các layout
- Update sizeName khi tạo mới kích thước
- Fix lỗi lấy đường dẫn các layer
### v1.1
- Fix lỗi khi sử dụng đơn vị khác với đơn vị px
### v1.0
- Phiên bản Pre-release định hướng các chức năng chính

# 📦 Hướng Dẫn Sử Dụng Extension KT CEP

## 1. 🚀 Giới Thiệu
KT CEP là extension dành cho Adobe Photoshop, giúp tự động hóa các thao tác xử lý layer, layout, và quản lý dữ liệu một cách nhanh chóng, tiện lợi.
Extension được phát triển trên môi trường Photoshop CC 2019 (Cần kiểm tra khi sử dụng với các phiên bản khác).
![AppyLayout](https://github.com/user-attachments/assets/dd425483-59f0-4c55-a50f-bfab1551b13b)


## 2. 🛠️ Cài Đặt Extension
1. Đóng Photoshop nếu đang mở.
2. Chạy file `Fix For Windown.REG` để đăng ký với Windows (nếu chưa thực hiện lần nào).
3. Copy toàn bộ thư mục `kt-cep` vào đường dẫn:
	- `C:\Program Files (x86)\Common Files\Adobe\CEP\extensions\`
4. Mở lại Photoshop.
5. Vào menu `Window > Extensions (Legacy) > KT CEP` để mở extension.

## 3. 🖥️ Giao Diện Chính
<img width="312" height="862" alt="image" src="https://github.com/user-attachments/assets/84230c87-b917-4435-86ed-ee739a8648f4" />

## 4. ⚙️ Các Chức Năng Chính

### 4.1. 💡 Mẹo
- Sử dụng phím F1 làm phím tắt đóng/mở extension nhanh.
<img width="352" height="858" alt="image" src="https://github.com/user-attachments/assets/d04458d1-3711-4442-8814-36c5ee147948" />
<img width="848" height="701" alt="image" src="https://github.com/user-attachments/assets/f8135c15-0ed5-491d-9188-b53e09c903f6" />
  
- Phóng to/ thu nhỏ kích thước Extension phù hợp với không gian làm việc.
<img width="353" height="978" alt="image" src="https://github.com/user-attachments/assets/865e0863-2369-4db9-bf00-a3fe94413a10" />

- Trong trường hợp gặp lỗi, hãy thử sử dụng nút "Reload" hoặc tắt/bật lại Extension
<img width="107" height="52" alt="image" src="https://github.com/user-attachments/assets/5e3fc1b9-151e-4762-bd2d-44306b1d9571" />

### 4.2. Các bước bắt buộc thiết lập trước khi sử dụng
#### 4.2.1. Giới hạn group cho phép Extension thao tác
- Ví dụ mỗi file trong album thiết kế bạn đều có 3 Group: Foreground, Main và Background.
  - <img width="299" height="137" alt="image" src="https://github.com/user-attachments/assets/05a485e3-4532-4d79-b289-e141672cfb8a" />
  - Foreground: chứa trang trí tiền cảnh
  - Main: chứa layout + hình ảnh
  - Background: chứ trang trí hậu cảnh

- Việc giới hạn này giúp tránh việc xử lý toàn bộ các layer trang trí ở Foreground, Background và ngăn chặn ảnh Extension làm sai lệch thiết kế không mong muốn.
- Thao tác như sau:  
<img width="312" height="620" alt="image" src="https://github.com/user-attachments/assets/58ad91a3-6ec2-499c-b811-169987d1324d" />

- Lưu ý: một số thao tác đơn giản vẫn cho phép thực hiện trên các group nằm ngoài phạm vi Group được giới hạn.

#### 4.2.2. Đặt tên cho khổ giấy (bắt buộc - để mở khóa các chức năng bên dưới)
- Nếu bạn làm việc trên nhiều kích thước khổ giấy, việc đặt tên giúp hệ thống quản lý thông tin tốt hơn
- Mỗi khi mở file làm việc, Extension sẽ tự động tracking sự thay đổi kích thước file để đưa ra gợi ý phù hợp  
<img width="312" height="382" alt="image" src="https://github.com/user-attachments/assets/0aa16df0-47fd-493c-a8ca-bceda979dfcc" />

- Nếu bạn làm cùng 1 khổ giấy, nhưng sử dụng nhiều phong cách design khác nhau, bạn nên đặt tên cho phong cách template đó, nó sẽ có lợi cho việc đề xuất layout sau này.
<img width="312" height="755" alt="image" src="https://github.com/user-attachments/assets/c6a79e1f-ee41-4d14-a509-68aaf089579d" />

### 4.3. Chức năng chính 
#### 4.3.1. Thao tác với Layer
<img width="305" height="234" alt="image" src="https://github.com/user-attachments/assets/2f682142-63a6-44db-8027-cc20f4495463" />

- Theo thứ tự từ trái qua phải, từ trên xuống dưới:

  - **Save Guides**: Lưu lại các đường guide hiện tại.  
  *Điều kiện*: Đã mở file và chọn khổ giấy/sản phẩm.

  - **Draw Guides**: Vẽ lại các đường guide đã lưu.  
  *Điều kiện*: Đã lưu guide cho khổ giấy/sản phẩm đang chọn.

  - **Group Left Page**: Gom nhóm các layer thuộc trang trái.  
  *Điều kiện*: Layer nằm hoàn toàn bên trái (không được đè lên vị trí chính giữa trang dù là 1px).

  - **Ungroup**: Bỏ gom nhóm "Left Group" và "Right Group".  
  *Điều kiện*: File có tồn tại các group này. Các group này sẽ được tạo tự động khi dùng chức năng "Group Left Page" và "Group Right Page".

  - **Group Right Page**: Gom nhóm các layer thuộc trang phải.  
  *Điều kiện*: Layer nằm hoàn toàn bên phải (không được đè lên vị trí chính trang giữa dù là 1px).

  - **Expand Mask to Fit**: Mở rộng mask để vừa với đối tượng.  
  *Điều kiện*: Layer có mask, nằm trong Group Main được cấu hình.

  - **Equalize Mask Size**: Điều chỉnh các mask có kích thước bằng nhau.  
  *Điều kiện*: Có nhiều group chứa mask, nằm trong Group Main được cấu hình.

  - **Align Center Left**: Căn giữa các layer trên trang trái.  
  *Điều kiện*: Đã từng lưu guides xác định vùng.

  - **Align Center Full Page**: Căn giữa các layer trên toàn trang.  
  *Điều kiện*: Đã từng lưu guides xác định vùng. Áp dụng khi làm album trang đơn.

  - **Align Center Right**: Căn giữa các layer trên trang phải.  
  *Điều kiện*: Đã từng lưu guides xác định vùng.

  - **Distribute Vertical Spacing**: Phân bố khoảng cách dọc giữa các layer theo giá trị nhập (mm).  
  *Điều kiện*: Chọn nhiều Layer hoặc group, nằm trong Group Main được cấu hình.

  - **Distribute Horizontal Spacing**: Phân bố khoảng cách ngang giữa các layer theo giá trị nhập (mm).  
  *Điều kiện*: Chọn nhiều Layer hoặc group, nằm trong Group Main được cấu hình.

  - **Inset Top 50%**: Thu nhỏ layer vào 50% từ cạnh trên.  
  *Điều kiện*: Đã có guides xác định cạnh trên.

  - **Inset Right 50%**: Thu nhỏ layer vào 50% từ cạnh phải.  
  *Điều kiện*: Đã có guides xác định cạnh phải.

  - **Inset Left 50%**: Thu nhỏ layer vào 50% từ cạnh trái.  
  *Điều kiện*: Đã có guides xác định cạnh trái.

  - **Inset Bottom 50%**: Thu nhỏ layer vào 50% từ cạnh dưới.  
  *Điều kiện*: Đã có guides xác định cạnh dưới.


#### 4.3.2. Quản Lý Layout
<img width="313" height="262" alt="image" src="https://github.com/user-attachments/assets/35ac9eed-3010-41b8-83e9-ca564b241b85" />

1. **Save Layout**: Lưu trữ thông tin của các layer mask hiện tại.  
2. **Delete Layout**: Chọn 1 layout từ khu vực "Layout đề xuất" và xóa.  
3. **Preview Layout**: Chọn 1 layout từ khu vực "Layout đề xuất" và xem trước bố cục trước khi áp dụng.  
4. **Apply Layout**: Chọn vào Group chứa Layout mẫu và áp dụng cho các layer.  
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/2537a6b0-8487-4d4a-aae0-ca343d73d506" />


#### 4.3.3. Quản Lý Dữ Liệu
- **Backup Database**: Backup dữ liệu lưu trữ. Để tiết kiệm bộ nhớ, KT CEP chỉ thực hiện backup với file dữ liệu JSON, không lưu trữ hình ảnh thumbnail của Layout.
- **Reset Database**: Xóa trống toàn bộ dữ liệu database.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/44ab42c2-a812-47ea-b1bc-13732324b2a5" />

#### 4.3.4. Toast Notification
- Hiển thị thông báo nhanh khi thao tác thành công/thất bại.
<img width="315" height="303" alt="image" src="https://github.com/user-attachments/assets/ae399f6e-4b71-49a5-8bde-346872b753a8" />

# Bonus: Giải tỏa stress với "Mèo đuổi chuột" (Mèo Neko)
![Neko](https://github.com/user-attachments/assets/25ff5296-ec80-4d99-82cc-d1c30ed4247c)

