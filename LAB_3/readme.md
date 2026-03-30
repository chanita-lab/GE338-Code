## 1. ออกแบบ Training Strategy
พื้นที่ศึกษาที่เลือก คือ บึงบอระเพ็ด จังหวัดนครสววรค์
### 1.1 แบ่งประเภทที่ดินเป็น 5 Class ได้แก่ 
- Water (น้ำ)
- Wetland Vegetation (พื้นที่ชุ่มน้ำ)
- Agriculture (เกษตรกรรม)
- Forest (ป่า)
- Urban (พื้นที่เมือง)
### 1.2 วิธีการสร้าง Training Samples
ใช้ข้อมูลจาก Dynamic World เป็นแหล่งอ้างอิง (Reference Dataset) : มีความสะดวกและทันสมัย มีหลาย class ใช้ train model ได้ง่าย เหมาะใช้เป็น reference เบื้องต้น แต่ไม่ใช่ ground truth จริง 100% ความแม่นยำจึงขึ้นอยู่กับลักษณะพื้นที่
### 1.3 การแบ่ง Train / Validation
