Các cách khai báo event và xử lí

    Cách 1: 
        container.onChange = () => {
            // TODO 1 
        }

        container.onChange = () => {
            // TODO 2 
        }
        // ->Ghi đè: Chỉ thực hiện TODO 2 

    Cách 2: "Khuyên dùng"
        container.addEventListener("change",() => {
            // TODO 1 
        })
        
        container.addEventListener("change",() => {
            // TODO 2 
        })
        // -> Chạy cả 2 
        container.innerHTML = NavBar({name:'Long'})

addEventListener("event", function handleEvent() {

})
addEventListener("event", () => {
    // Code xử lí 
})

event: https://www.w3schools.com/jsref/dom_obj_event.asp
    change: Thường áp dụng cho thẻ input -> realtime 
    click: Tất cả phần tử có thể bấm 
    submit: Thường áp dụng cho thẻ form 
        preventDefault: Ngăn trang web reload và làm mất dữ liệu người dùng nhập 
    keyup || keypress: Thường dùng khi bấm detect ra người dùng bấm enter 
    
event.target: Tham chiếu tới phần tử mà sự kiện đang diễn ra trên nó 
    value
    elements 


destructuring: Phân tách các giá trị của 1 mảng hoặc 1 object và gán cho biến 

eval: Hàm để thực hiện tính toán (bài toán calculator)







