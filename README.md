👤 ผู้จัดทำ (Author)
# Data-Warehousing-Week-11---Mini-Project-
กลุ่มอุตสาหรรมที่อยู่ Safe Sight ในรายวิชา Business Idea Creation
นาย มัทธิว ขำดี 67160365

🛡️ Workplace Safety Analytics & Business ROI Simulation Dashboard
แดชบอร์ดวิเคราะห์สถิติอุบัติเหตุจากการทำงาน (Occupational Health & Safety) เชิงลึก มุ่งเน้นการวิเคราะห์หาสาเหตุรากเหง้า (Root Cause Analysis) นำเสนอโซลูชันนวัตกรรม AI/IoT และจำลองแบบจำลองมูลค่าตอบแทนทางการเงิน (ROI & Cost Savings Simulation) เพื่อสนับสนุนการตัดสินใจระดับผู้บริหาร

📌 ภาพรวมโปรเจกต์ (Project Overview)

องค์กรชั้นนำจำเป็นต้องปรับเปลี่ยนการจัดการความปลอดภัยจากการ "ตั้งรับ" (Reactive) มาเป็น "เชิงรุกและทำนายผล" (Proactive & Predictive) โปรเจกต์นี้ถูกออกแบบขึ้นเพื่อตอบโจทย์ 3 ด้านหลัก:
  Identify Critical Risks: ระบุกลุ่มความเสี่ยงวิกฤตและกลุ่มผู้ปฏิบัติงานที่มีอัตราเกิดอุบัติเหตุสูงสุด (ผู้รับเหมาคิดเป็น 57.9% ของเคสทั้งหมด)
  Prescriptive Solutions: เสนอแนวทางแก้ไขด้วยนวัตกรรม AI และ IoT CCTV ตัดการทำงานเครื่องจักร
  Financial ROI Simulation: คำนวณผลตอบแทนการลงทุนแบบ Interactive ให้ผู้บริหารทดลองปรับเป้าหมายการลดอุบัติเหตุ (% Target Reduction) เพื่อดูมูลค่าเงินที่ประหยัดได้ (Estimated Cost Savings) และ % ROI

🚀 ฟีเจอร์เด่นบน แดชบอร์ด (Key Features)
1. Interactive ROI & Savings Simulator
  Dynamic What-If Slicer: ให้ผู้บริหารปรับแถบสไลเดอร์เป้าหมาย % การลดอุบัติเหตุได้แบบ Real-time
  Dynamic KPI Cards: คำนวณมูลค่าเงินประหยัด ($\text{Estimated Cost Savings}$), จำนวนเคสที่ลดลง ($\text{Incidents Reduced}$), และอัตราผลตอบแทนการลงทุน ($\text{ROI \%}$) โดยอัตโนมัติ

2. Before vs. After Visual Analysis
   Clustered Bar Chart: เปรียบเทียบจำนวนอุบัติเหตุก่อนและหลังนำโซลูชัน AI/IoT มาใช้ แยกตามหมวดความเสี่ยงวิกฤต (Pressed, Manual Tools, Chemical substances, etc.)

3. Prescriptive Solution Mapping & Actionable Strategy
   ตารางแผนผังโซลูชันธุรกิจ: จับคู่ปัญหาหลัก (Root Cause) $\rightarrow$ โซลูชัน AI/IoT $\rightarrow$ ผลลัพธ์เชิงธุรกิจที่คาดหวัง
   ตารางแผนงานจัดการความเสี่ยงวิกฤต: สรุปมาตรการป้องกันแก้ไขเชิงลึกแยกตามประเภทความเสี่ยง (Critical Risk Matrix)

📊 ตัวอย่างตัวเลขและข้อสรุปสำคัญ (Key Insights)
  อุบัติเหตุทั้งหมด (Total Incidents): 425 เคส
  กลุ่มความเสี่ยงสูงสุด (Top Contributor): ผู้รับเหมาเกิดเหตุสูงถึง 246 เคส (57.9%) และ Near Miss Escalation 109 เคส
  ความเสี่ยงทางกายภาพที่สำคัญ (Critical Risks):
    Pressed (อุบัติเหตุถูกกดทับ): 24 เคส
    Manual Tools (เครื่องมือช่าง): 20 เคส
    Chemical substances (สารเคมี): 17 เคส

💡 โซลูชันเชิงกลยุทธ์ที่นำเสนอ (Proposed Solutions)
  หมวดปัญหา (Root Cause)

โซลูชันนวัตกรรม (Business Idea)

ผลลัพธ์เชิงธุรกิจ (Expected Impact)

ผู้รับเหมาเกิดเหตุสูงสุด (57.9%)

<img width="872" height="267" alt="image" src="https://github.com/user-attachments/assets/ba981cb2-4543-49ee-a1d0-ad2350d18590" />

🛠️ เทคโนโลยีที่ใช้ (Tech Stack & Tools)

  Power BI Desktop: การออกแบบ Visual, Dashboard Layout และ Data Storytelling
  DAX (Data Analysis Expressions): สำหรับคำนวณค่าน้ำหนักอุบัติเหตุ, Cost Savings แบบ Dynamic และ What-If Parameter
  Power Query: การทำ Data Cleansing และ Transformation
  Data Modeling: สถาปัตยกรรมข้อมูลแบบ Star Schema

📂 โครงสร้าง Repository (Repository Structure)

├── 📁 data/
│   └── safety_incidents_dataset.csv     # ชุดข้อมูลอุบัติเหตุและความเสี่ยง
├── 📁 pbix/
│   └── Safety_Analytics_ROI_Sim.pbix    # ไฟล์ Power BI Dashboard
├── 📁 screenshots/
│   └── dashboard_preview.png             # ภาพตัวอย่างแดชบอร์ด
├── README.md                            # เอกสารอธิบายโปรเจกต์
└── LICENSE                              # สิทธิ์การใช้งาน

🎯 วิธีนำไปใช้งาน (How to Use)

  Clone หรือ Download Repository นี้ลงเครื่องคอมพิวเตอร์ของคุณ:
    git clone https://github.com/your-username/workplace-safety-roi-dashboard.git
  ดาวน์โหลดโปรแกรม Power BI Desktop (หากยังไม่มี)
  เปิดไฟล์ Safety_Analytics_ROI_Sim.pbix ในโฟลเดอร์ pbix/
  ทดลองปรับเลื่อนแถบ เป้าหมาย % การลดอุบัติเหตุ เพื่อดูแบบจำลองการคำนวณ ROI และ Cost Savings
















