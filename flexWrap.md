# Flex Wrap 

Cho phép các items tự động xuống hàng hoặc vẫn luôn nằm trên cùng một hàng khi kích thước container thay đổi

Flex-wrap có 3 giá trị đó là wrap, nowrap và wrap-reverse.

Mặc định là `nowrap` nên các bạn không cần phải set. Khi chúng ta resize trình duyệt lại nếu các bạn sử dụng thuộc tính `flex-wrap: nowrap` thì các items sẽ tự động co lại cho chớ không có rớt xuống hàng, điều này dễ làm cho content bên trong(nếu có) bị ép lại có thể gây xấu giao diện.


`flex-wrap: wrap` ngược lại so với `flex-wrap: nowrap` khi kích thước container thay đổi và tổng chiều rộng các items cộng lại lớn hơn chiều rộng của container bọc ngoài thì nó sẽ rớt xuống.

`flex-wrap: wrap-reverse` cũng tương tự như `flex-wrap: wrap` nhưng nó ngược lại thay vì item rớt xuống thì nó rớt lên.