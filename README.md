Demo Basic Auth
## Cài đặt
1. Mở command Prompt
2. npm install
3. node basic_auth.js
![Ảnh minh họa](./public/img/A4.png)
## Test với POSTMAN 
4. Get: http://localhost:3000
5. Tab Auth → chọn Basic Auth → nhập username/password
![Ảnh minh họa](./public/img/A3.png)

Demo Cookie Auth
## Cài đặt
1. Mở command Prompt
2. npm install
3. node cookie_auth.js
![Ảnh minh họa](./public/img/A2.png)
## Test với POSTMAN 
4. POST: http://localhost:3001/login
5. Body -> raw -> nhập { "username": "admin", "password": "12345" } => thông báo thành công: Logged in!
![Ảnh minh họa](./public/img/A1.png)
## Test với MONGODB
6. Kết nối với localhost:27017
7. Chọn cookieApp -> cookies
8. hiện kết quả:
{
  "_id": {
    "$oid": "68d52dd85242d39c5af5d69a"
  },
  "cookie_token": "befc0638-dec2-463a-9ab0-d3c963a4d144",
  "userId": "1",
  "userRole": "adsys",
  "createdAt": {
    "$date": "2025-09-25T11:56:08.925Z"
  },
  "__v": 0
}
![Ảnh minh họa](./public/img/Screenshot%202025-09-25%20191016.png)
