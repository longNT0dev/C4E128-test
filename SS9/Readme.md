JSON
    stringify: Chuyển object | array sang string để lưu vào localStorage 
    parse: Chuyển string trong localStorage về array | object để cập nhật
-> localStorage: Lưu data dưới dạng string 
    Ví dụ: 
        localStorage.info = JSON.stringify({
                name:"Long",
                age:26
            }) 

        let data = JSON.parse(localStorage.info)
        data.name = "Nghĩa"
        console.log(data)

        localStorage.info = JSON.stringify(data)


for...in 
for...of
        // Đối với array 
        // i là chỉ số của mảng
        // for(let i in arr) {
        //     arr[i] = arr[i] + 1
        // }
        // console.log(arr)

        // e là giá trị các phần tử trong mảng
        // for(let e of arr) {
        //    console.log(`${e} là giá trị của mảng`)
        //    Chỉ dùng để đọc giá trị 
        // }

        // Đối với object 
        // i là key của object  
        for(let i in obj) {
            console.log(i)
        }
forEach: Như vòng lặp for thông thường nhưng không return ra giá trị nào cả 

Object 
    CRUD 
        // Create
        let obj = {
            key: "value",
            key: "value",
            key: "value",
        }
        // Read 
        obj.key
        // Update 
        obj.key = newValue
        // Delete 
        delete obj.key 

document: Là 1 object được định nghĩa sẵn trên trình duyệt (lấy ra nội dung file html)


Search : method object js      