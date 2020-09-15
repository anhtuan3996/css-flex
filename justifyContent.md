# Justify-content

Thuộc tính này cho phép các bạn căn chỉnh các phần tử theo chiều ngang hoặc chiều dọc tùy thuộc vào thuộc tính `flex-direction`

Trong justify-content có 5 giá trị đó là `flex-start`, `flex-end`, `center`, `space-between` và `space-around`. Khi sử dụng thuộc tính này thì nên xem thêm đó là chúng ta đang làm với flex-direction theo row(chiều ngang) hay column(chiều dọc).


Trường hợp đầu tiên là khi làm với `flex-direction: row`. Lúc này những phần tử(items) sẽ được căn chỉnh theo chiều ngang.
    `flex-start`: Giá trị mặc định trong thuộc tính justify-content khi sử dụng giá trị này thì những phần tử sẽ nằm sát lề bên trái của container
    `flex-end`: Sử dụng giá trị này thì các phần tử sẽ nằm sát lề bên phải, đừng nhầm với cái `row-reverse`
    `center`: Giá trị này làm cho các phần tử nằm giữa container
    `space-between`: Giá trị này tạo khoảng cách giữa các phần tử bằng nhau, phần tử đầu tiên sát lề bên trái, phần tử cuối cùng sát lề bên phải, container sẽ tự động canh khoảng cách giữa các phần tử với nhau sao cho luôn bằng nhau.
    `space-around`: Giá trị này thì na ná space-between nhưng khác ở chỗ là có khoảng cách 2 bên giữa các phần tử và những khoảng cách này bằng nhau.
Trường hợp thu 2 là khi làm với `flex-direction: column`. Lúc này những phần tử(items) sẽ được căn chỉnh theo chiều doc.