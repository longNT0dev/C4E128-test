// DOM 
document: Nút gốc của cây  


// Các hàm (phương thức của document) giúp tìm kiếm các thẻ
// Trường phái 1 
document.getElementById
-> Trả về 1 thẻ duy nhất, đầu tiên mà nó gặp 
document.getElementsByClassName
-> Trả về 1 mảng chứa các thẻ có cùng class
document.getElementsByTagName
-> Trả về 1 mảng chứa các thẻ có cùng tên thẻ 


// Trường phái 2 
document.querySelector
-> Trả về 1 thẻ duy nhất
document.querySelectorAll
-> Trả về tất cả các thẻ 


// Thuộc tính
innerText: Chỉ lấy ra text
innerHTML: Lấy ra cả thẻ bên trong
classList
    add: Thêm 1 class vào thẻ mong muốn 
    contains: Kiểm tra 1 thẻ có chứa class nào đó không 

// Phương thức 
appendChild(): thêm 1 thẻ vào bên trong 
createElement(`Tên thẻ muốn tạo`): Tạo 1 thẻ html 
removeChild(): Xóa 1 thẻ bên trong 
insertAdjacentHTML(position,text): Chèn ở 1 số vị trí đặc biệt 
    // before begin
    <div id="container" class="class1 class2 class3">
        //after begin

        //before end
    </div>
    // after end


new Date
    getHours
    getDate
    getDay
    getMinute
    getSecond

onLoad: Sự kiện trong js 

trim: 1 phương thức của string dùng để xóa khoảng trống ở 2 đầu 


// BTVN 
1. Tìm hiểu về các event trong js 
2. Cách thức xử lí khi các event xảy ra 