# 1. Grid

- Grid: full-width, chiếm hết chiều ngang của đối tượng cha
- Wide: chiều ngang tối đa là 1200px

# 2. Row - Hàng

- Chứa các columns, giúp các columns nằm theo chiều ngang
- Khi tổng chiều ngang columns vượt quá kích thước row, cho columns xuống hàng
- Loại bỏ khoảng trắng thừa do gutters tạo ra ở 2 phía

**Row sử dụng giá trị âm sang 2 phía trái/phải để bù trừ cho khoảng padding trái/phải của columns**

# 3. Column - Cột

- Column nghĩa là cột, được sử dụng để chứa nội dung/thành phần hiển thị trên website của bạn
- Column sử dụng padding trái/phải để tạo nên gutters - rãnh ngăn cách giữa các column trong Grid layout.
- **Column luôn luôn là con trực tiếp của Row**
- Column được sử dụng với `class = col`. Đi kèm theo đó là một số prefix

  1. `class = s-*`: Phù hợp cho màn hình smartphone (< 739px)
  2. `class = m-*`: Phù hợp cho màn hình Table (>= 740px)
  3. `class = l-*`: Phù hợp cho màn hình PC (> 1113px)

- **Trong đó:** 1. `* từ 0 tới 12`. 2. 0 được sử dụng để ẩn column 3. 1 - 12 tương ứng với độ rộng chúng ta muốn sử dụng cho column (trên cơ sở 12 columns trong Grid system)
  ![Example](https://raw.githubusercontent.com/nmhung2022/Grid-System/768479980c1b595e2dc4f222b2abdadabcec8692/3.%20Column/gridSystem.png)
