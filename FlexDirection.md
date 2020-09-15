# Flex direction

Như tên gọi của nó là hướng(trục), thì trong flexbox có 2 trục chính đó là trục X và trục Y giống như biểu đồ toán học đó các bạn. Lưu ý là flexbox chỉ hiển thị theo 1 trong 2 hướng thôi nha, chứ không hiển thị 1 lần 2 hướng như CSS Grid được.


Mặc định thì những items trong flexbox được sắp xếp theo trục X và từ trái qua phải

Trong flex-direction có 4 giá trị bao gồm: row, row-reverse, column và column reverse.

flex-direction: `row` là giá trị mặc định trong flex-direction các items sẽ được sắp xếp theo chiều ngang(trục X) và hiển thị từ trái sang phải.

flex-direction: `row-reverse` cũng giống như thuộc tính flex-direction: row nhưng những items sẽ được hiển thị từ phải qua trái

flex-direction: column các items được sắp xếp chiều dọc(trục Y) và hiển thị từ trên xuống dưới


flex-direction: column-reverse cũng giống với thuộc tính flex-direction: column là các items được sắp xếp chiều dọc(trục Y) nhưng khác ở chỗ là các items hiển thị từ dưới lên trên