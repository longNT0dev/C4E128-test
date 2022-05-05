position
    static: Mặc định của tất cả các thẻ 
    relative: Dịch chuyển khối đi x đơn vị so với vị trí ban đầu, các thẻ relative dịch chuyển về mặt thị giác   
        top/left/right/bottom : x (px) 
        z-index: Hiển thị 1 thẻ nằm ở lớp trên hay là lớp dưới
    absolute: Dịch chuyển khối đi x đơn vị so với phần tử cha hoặc góc trên bên trái của màn hình. Không còn chiếm chỗ, các thẻ khác có thể chiếm vị trí đó   
        Phần tử cha: 
            + Chứa thẻ con 
            + position: relative/absolute
        -> Ngoại lệ transform không đúng 
    fixed: Cố định 1 khối ở vị trí bất kì dựa vào top/left/right/bottom 
    sticky: Phần tử sẽ nằm ở vị trí ban đầu cho tới khi cuộn chuột chạm vào nó 


display: flex -> Chủ yếu dùng để xây dựng giao diện 
    Sử dụng flex cho thẻ cha và kết hợp với 
        justify-content: Căn theo trục chính 
        align-items: Căn theo trục phụ 
    flex-direction:
        Mặc định trục chính sẽ là trục nằm ngang và trục phụ nằm dọc  
        column -> trục chính nằm dọc còn trục phụ nằm ngang    
    flex-wrap: Xuống dòng nếu như không đủ khoảng trống trên 1 dòng  


display: grid 


line-height: Độ cao của dòng 

-> Pseudo: https://www.w3schools.com/css/css_pseudo_classes.asp
hover


overflow: Quản lí nội dung bị tràn ra khỏi 1 khối 


-> Animation trong css (hiệu ứng chuyển động) 
transition 
transform 



