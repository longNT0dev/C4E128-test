Vòng lặp 
for  
while
-> Kiểm tra điều kiện trước rồi mới chạy 
do...while: Chạy câu lệnh trước rồi mới kiểm tra điều kiện  


array: Kiểu dữ liệu 
length: thuộc tính -> lấy độ dài của mảng hoặc của string  

***Các thao tác với array  
*Create
  let arr = [ 5,1,7,8,"name","age", [3,4] ]  
*Read
  Chỉ số của 1 mảng bắt đầu từ 0    
  arr[i] trong đó i là chỉ số muốn lấy (i chạy từ 0 -> arr.length - 1)
*Update
  splice: Có thể sử dụng để thay thế 
  push: Đẩy 1 hoặc nhiều giá trị vào cuối mảng  
  pop: Xóa 1 giá trị ở cuối mảng  
  shift: Xóa 1 giá trị ở đầu mảng 
  unshift: Thêm 1 hoặc nhiều giá trị ở đầu mảng 
  reverse: Đảo ngược mảng 
  sort: Sắp xếp mảng theo string 
  join: Nối các phần tử của mảng với 1 hoặc nhiều kí tự bất kì
  includes: Kiểm tra 1 phần tử có trong mảng không 
  concat: Gộp 2 mảng với nhau 

  // Một số phương thức không làm thay đổi mảng ban đầu 
      map 
      slice 
      filter

   Tham trị: Lưu trữ giá trị 
      
   Tham chiếu: Trỏ tới địa chỉ ô nhớ trên máy tính. Nên khi giá trị tại địa chỉ ô nhớ thay đổi 
   -> thay đổi hết mọi biến tham chiếu tới đó

  Thay đổi giá trị tại 1 vị trí bất kì 
   arr[i] = newValue 
*Delete  
slice: Xóa phần tử và gán vào 1 mảng mới 
splice
        // Thêm 
        a.splice(2,0,"hello","hi")
         console.log("Thêm " + a)
        // Xóa 
        a.splice(2,3,"Added")
        console.log("Xóa " + a)













