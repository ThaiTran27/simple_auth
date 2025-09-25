# Demo Basic Auth
## Cài đặt
1. Mở command Prompt
2. npm install
3. node basic_auth.js
![Ảnh minh họa](./public/img/A4.png)
## Test với POSTMAN 
4. Get: http://localhost:3000
5. Tab Auth → chọn Basic Auth → nhập username/password
![Ảnh minh họa](./public/img/A3.png)
6. GET: http://localhost:3000/secure
![alt](./public/img/image%20copy.png)
![alt](./public/img/image%20copy%202.png)
![alt](./public/img/image.png)
7. GET: http://localhost:3000/public
![alt](./public/img/image%20copy%203.png)
# Demo Cookie Auth
## Cài đặt
1. Mở command Prompt
2. npm install
3. node cookie_auth.js
![Ảnh minh họa](./public/img/A2.png)
## Test với POSTMAN 
4. POST: http://localhost:3001/login
5. Body -> raw -> nhập { "username": "admin", "password": "12345" } => thông báo thành công: Logged in!
![Ảnh minh họa](./public/img/A1.png)
6. Get: http://localhost:3001/profile
![alt](./public/img/image%20copy%204.png)
7. POST: http://localhost:3001/logout
![alt](./public/img/image%20copy%205.png)
## Test với MONGODB
8. Kết nối với localhost:27017
9. Chọn cookieApp -> cookies
10. hiện kết quả:
![Ảnh minh họa](./public/img/Screenshot%202025-09-25%20191016.png)
