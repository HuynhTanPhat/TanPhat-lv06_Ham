># **Huỳnh Tấn Phát**
>
>###***Báo cáo học hàm***

>[1.Hàm với chương trình](#Hàm với chương trình)  
>[2.Khái niệm hàm](#Khái niệm hàm)  
>[3.Quy tắc xây dựng hàm](#Quy tắc xây dựng hàm)  
>[4.Phân loại hàm](#Phân loại hàm)  
>[5.Hàm đối với con trỏ](#Hàm đối với con trỏ)  

<a name="Hàm với chương trình">
##1.Hàm với chương trình
<li> Một chương trình C bao gồm một hoặc nhiều hàm.  
<li> Hàm `main()` là phần bắt buộc của một chương trình.  
<li> Chương trnhf bắt đàu thực hiện câu lệnh đầu tiên của hàm `main()`và cho đến khi gặp dấu `}` cuois cùng của hàm này.  

<a name="Khái niệm hàm">
##2.Khái niệm hàm  

  -Hàm là một đoạn chương trình dộc lập thực hiện trọn vẹn một công việc rồi trả về một giá trị cho chương trình đã gọi nó.  
  ```sh
  **Lưu ý**:  
  -Hàm là một đơn vị độc lập của chương trình.  
  -Không cho phép xây dựng một hàm bên trong một hàm khác.  
  ```
  
<a name="Quy tắc xây dựng hàm">
##3.Quy tắc xây dựng hàm  
  
 **Nguyên mẫu của hàm:**  
  `<kiểu dữ liệu của hàm><tên hàm(danh sách các tham số)>;`  
  -Nguyên mẫu của hàm có trong chương trình nên đặt trước hàm `main ()`.  
  **Cấu trúc của một hàm**
  ```sh
  <Kiểu trả về><tên hàm>(<ds hình thức tham số hay đối số>)
  {
     <khai báo biến cục bộ>;
     <các câu lệnh trong thân hàm>;
     [retunr<bài tập trả về giá trị hàm>];
  }
  ```
  **Chú ý**: Đối với hàm không có kiểu trả về(hoặc không có đối số) ta có thể dùng hàm kiểu `void`
  **VD:**
 ```sh
 void 
  {int i;
  for(i=0;i<10;i++) 
  putch(7);
  }
 ```
  **Cách sử dụng hàm:**  
 <tên hàm>([danh sách tham số thực])
 
<a name="Phân loại hàm">
##4.Phân loại hàm  
 
 **Phân loại theo cách sử dụng**  
 <li>Tham số hình thức: là tham số ta ghi trong nguyên mẫu hay ghi lúc khai báo.  
 <li>Tham chiếu: là tham số thực ta truyền cho hàm dưới dạng con trỏ(địa chỉ).  
 <li>Tham trị: là tham số thực ta truyền cho hàm dưới dạng biến.  
 <li>Tham số thực: là các giá trị biến mà ta ghi sau tên hàm khi gọi hàm đó đẻ thực hiện.  
 **Phân loại theo công dụng** (hai công dụng nên có các hàm sau)
 <li>Tham số vào:cung cấp giá trị cho hàm.  
 <li>Tham số ra:lưu kết qur tính toán được trong hàm.  
 <li>Tham số vừa vào vừa ra:cả hai   
 
<a name="Hàm đối với con trỏ">
##5.Hàm đối với con trỏ
 
**Hàm có đối là con trỏ**  
 <li>Đối số của hàm là con trỏ kiểu int (float,double,... ) thì tham số thực tương ứng phải là địa chỉ của biến kiểu int (float,double,... ).
<li>Khi đó địa chỉ của biến được truyền cho đối con trỏ tương ứng.  
**Khi nào sử dụng đối con trỏ:** Khi muốn bảo lưu lại kết quả tính toán được của các đối số trong hàm.  
