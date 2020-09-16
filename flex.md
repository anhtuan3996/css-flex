# Flex

Flex là viết tắt của 3 thuộc tính `flex-grow` `flex-shrink` và `flex-basis`. Nó như thế này. `flex: flex-grow flex-shrink flex-basis`. Mặc định `grow(0) shrink(1) và basis(auto)`.

# Giải thích grow và shrink khi kết hợp
Giả sử ban đầu ta có container có độ rộng tối đa là 640px sau khi tính toán bao gồm padding 2 bên của container. Lúc này có 2 phần tử như ở trên có flex-basis là 300px(bằng nhau về chiều rộng).

Khi các bạn resize trình duyệt lại sao cho container còn 430px thì lúc này chúng ta sẽ mất là 640 – 430 =  210px. Ô số 1 do có flex-shrink: 1 nên nó mất 70px(chiều rộng của nó bây giờ sẽ là 300 – 70 = 230px), còn ô số 2 có flex-shrink: 2 nên sẽ mất đi 140px(chiều rộng sẽ còn 300 – 140x = 160px).

Các bạn lại resize trình duyệt tiếp cho đến khi độ rộng container xuống 340px thì chúng ta mất 640 – 340  = 300px. Ô số 1 có flex-shrink: 1 nên sẽ mất 100px(còn 200px) còn ô số 2 sẽ mất 200px(còn 100px) do có flex-shrink: 2.

Tương tự với flex-grow. Khi tăng độ rộng container lên 940px. Thì container được tăng thêm 300px(640 + 300 = 940). Ô số 1 có flex-grow: 2 nên sẽ tăng lên thêm 200px(tổng sẽ là 500px) còn ô số 2 có flex-grow: 1 nên sẽ chiếm 1/3 là 100px nên nó sẽ tăng thêm độ rộng 100px(tổng sẽ là 400px).