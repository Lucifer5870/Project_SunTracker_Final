1.ดาวน์โหลด ArduinoIDE จาก https://www.arduino.cc/en/Main/OldSoftwareReleases#previous
![image](https://user-images.githubusercontent.com/79622469/126730422-26269902-04f2-45e2-ab38-42ce91601ae3.png)


2. เปิด arduino




![image](https://user-images.githubusercontent.com/79622469/126730482-7db12cfc-8e3e-419c-9ddd-e52457c098de.png)


3. เมื่อเปิดโปรแกรมขึ้นมาแล้ว ให้ไปที่เมนู File -> Preferences เพื่อติดตั้งบอร์ด NodeMCU/ESP32 แบบออนไลน์




![image](https://user-images.githubusercontent.com/79622469/126730717-e581525a-9911-40da-bd33-6fcd0b7220ad.png)



4. เพิ่ม https://dl.espressif.com/dl/package_esp32_index.json ลงในช่อง Additional Boards Manager URLs ดังภาพ





![image](https://user-images.githubusercontent.com/79622469/126730784-7cf80bfe-2bc4-4da8-8501-f9069b7c4c4a.png)


5. คลิกไปที่เมนู Tools -> Board -> Board Manager



![image](https://user-images.githubusercontent.com/79622469/126730880-5a7c5ecc-52ff-4b5e-be50-e4d4d94b17c5.png)


6. พิมพ์คำว่า ESP32 ลงในช่อง และเริ่มต้นติดตั้งดังภาพ



![image](https://user-images.githubusercontent.com/79622469/126730910-fc51f2e5-4f49-49a2-87c3-eba10093a6b8.png)


7. รอจนกว่าการติดตั้งจะเสร็จ (หากเป็นการติดตั้งครั้งแรกจะใช้เวลาค่อนข้างนาน)


9. เมื่อติดตั้งเสร็จสิ้น ในหน้าต่าง Board ก็จะปรากฏประเภทของบอร์ด ESP32 ขึ้นมา ให้เลือกใช้งานได้แล้ว




![image](https://user-images.githubusercontent.com/79622469/126731004-5ae0a633-320c-491a-b893-6ea8098616ff.png)





9. การใช้งานบอร์ด ESP32 สามารถทำได้ โดยเริ่มจากเชื่อมต่อสายส่งสัญญาณเข้ากับตัวบอร์ด




11. จากนั้นเลือก Port ที่เชื่อมต่อบอร์ด ESP32



![image](https://user-images.githubusercontent.com/79622469/126731046-64c7b8b3-038c-42d3-b63f-08fc2e006cdd.png)



11. จากนั้นนำโค๊ดจากไฟล์ Firmware มาใส่แล้วทำการ Upload ลงบอร์ด
