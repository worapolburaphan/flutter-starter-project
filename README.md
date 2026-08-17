# Flutter Starter Project (Flutter Starter App)

โปรเจกต์นี้เริ่มต้นจาก `flutter_mysecond_project` และได้ถูกเปลี่ยนชื่อและปรับแต่งโครงสร้างใหม่เพื่อใช้เป็นโปรเจกต์เริ่มต้น (Starter Project)

## สิ่งที่ได้ทำในวันนี้ (อัปเดตล่าสุด)

1. **เปลี่ยนชื่อโปรเจกต์ (Project Rename)**:
   - เปลี่ยนชื่อแพ็กเกจ (Package Name) และค่าคอนฟิกต่างๆ จาก `flutter_mysecond_project` เป็น `flutter_starter_project` ทั้งในไฟล์ `pubspec.yaml`, `AndroidManifest.xml`, `build.gradle.kts`, `Info.plist`, และการตั้งค่าบนเว็บ
   - อัปเดตโครงสร้างโฟลเดอร์ของ Kotlin ในฝั่ง Android ให้ตรงกับชื่อแพ็กเกจใหม่
   
2. **เปลี่ยนชื่อแอปพลิเคชัน (App Name)**:
   - เปลี่ยนชื่อแอปที่แสดงบนหน้าจอโฮมเพจของ iOS และ Android เป็น **"Flutter Starter App"**

3. **อัปเดตโค้ดภายในแอป (`lib/main.dart`)**:
   - ปรับแก้ไข `title` ของ `MaterialApp` และ `MyHomePage` ให้ตรงกับชื่อแอปใหม่

4. **การจัดการ Git (Version Control)**:
   - รัน `git init` และเชื่อมต่อกับ Remote Repository (`worapolburaphan/flutter-starter-project`) บน GitHub
   - ดัน (Push) โค้ดทั้งหมดขึ้นไปยัง branch `main` ได้สำเร็จ

## การเริ่มต้นใช้งาน (Getting Started)

โค้ดนี้เหมาะสำหรับใช้เป็นโครงร่างเริ่มต้นในการพัฒนาแอปพลิเคชันด้วย Flutter

ข้อมูลเพิ่มเติมสำหรับผู้เริ่มต้น:
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

หรือสามารถเข้าไปดู [online documentation](https://docs.flutter.dev/) เพื่อศึกษาข้อมูลเพิ่มเติม
