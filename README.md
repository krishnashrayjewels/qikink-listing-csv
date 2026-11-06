# 📦 Qikink Bulk Listing CSVs — Indian Marketplaces Launch Suite
**Account / Client ID:** `667843`  
**Brand Name:** `Krishna Shray`  
**Platforms Supported:** Flipkart, Meesho, Amazon India (IN)  
**Total Listing Rows:** 67 Sized SKUs (Every apparel size has its own dedicated row)  
**Catalog Scope:** Oversized Tees (UJ35), Classic Round Neck Tees (180 GSM), Fleece Hoodies (320 GSM), Ceramic Mugs (11oz), Canvas Eco Tote Bags, Acrylic Keychains (Pack of 2)  
**Pricing Strategy:** Uniform pricing across all platforms with minimum 10% clean net profit margin strictly AFTER platform commission, Easy Ship logistics, and RTO buffer deductions.

---

## 🛠️ Audit & Compliance Fixes Applied
1. **Title Compliance:** All brackets `[...]` and promotional taglines have been removed from product titles. Titles strictly adhere to marketplace standards:  
   `<Product type> - <Design theme> - <Fabric/GSM> - <Fit>`
2. **Individual Size Rows:** Every apparel SKU is expanded into individual size rows:
   * **UJ35 Oversized T-Shirts:** `XS`, `S`, `M`, `L`, `XL`, `XXL` (SKU Suffixes: `-XS`, `-S`, `-M`, `-L`, `-XL`, `-XXL`)
   * **Classic 180 GSM T-Shirts:** `S`, `M`, `L`, `XL`, `XXL`
   * **Fleece 320 GSM Hoodies:** `S`, `M`, `L`, `XL`, `XXL`
   * **Mugs, Tote Bags & Keychains:** Single free-size / standard row.
3. **Empty Main Image URLs:** `Main Image URL` is strictly empty (`""`) across all rows to prevent any placeholder/fake URL rejections. Real mockup URLs will be inserted by Fo.  
   *Reference Real URL Format:*  
   `https://qikink-assets.s3.ap-south-1.amazonaws.com/clients/667843/clientProducts/32516396/images/Front_1_c_1.jpg`
4. **Authentic Indian Audience Themes:** Eliminated fictional/anime themes in favor of high-demand domestic themes:
   * **Devotional:** Shree Krishna Flute Morpankh, Radha Krishna Bhakti, Mahadev Trishul Damru, Jai Shree Ram Ayodhya, Mahabali Hanumanji.
   * **Festive:** Shubh Deepavali Mandala, Shubh Labh Diya.
   * **Motivational / Typography:** Karma Bhagavad Gita Sanskrit, Kar Har Maidan Fateh, Subah Ki Pehli Chai.
   * **Field Added:** New column `design_status = pending_fo` included in every single row.

---

## 📁 Repository Directory Structure
```
├── /flipkart/
│   └── flipkart_bulk_listing.csv     # 67 rows with FSN/SKU/Size/Attributes
├── /meesho/
│   └── meesho_bulk_listing.csv       # 67 rows formatted for Meesho Supplier Panel
├── /amazon/
│   └── amazon_flat_file_in.csv       # 67 rows formatted for Amazon India Flat File
└── README.md                         # Full pricing mathematics, size charts, HSN codes, and handover audit
```

---

## 💰 First 3 Months Launch Pricing Mathematics
Every single product strictly follows the golden launch rule: **Net margin ≥ 10% at all times (never negative)** after factoring in:
1. **Qikink Base Landed Cost** (Blank fabric/substrate + high-definition DTF/Sublimation printing)
2. **Marketplace Platform Fees** (Referral commission + closing fee + payment gateway GST)
3. **Logistics / Shipping Fee** (Standard 500g / 1kg Easy Ship slabs)
4. **RTO Allocation Buffer** (Risk cushion for occasional undelivered/returned orders)

### 📊 Category-Wise Unit Economics Breakdown

