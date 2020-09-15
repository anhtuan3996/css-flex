# Align Items

Ngược lại với thuộc tính justify-content thì mặc định align-items canh các phần tử theo chiều dọc thay vì chiều ngang như justify-content. Tuy nhiên nếu đổi flex-direction sang column thì align-items sẽ canh theo chiều ngang.

Trường hợp đầu tiên khi làm việc với flex-direction: row(mặc định). Các phần tử sẽ được canh theo chiều dọc. Trong align-items có 5 giá trị đó là `flex-start`, `flex-end`, `center`, `stretch(default)`, `baseline(typography)`


Mặc định trong align-items là `stretch`, nếu các phần tử các bạn set height: auto thì nó sẽ cao full hết container chứa nó, nhưng nếu các bạn set height cố định thì nó sẽ đè lên thuộc tính stretch này và tất nhiên nó sẽ không cao full mà chỉ lấy giá trị height mà bạn set.

# Align-self

Thuộc tính  này tương tự với thuộc tính align-items ở trên nhưng khác ở chỗ là áp dụng riêng lẻ cho các phần tử mà bạn muốn thay đổi giá trị của nó.

Giả sử bạn có các phần tử đều là align-items: flex-start(mặc định) nhưng bạn muốn thẻ div màu vàng ở giữa chứ không phải ở trên thì lúc này các bạn chỉ cần css cho thẻ div màu vàng align-self: center là được