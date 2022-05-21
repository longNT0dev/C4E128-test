Xem lại buổi 9 + 10 

localStorage 

API
mockAPI: Tạo url chứa dữ liệu


fetch(url) -> Trả về 1 Promise chứa dữ liệu 
-> Để đọc được dữ liệu cần sử dụng từ khóa then 

        // Lấy thẻ container được tạo trong html 
        let container = document.getElementById("container");
        fetch('https://60bc32b7b8ab37001759ee4d.mockapi.io/blogs')
            .then((result) => result.json())
            .then((data) => {
                // DOM để dữ liệu lên trình duyệt 
                for (let el of data) {
                    // Tạo 1 item html cần thêm và truyền dữ liệu thông qua ${}
                    let html = `
                        <div class="item">
                            <h1>${el.title}</h1>
                            <p>${el.content}</p>
                        </div>
                    `
                    container.innerHTML += html

                }
            })

asynchonous/synchonous: 
-> https://blog.bitsrc.io/understanding-asynchronous-javascript-the-event-loop-74cd408419ff

Cơ chế xử lí bất đồng bộ: callback, Promise async/await 


git init/git clone -> Chỉ làm 1 lần duy nhất để nói cho máy tính biết sau này push lên đâu 

git pull = git fetch + git merge 
-> Lấy code mới nhất trên github về máy rồi mới code

// push code 
git add .
git commit -m "message"
git push 

-> Đẩy lên github khi chắc chắn k có lỗi 


Tiếp tục 
