Các bước thực hiện so sánh sql server và mongoDB bằng Jmeter:

- Tải file apache-jmeter-5.5 và giải nén
- Mở ứng dụng Apache jmeter , chọn Open  Mở file Test PlanMSSQL.jmx(Khi thực hiện test SQL Server) hoặc Test PlanMongo.jmx(Khi thực hiện test MongoDB)

![image](https://user-images.githubusercontent.com/118526250/205438034-26f0d811-fce8-41c1-8ccf-79ac8a758c5a.png)


- Chọn số user thực hiện test ở phần theard group

![image](https://user-images.githubusercontent.com/118526250/205438056-367ee851-f467-4d06-b7a1-baabe3ff3a07.png)



- Cấu hình kết nối ở JDBC Connection Configuration, Các thao tác truy vấn, update ở JDBC Request

![image](https://user-images.githubusercontent.com/118526250/205438062-47265613-fb60-4d3d-bdef-d70fed87dc16.png)

![image](https://user-images.githubusercontent.com/118526250/205438066-a6270480-49af-4188-b7d9-d65f20ca87ad.png)




- Chọn Start và xem thống kê ở Summary Report

![image](https://user-images.githubusercontent.com/118526250/205438090-51cc82d3-e86c-4bb0-95a0-b0ea86cb1183.png)





