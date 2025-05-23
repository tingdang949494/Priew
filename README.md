# Priew

## ระบบ AGI สำหรับ Cyber Security
ระบบนี้มีจุดประสงค์เพื่อช่วยงานด้านวิเคราะห์ ป้องกัน และตอบสนองต่อภัยคุกคามทางไซเบอร์แบบอัตโนมัติ

### โครงสร้างระดับสูง
1. **Data Ingestion Layer**: รวบรวมข้อมูลจากแหล่งต่าง ๆ เช่น logs, network traffic, endpoint telemetry
2. **Data Processing & Storage**: ประมวลผลและจัดเก็บข้อมูลในรูปแบบที่พร้อมใช้งาน
3. **Threat Detection & Analysis**: ใช้ Machine Learning และ rule-based engine เพื่อตรวจจับพฤติกรรมต้องสงสัย
4. **AGI Reasoning Engine**: วิเคราะห์เชิงลึก วางแผนตอบสนอง และตัดสินใจโดยอิงจากความรู้และบริบท
5. **Response Automation**: ดำเนินการตอบสนอง เช่น block IP, isolate host, แจ้งเตือน
6. **Feedback & Continuous Learning**: นำผลลัพธ์จากการตอบสนองกลับมาเรียนรู้ปรับปรุงโมเดล
7. **Monitoring & Management Interface**: ให้ผู้ดูแลสามารถติดตามและปรับแต่งนโยบายได้

### โครงสร้างโปรเจกต์ปัจจุบัน
โปรเจกต์ถูกแบ่งออกเป็นโมดูลต่าง ๆ ตามขั้นตอนการทำงานของระบบ ได้แก่:
- `data_ingestion`
- `data_processing`
- `threat_detection`
- `reasoning_engine`
- `response_automation`
- `feedback`
- `monitoring`

มีโฟลเดอร์ `tests` สำหรับเก็บชุดทดสอบ
