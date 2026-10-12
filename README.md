# MindAR Face Tracking & Blendshape Project

โปรเจกต์เว็บแอปพลิเคชัน Augmented Reality (AR) สำหรับติดตามใบหน้า (Face Tracking) และขยับ Blendshape ของโมเดล 3D แบบเรียลไทม์ผ่านเว็บเบราว์เซอร์ โดยใช้ MindAR และ Three.js

## คุณสมบัติหลัก (Features)
* ติดตามใบหน้าและดึงค่า Blendshape (เช่น การกะพริบตา, การอ้าปาก)
* แสดงผลโมเดล 3D (.glb) บนใบหน้าผู้ใช้งาน
* ทำงานผ่านเว็บเบราว์เซอร์โดยไม่ต้องติดตั้งแอปพลิเคชันเพิ่มเติม

## เทคโนโลยีที่ใช้ (Tech Stack)
* [MindAR](https://hiukim.github.io/mind-ar-js-doc/) (Face Tracking)
* [Three.js](https://threejs.org/) (3D Rendering)
* HTML5 / JavaScript (ES Modules)

## วิธีการใช้งาน (Getting Started)
1. โคลนหรือดาวน์โหลดโปรเจกต์นี้ลงในเครื่องของคุณ
2. วางไฟล์โมเดล 3D ของคุณ (นามสกุล `.glb`) ไว้ในโฟลเดอร์โปรเจกต์
3. เปิดไฟล์ `index.html` ผ่าน **Local Server** (แนะนำให้ใช้ส่วนขยาย **Live Server** ใน VS Code)
4. อนุญาตให้เว็บไซต์เข้าถึงกล้องหน้าของคุณ
