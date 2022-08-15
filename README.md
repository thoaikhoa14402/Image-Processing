#Image-Processing
perform some basic processing functions:
1. Change the brightness.
2. Change the contrast.
3. Flip the image (horizontally / vertically)
4. Convert from RGB to grayscale.
5. Blending 2 gray images of the same size.
6. Blur an image.
7. Crop an image into Circle.
8. Crop an image into Ellipse.
-------------------------------------------------------
Nhắc lại: Mỗi điểm ảnh có thể là một giá trị (ảnh xám) hoặc một vector (ảnh màu).

Trong đồ án này, bạn được yêu cầu thực hiện các chức năng xử lý ảnh cơ bản sau:
    
1. Thay đổi độ sáng cho ảnh (1 điểm)

![img](https://i.imgur.com/XIaBAIv.jpg)

2. Thay đổi độ tương phản (1 điểm)

![img](https://i.imgur.com/4uxIHJD.jpg)

3. Lật ảnh (ngang - dọc) (2 điểm)

![img](https://i.imgur.com/VKjvVdc.jpg)

4. Chuyển đổi ảnh RGB thành ảnh xám (2 điểm)

![img](https://i.imgur.com/qJw14wS.jpg)

Tham khảo tại [đây](https://www.tutorialspoint.com/dip/grayscale_to_rgb_conversion.htm)

5. Chồng 2 ảnh cùng kích thước (1 điểm): chỉ làm trên ảnh xám

![img](https://i.imgur.com/no2NH1k.jpg)

6. Làm mờ ảnh (2 điểm)

![img](https://i.imgur.com/daY9Mnd.jpg)

Tham khảo tại [đây](https://en.wikipedia.org/wiki/Kernel_(image_processing)), phần Box blur hoặc Gaussian blur 3 $\times$ 3

7. Viết hàm main xử lý (1 điểm) với các yêu cầu sau:

- Cho phép người dùng nhập vào tên tập tin ảnh mỗi khi hàm main được thực thi.
- Cho phép người dùng lựa chọn chức năng xử lý ảnh (từ 1 đến 6, đối với chức năng 4 cho phép lựa chọn giữa lật ngang hoặc lật dọc). Lựa chọn 0 cho phép thực hiện tất cả chức năng với tên file đầu ra tương ứng với từng chức năng. Ví dụ:
    - Đầu vào: `cat.png`
    - Chức năng: Làm mờ
    - Đầu ra: `cat_blur.png`
