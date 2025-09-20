# EDA_SuperStore_Dataset
# Superstore Data Analysis & RFM Segmentation

## معرفی
این پروژه تحلیل داده‌های فروش یک فروشگاه (Superstore Dataset از Kaggle) است.  
تمرکز اصلی روی تحلیل اکتشافی داده‌ها (EDA) و تحلیل مشتریان با استفاده از روش RFM Segmentation می‌باشد.  
## معرفی دیتاست
سوپر استور یک شرکت خرده‌فروشی مستقر در ایالات متحده است. این شرکت در فروش مبلمان، لوازم اداری و محصولات فناوری تخصص دارد. این دیتاست شامل 20 ستون و 9995 رکورد است. نام ستون ها به شرح زیر است :

Order ID ,	Order Date ,	Ship Date ,	Ship Mode ,	Customer ID ,	Customer Name	, Segment ,	Country ,	City ,	State ,	Postal Code ,	Region ,	Product ID ,	Category ,	Sub-Category ,	Product Name ,	Sales ,	Quantity ,	Discount ,	Profit .
می توانید دیتاست را در لینک زیر مشاهده نمایید : https://drive.google.com/file/d/1tyeZkWXo3Lhs5xVk3dDJYpfvBDaUYR5K/view?usp=drivesdk
## فایل کدها 
EDA_SuperStore_Dataset.ipynb
## مراحل انجام کار
1. EDA (Exploratory Data Analysis)

   - بررسی داده‌ها (missing values, duplicates)
   - بررسی آماری داده‌ها، نمودارهای توزیع و روابط بین ویژگی‌ها
   - تحلیل تک‌متغیره
   - تحلیل دو متغیره 
   - تحلیل چندمتغیره (بررسی همزمان چند ویژگی)   

3. سوالات تحلیلی  
   - بیشتر سود کسب شده از سفارشات مربوط به کدام محصول است؟
   - کدام محصول براساس تعداد فروش پر فروش ترین محصول در این فروشگاه است؟(quantity)
   - بیشترین حجم سفارشات مربوط به کدام شهر است؟
   - کدام دسته از محصولات فروش بیشتری دارند؟(Category)
   - مشتریان دائم کدامند؟ یعنی کدام مشتریان تعداد سفارشات بالاتر و بیشتری دارند؟

4. RFM Analysis  
   - محاسبه Recency (آخرین زمان خرید)  
   - محاسبه Frequency (تعداد دفعات خرید)  
   - محاسبه Monetary (میزان کل خرید)  
   - تقسیم‌بندی مشتری‌ها بر اساس امتیاز RFM  
   - شناسایی مشتریان وفادار، مشتریان پرخطر و مشتریان جدید  

## ابزارها
- Python: Pandas, Numpy, Matplotlib, Seaborn  
- تحلیل RFM با استفاده از Pandas

## نتایج کلیدی
- بیشترین حجم سفارشات مربوط به شهرهای New York City و Los Angeles و Philadelphia و San Francisco است.
- محصولات دسته Office supplies بیشترین فروش را از نظر سفارشات دارند.
- محصولات دسته Technology بیشترین فروش رلا برحسب (sales) داشته اند.
- 10 مشتری که از نظر تعداد سفارشات ، خرید بیشتری داشته اند بدست آمده است.اولین مشتری William Brown است.
- بخش RFM نشان داد که حدود 250 تا از مشتریان در دسته وفادار (Loyal Customers) قرار دارند و 200 نفر از مشتریان در دسته need attention قرار دارند و حدود 140 نفر از مشتریان به عنوان بهترین مستریان شناسایی شدند . 230 نفر از مشتریان در دسته potential customers تعلق دارند.  