| Category | Qikink SKU / Model | Launch Selling Price | Qikink Cost | Platform Fee (Avg) | Shipping Fee (Avg) | RTO Buffer | Net Profit (INR) | Net Margin % | Status |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Ceramic Mugs** | 11 oz Glossy Ceramic | **₹299** | ₹115 | ₹32 | ₹65 | ₹12 | **+₹75** | **25.08%** | ✅ PASS (>10%) |
| **Keychains (Pack of 2)**| 3mm Acrylic 2x2 | **₹299** | ₹65 | ₹30 | ₹55 | ₹10 | **+₹139** | **46.48%** | ✅ PASS (>10%) |
| **Classic Cotton Tee** | 180 GSM Bio-Wash | **₹349** | ₹195 | ₹35 | ₹65 | ₹18 | **+₹36** | **10.31%** | ✅ PASS (>10%) |
| **Canvas Tote Bag** | 280 GSM Eco Cotton | **₹349** | ₹135 | ₹35 | ₹60 | ₹15 | **+₹104** | **29.79%** | ✅ PASS (>10%) |
| **Oversized Streetwear**| **UJ35 240 GSM** | **₹499** | ₹235 | ₹65 | ₹70 | ₹30 | **+₹99** | **19.83%** | ✅ PASS (>10%) |
| **Fleece Warm Hoodie** | 320 GSM Heavy Fleece | **₹799** | ₹430 | ₹95 | ₹95 | ₹40 | **+₹139** | **17.39%** | ✅ PASS (>10%) |

*Note: Selling prices are uniform (₹299 / ₹349 / ₹499 / ₹799) across Amazon, Flipkart, and Meesho to prevent cross-channel price discrepancies and algorithmic suppression.*

---

## 📐 Qikink Official Size Charts & Technical Specifications

### 1. UJ35 Oversized T-Shirt (240 GSM Salina Micro-Knit)
* **Model Code:** UJ35
* **Fabric:** Salina Fabric (100% Micro-Knit Polyester), 240 GSM, anti-pilling, structured drape.
* **Size Measurements (Inches):**
  * **XS:** Chest 40", Length 27"
  * **S:** Chest 42", Length 28"
  * **M:** Chest 44", Length 29"
  * **L:** Chest 46", Length 30"
  * **XL:** Chest 48", Length 31"
  * **XXL:** Chest 50", Length 32"

### 2. Classic Round Neck T-Shirt (180 GSM 100% Super Combed Cotton)
* **Model Code:** Classic 180
* **Fabric:** 100% Super Combed Cotton, Bio-Washed, Pre-Shrunk, 180 GSM.
* **Size Measurements (Inches):**
  * **S:** Chest 38", Length 26"
  * **M:** Chest 40", Length 27"
  * **L:** Chest 42", Length 28"
  * **XL:** Chest 44", Length 29"
  * **XXL:** Chest 46", Length 30"

### 3. Fleece Pullover Hoodie (320 GSM Bio-Washed Brushed Fleece)
* **Fabric:** 320 GSM Cotton-Poly Blend Heavy Brushed Fleece with Derby Ribbing.
* **Size Measurements (Inches):**
  * **S:** Chest 38", Length 26"
  * **M:** Chest 40", Length 27"
  * **L:** Chest 42", Length 28"
  * **XL:** Chest 44", Length 29"
  * **XXL:** Chest 46", Length 30"

### 4. Ceramic Coffee Mug (11 oz / 330 ml)
* **Dimensions:** Height 9.5 cm, Outer Diameter 8.2 cm, Volume 330 ml.
* **Print Area:** 20 cm x 8.5 cm wrap-around sublimation. Microwave & Dishwasher safe.

### 5. Canvas Eco Tote Bag
* **Dimensions:** Height 14.5" x Width 13.5" x Gusset 2.5", Shoulder Handle Drop 11.5". Capacity: 10 kg.

### 6. Designer Keychains (Pack of 2)
* **Dimensions:** 2.0" x 2.0" (5cm x 5cm), Thickness 3mm transparent acrylic, split key ring diameter 25mm.

---

## 🏛️ Indian GST HSN Codes & Tax Rates
* **T-Shirts & Oversized Tees:** `61091000` (GST 5% for value ≤ ₹1000)
* **Hoodies & Sweatshirts:** `61102000` (GST 5% for value ≤ ₹1000)
* **Ceramic Tableware & Mugs:** `69120010` (GST 12%)
* **Canvas Tote Handbags:** `42022220` (GST 12%)
* **Acrylic & Metal Keychains:** `39269099` (GST 18%)

---

## 🤝 Handover Notes for Fo & Kamlesh
1. **Mockup Images:** `main_image_url` is left empty in all rows. Fo can directly populate live Amazon S3 assets in the established format.
2. **Design Status:** Every row tracks `design_status = pending_fo`. Once Fo uploads mockups, this can be transitioned to `ready_for_upload`.
3. **Account Linkage:** Qikink Client ID `667843` is mapped.
