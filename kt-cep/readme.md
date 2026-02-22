# 📥 Hướng dẫn download
- B1. Tải file `Fix For Window.REG` ở thư mục `kt-cep` bên cạnh hoặc [Tại đây](https://github.com/kimthien128/kimthien128/blob/main/kt-cep/Fix%20For%20Windown.REG)
- B2. Truy cập vào https://github.com/kimthien128/kimthien128/releases
- B3. Tìm và tải file zip có phiên bản phát hành mới nhất, ví dụ: `kt-cep-v1.5.zip`

# 📋 Thông tin cập nhật phiên bản
### v1.5
- Refactor: Pagination for all layout
- Add zoom control
- Update suggestion layout
### v1.4
- Silent layer reading
- Fix save Guide
- Reduce errors caused by file size
### v1.3
- Fix transform mapping Layer
- Show more modal loading
- Select muti layer
- Distribute outside main group
### v1.2
- Fix lỗi chức năng thao tác với các layout
- Update sizeName khi tạo mới kích thước
- Fix lỗi lấy đường dẫn các layer
### v1.1
- Fix lỗi khi sử dụng đơn vị khác với đơn vị px
### v1.0
- Phiên bản Pre-release định hướng các chức năng chính

# 📦 Hướng Dẫn Sử Dụng Extension KT CEP
***Tip: Muốn xem rõ hình ảnh nào chỉ cần click vào hình ảnh đó*  

## 0. Fix lỗi "Không thể kết nối đến server"
*Lỗi này chỉ xảy khi khi thực hiện các chức năng cần truy cập lên Internet như: **kích hoạt bản quyền, kiểm tra cập nhật phiên bản phần mềm.***  

<img width="408" height="552" alt="image" src="https://github.com/user-attachments/assets/96a1ba16-6de0-4835-a1f3-6d8a0746ca64" />
<img width="303" height="487" alt="image" src="https://github.com/user-attachments/assets/5d7fb3e1-889b-4ef5-952f-c367f5ef6908" />
  
#### Thực hiện tạm thời tắt tường lửa để extension có thể thực hiện truy cập Internet, sau khi chức năng chạy xong bật lại tường lửa bình thường.  
  
<img width="840" height="644" alt="image" src="https://github.com/user-attachments/assets/f6aa367d-3f99-4af8-a9dc-145bf7560f1e" />  

#### Chỉ cần tắt Private network:  
  
<img width="769" height="390" alt="image" src="https://github.com/user-attachments/assets/e192ad59-3690-470f-904c-44af8656ff63" />




## 1. 🚀 Giới Thiệu
KT CEP là extension dành cho Adobe Photoshop, giúp tự động hóa các thao tác xử lý layer, layout, và quản lý dữ liệu một cách nhanh chóng, tiện lợi.
Extension được phát triển trên môi trường Photoshop CC 2019 (Cần kiểm tra khi sử dụng với các phiên bản khác).
![AppyLayout](https://github.com/user-attachments/assets/dd425483-59f0-4c55-a50f-bfab1551b13b)


## 2. 🛠️ Cài Đặt Extension
1. Tải file zip và giải nén.
2. Đóng Photoshop nếu đang mở.
3. Chạy file `Fix For Windown.REG` để đăng ký với Windows (Chỉ cần chạy 1 lần duy nhất, các bản cập nhật tiếp theo không cần chạy lại, áp dụng cho hầu hết các Extension khác trên Internet).
4. Copy toàn bộ thư mục `kt-cep` vào đường dẫn:
	- Windows x64: `C:\Program Files (x86)\Common Files\Adobe\CEP\extensions\`
5. Mở lại Photoshop.
6. Vào menu `Window > Extensions > KT CEP` để mở extension.

## 3. 🖥️ Giao Diện Chính
<img width="312" height="831" alt="image" src="https://github.com/user-attachments/assets/cb30f796-767d-42ba-9798-b20601448c81" />

## 4. ⚙️ Các Chức Năng Chính

### 4.1. 💡 Mẹo sử dụng
- Cài đặt phím F1 làm phím tắt đóng/mở extension nhanh.
![SetShortcut](https://github.com/user-attachments/assets/8436bdca-9acf-44be-b7e2-bcadaa8832ab)
  
- Phóng to/ thu nhỏ kích thước Extension phù hợp với không gian làm việc.
![MinimizeWorkspace](https://github.com/user-attachments/assets/67ee06e1-6f4b-4442-af95-997f04680198)

- Trong trường hợp gặp lỗi, hãy thử sử dụng nút "Reload" hoặc nhấn phím F1 đã cài đặt trước đó để tắt/bật lại Extension
<img width="107" height="52" alt="image" src="https://github.com/user-attachments/assets/5e3fc1b9-151e-4762-bd2d-44306b1d9571" />

### ⚙️ 4.2. Các bước bắt buộc thiết lập trước khi sử dụng
#### 4.2.1. Giới hạn group cho phép Extension thao tác
- Ví dụ mỗi file trong album thiết kế bạn đều có 3 Group: Foreground, Main và Background.
  - <img width="299" height="137" alt="image" src="https://github.com/user-attachments/assets/05a485e3-4532-4d79-b289-e141672cfb8a" />
  - Foreground: chứa trang trí tiền cảnh
  - Main: chứa layout + hình ảnh
  - Background: chứ trang trí hậu cảnh

- Việc giới hạn này giúp tránh việc xử lý toàn bộ các layer trang trí ở Foreground, Background và ngăn chặn ảnh Extension làm sai lệch thiết kế không mong muốn.
- Thao tác như sau:  
![SetupAllowGroup](https://github.com/user-attachments/assets/894a2263-8c90-4c19-9cbe-c9a08f6930ff)

- *Lưu ý: một số thao tác đơn giản vẫn cho phép thực hiện trên các group nằm ngoài phạm vi Group được giới hạn.*

#### 4.2.2. Đặt tên cho khổ giấy (bắt buộc - để mở khóa các chức năng bên dưới)
- Nếu bạn làm việc trên nhiều kích thước khổ giấy, việc đặt tên giúp hệ thống quản lý thông tin tốt hơn
- Mỗi khi mở file làm việc, Extension sẽ tự động tracking sự thay đổi kích thước file để đưa ra gợi ý phù hợp  
<img width="312" height="382" alt="image" src="https://github.com/user-attachments/assets/0aa16df0-47fd-493c-a8ca-bceda979dfcc" />

- Nếu bạn làm cùng 1 khổ giấy, nhưng sử dụng nhiều phong cách design khác nhau, bạn nên đặt tên cho phong cách template đó, nó sẽ có lợi cho việc đề xuất layout sau này.
<img width="312" height="755" alt="image" src="https://github.com/user-attachments/assets/c6a79e1f-ee41-4d14-a509-68aaf089579d" />

- Mỗi khi mở một kiểu album mới, nên sử dụng nút `Vẽ Guide` để vẽ lại các đường guide xem đã thao tác trên đúng loại album đã đặt tên hay chưa.

### ✨ 4.3. Chức năng chính 
#### 4.3.1. Thao tác với Layer
<img width="305" height="234" alt="image" src="https://github.com/user-attachments/assets/2f682142-63a6-44db-8027-cc20f4495463" />

- Đây là mô tả các chức năng theo thứ tự từ trái qua phải, từ trên xuống dưới:

- Guide:
  - **Save Guides**: Lưu lại các đường guide hiện tại.  
  *Điều kiện*: Đã mở file và chọn khổ giấy/sản phẩm.

  - **Draw Guides**: Vẽ lại các đường guide đã lưu.  
  *Điều kiện*: Đã lưu guide cho khổ giấy/sản phẩm đang chọn.  
![Guide](https://github.com/user-attachments/assets/f2ecf06d-b9b2-4f82-bcbe-e51a95b2077b)

- Group:
  - **Group Left Page**: Gom nhóm các layer thuộc trang trái.  
  *Điều kiện*: Layer phần lớn nằm bên trái.

  - **Ungroup**: Bỏ gom nhóm "Left Group" và "Right Group".  
  *Điều kiện*: File có tồn tại các group này. Các group này sẽ được tạo tự động khi dùng chức năng "Group Left Page" và "Group Right Page".

  - **Group Right Page**: Gom nhóm các layer thuộc trang phải.  
  *Điều kiện*: Layer phần lớn nằm bên phải.  
![Ungroup](https://github.com/user-attachments/assets/4670e576-a566-412e-adc8-a5491366b0fa)

- Mask:
  - **Expand Mask to Fit**: Mở rộng mask để vừa với đối tượng.  
  *Điều kiện*: Layer có mask, nằm trong Group Main được cấu hình.  
   Có thể gom nhóm tất cả các layer cần mở rộng mask vào chung group:
![ExpandMaskToFix](https://github.com/user-attachments/assets/0f0cfe90-24ae-45dd-b297-d54b8508c77e)

   Hoặc có thể nhấn Ctrl và chọn nhiều group:
![ExpandMaskToFixSelectMuti](https://github.com/user-attachments/assets/f69f8e3e-d071-4bc8-a199-1e3fafbf43e4)

  - **Equalize Mask Size**: Điều chỉnh các mask có kích thước bằng nhau.  
  *Điều kiện*: Có nhiều group chứa mask, nằm trong Group Main được cấu hình.
   Các group ở layer dưới sẽ tham chiếu theo Mask của group nằm ở trên cùng nhất trong danh sách các group được chọn trong bảng Layer.
   Trong ví dụ bên dưới, `Group 2` sẽ là group gốc được tham chiếu: 
![EquaMask](https://github.com/user-attachments/assets/c1341897-4d04-4493-b6bf-d737d977db5e)

- Align:
  - **Align Center Left**: Căn giữa các layer trên trang trái.  
  *Điều kiện*: Đã từng lưu guides xác định vùng.
  - **Align Center Full Page**: Căn giữa các layer trên toàn trang.  
  *Điều kiện*: Đã từng lưu guides xác định vùng. Áp dụng khi làm album trang đơn.
  - **Align Center Right**: Căn giữa các layer trên trang phải.  
  *Điều kiện*: Đã từng lưu guides xác định vùng.  
![Align](https://github.com/user-attachments/assets/d82205e4-bd88-4c81-a26b-45000a06a568)

- Distribute Spacing:
  - **Distribute Vertical Spacing**: Phân bố khoảng cách dọc giữa các layer theo giá trị nhập (mm).  
  *Điều kiện*: Chọn nhiều Layer hoặc group, nằm trong Group Main được cấu hình.
  - **Distribute Horizontal Spacing**: Phân bố khoảng cách ngang giữa các layer theo giá trị nhập (mm).  
  *Điều kiện*: Chọn nhiều Layer hoặc group, nằm trong Group Main được cấu hình.  
![Distribute](https://github.com/user-attachments/assets/f9af5b74-4a35-4c99-91da-13a5f878afa8)

- Inset 50%
  - **Inset Top 50%**: Thu nhỏ layer vào 50% từ cạnh trên.  
  *Điều kiện*: Đã có guides xác định cạnh trên.
  - **Inset Right 50%**: Thu nhỏ layer vào 50% từ cạnh phải.  
  *Điều kiện*: Đã có guides xác định cạnh phải.
  - **Inset Left 50%**: Thu nhỏ layer vào 50% từ cạnh trái.  
  *Điều kiện*: Đã có guides xác định cạnh trái.
  - **Inset Bottom 50%**: Thu nhỏ layer vào 50% từ cạnh dưới.  
  *Điều kiện*: Đã có guides xác định cạnh dưới.  
![Inset](https://github.com/user-attachments/assets/9c77db18-15e9-40cd-bc09-ce079b7b37e4)

#### Combo chuỗi thao tác thường dùng
![Combo](https://github.com/user-attachments/assets/c550cf0b-a2ea-4a12-b4b5-2863fcf5c3c3)


#### 4.3.2. Quản Lý Layout
<img width="307" height="317" alt="image" src="https://github.com/user-attachments/assets/efaf3f44-a538-4fba-a0c3-36701e7b9526" />

1. **Save Layout**: Lưu trữ thông tin của các layer mask hiện tại.  
2. **Delete Layout**: Chọn 1 layout từ khu vực "Layout đề xuất" và xóa.  
3. **Preview Layout**: Chọn 1 layout từ khu vực "Layout đề xuất" và xem trước bố cục trước khi áp dụng.  
4. **Apply Layout**: Chọn vào Group chứa Layout mẫu và áp dụng cho các layer.

![Layout](https://github.com/user-attachments/assets/24c013b3-4b0b-4312-a5df-5c692c610110)

5. **Pagination**: Xem layout qua các trang, layout sắp xếp theo thứ tự **số lượng mask tăng dần**
6. **Zoom control**: Phóng to/ thu nhỏ hình ảnh thumbnail layout
7. **Filter**: Đề xuất những layout phù hợp với file đang được mở bằng từ toàn bộ layout đã của lưu thuộc khổ giấy hiện tại
   
![LayoutControl](https://github.com/user-attachments/assets/4dd817aa-6a5a-4b12-ba04-45853eeb9663)


#### 4.3.3. Quản Lý Dữ Liệu
- **Backup Database**: Backup dữ liệu lưu trữ. Để tiết kiệm bộ nhớ, KT CEP chỉ thực hiện backup với file dữ liệu JSON, không lưu trữ hình ảnh thumbnail của Layout.
- **Reset Database**: Xóa trống toàn bộ dữ liệu database.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/44ab42c2-a812-47ea-b1bc-13732324b2a5" />


## 🎁 Bonus: Chơi với mèo trong khi làm việc
![Neko](https://github.com/user-attachments/assets/25ff5296-ec80-4d99-82cc-d1c30ed4247c)

Nguồn: Mèo Neko
