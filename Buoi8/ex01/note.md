# Flex = flexible box module

## Các thuộc tính trong nhóm flex container

- display: flex | inline-flex: Kích hoạt flex
- flex-direction: Chọn hướng cho trục chính (main axis)

* row : mặc định
* row-reverse
* column
* column-reverse

- justify-content: Căn chỉnh các item theo hướng song song với trục chính

* flex-start
* flex-end
* center
* space-between: căn đều
* space-around: lùi vào 1/2
* space-evenly: chia đều

- align-items: Căn chỉnh các item theo hướng vuông góc với trục chính, căn chỉnh theo hàng

* stretch: Mặc định full chiều cao theo container
* flex-start:
* center:
* flex-end:
* baseline

- flex-wrap: Bọc

* no-wrap : Mặc định
* wrap : Xuống dòng
* wrap-reverse : Ngược lại

- align-content: Căn chỉnh hàng cột theo hướng vuông góc với trục chính,

* stretch
* flex-start
* flex-end
* center
* space-between: căn đều
* space-around: lùi vào 1/2
* space-evenly: chia đều

- gap: Căn chỉnh khoảng cách giữa các item

## Các thuộc tính trong nhóm Flex Item

- flex-grow: Dãn đều các item
  => Số nguyên: 0 - không giãn, 1: Giãn đều'

- flex-shrink:0 Tự động giãn ra, 1 tự động co lại

- flex-basis: Tự động linh hoạt theo hướng của with hight

* Bị chặn bởi min-with và max-with, nếu max-with là 100, thì flex basis chỉ đến 100 thôi nếu 200 thì không chạy

- flex: Gộp flex-grow flex-shrink flex-basis
