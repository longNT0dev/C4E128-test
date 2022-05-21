function 
    regular
    arrow 
-> Khác nhau về từ khóa this 
    IIEF

        // Khai báo hàm
        
        // regular function 
        function nameFunction(params1,params2) {
            // Xử lí 1 công việc gì đó 
        }

        // arrow function 
        // const nameFunction = (params1,params2) => {
        //     // Xử lí 1 công việc gì đó 
        // }
        
        // //  immediate function (IIEF): Khai báo và sử dụng ngay lập tức 
        // (function nameFunction(params1,params2) {

        // })()


        // anonymous function - callback -> hàm chỉ thực thi khi công việc trước đã hoàn thành  
        // Tham số của hàm A là hàm B thì B gọi là callback 
        // function A(B) {
        //     B là callback nếu B là 1 function 
        // } 

        // Lời gọi hàm để sử dụng 
        nameFunction()

* Nâng cao 
// asynchonous: Đưa các tác vụ nặng xử lí ở 1 nơi khác, không block người dùng 
setTimeout: Chỉ chạy 1 lần duy nhất sau 1 khoảng thời gian  
setInterval: Chạy lại sau mỗi khoảng thời gian 

// synchonous: Đòng bộ  
-> Nếu 2 công việc liên quan tới nhau thì phải đưa code bất đồng bộ về đồng bộ 
-> Các cơ chế xử lí bất dồng bộ: callback, Promise, async/await 


this trong object 
    bind: Cho 1 object khác mượn hàm  
    call 
    apply 

    let user = {
        name: "Long",
        logger: function() {
            console.log(this.name)
        }
        }

    let admin = {
        name:"admin"
    }
    
    user.logger.bind(admin)()
    

