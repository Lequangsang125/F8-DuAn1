# F8-DuAn1
học thêm được 

cần để ý các nút hoặc màu nếu có nhiều thuộc tính chung thì tạo các theme hoặc common dùng chung

thuộc tính 
word-break: break-all; xuống dòng khi người dùng nhập quá nhiều ký tự dính liền 

muốn bo góc cho product card cần bo cả con cả cha để làm hiệu ứng hover ảnh còn tràn ra 

muốn căn phần tử ảnh png trong suốt thì dùng
calc((100vw - 1110px)/2 - 100px);

giúp cho tiêu đề ngắn lại và lược phần thừa
.line-clamp{
    display: -webkit-box;
    -webkit-line-clamp: var(--line-clamp,2);
    -webkit-box-orient: vertical;
    overflow: hidden;
}
nếu muốn 3 dòng thì ghi thêm 
--line-clamp: 3
