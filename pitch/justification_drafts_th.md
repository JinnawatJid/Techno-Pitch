# Justification Drafts for Shopder (Internal Notes)

## 1. Matching Algorithm (Technopreneur Perspective)
- **Hybrid Recommendation System:**
    - **Collaborative Filtering:** วิเคราะห์ความสนใจจากพฤติกรรมการปัด (Swipe) ของผู้ใช้ที่คล้ายกัน
    - **Content-based Filtering:** ใช้ Tag และ Image Recognition (Computer Vision) วิเคราะห์ลักษณะเสื้อผ้า (สี, ทรง, สไตล์)
    - **Cold Start Solution:** ให้ผู้ใช้เลือกสไตล์ที่ชอบตอน Onboarding เพื่อให้ระบบแนะนำได้ทันที
- **Tech Goal:** ลด Decision Fatigue (ความเหนื่อยล้าในการตัดสินใจ) และเพิ่ม Transaction Probability

## 2. Platform Leakage (Anti-Leakage Strategy)
- **Escrow Payment System:** เงินไม่ถึงมือผู้ขายจนกว่าผู้ซื้อจะกดยืนยัน ปลอดภัยกว่าไปโอนตรงข้างนอก
- **Exclusive Incentives:**
    - **Green Points:** ได้แต้มเฉพาะเมื่อซื้อผ่านระบบเท่านั้น เอาไปแลกสิทธิประโยชน์ได้
    - **Carbon Certificate:** มีหลักฐานความรักษ์โลกแบบ Official
- **Trust & Reputation:** ระบบรีวิวและคะแนนผู้ขายที่โปร่งใส

## 3. Financials (Business Logic)
- **Burn Rate & Funding:** ช่วง 3 ปีแรกจะระดมทุนจาก Pre-seed/Seed Round และใช้เงินทุนจากผู้ก่อตั้ง (Bootstrapping) เพื่อพัฒนา Tech และสะสมฐานผู้ใช้ (User Acquisition)
- **CAC vs LTV:** ลงทุนการตลาดหนักช่วงแรกเพื่อลด CAC ในระยะยาวผ่าน Organic Growth และ Word of Mouth
- **Revenue Logic:** เน้นเพิ่ม Retention Rate ให้คนอยู่กับแอปนานๆ เพื่อเปลี่ยนจากผู้ใช้ทั่วไปเป็นสมาชิกรายเดือน (Conversion to Subscription)

## 4. Carbon Tracker (Methodology)
- **Data Source:** อ้างอิงฐานข้อมูล **Higg Index** หรือ **Life Cycle Assessment (LCA)** ของเสื้อผ้าแต่ละประเภท (เช่น เสื้อยืด 1 ตัว ประหยัดน้ำ 2,700 ลิตร และลด CO2 ได้ประมาณ 2-3 kg)
- **Calculation:** ใช้สูตร `(New Item Footprint - Refurbished/Shipping Footprint) = Saved Carbon`
- **Verification:** ในอนาคตจะร่วมมือกับสถาบันวิจัยสิ่งแวดล้อมเพื่อรับรองความถูกต้องของระบบคำนวณ

## 5. Competitive Advantage (vs TikTok/FB)
- **Focus vs Generalist:** TikTok เป็นห้างขนาดใหญ่ที่มีทุกอย่าง แต่ Shopder เป็น "Thrift Store Boutique" ที่ออกแบบมาเพื่อคนซื้อของมือสองโดยเฉพาะ (มีระบบตรวจสอบสภาพสินค้า, ไซส์, ตำหนิ ที่ชัดเจนกว่า)
- **Trust vs Wild West:** FB Marketplace คือ "ตัวใครตัวมัน" แต่ Shopder คือ "Managed Marketplace" ที่มีการคัดกรองและระบบชำระเงินที่ปลอดภัย
- **Discovery Experience:** TikTok เน้นความบันเทิง (Entertainment) แต่ Shopder เน้นการค้นหา "ขุมทรัพย์" (Thrill of the Hunt) ที่เหมาะกับของที่มีชิ้นเดียวในโลก (Unique items)
