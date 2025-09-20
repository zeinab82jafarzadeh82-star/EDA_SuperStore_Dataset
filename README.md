# EDA_SuperStore_Dataset
# Superstore Data Analysis & RFM Segmentation

## معرفی
این پروژه تحلیل داده‌های فروش یک فروشگاه (Superstore Dataset از Kaggle) است.  
تمرکز اصلی روی تحلیل اکتشافی داده‌ها (EDA) و تحلیل مشتریان با استفاده از روش RFM Segmentation می‌باشد.  
## معرفی دیتاست
سوپر استور یک شرکت خرده‌فروشی مستقر در ایالات متحده است. این شرکت در فروش مبلمان، لوازم اداری و محصولات فناوری تخصص دارد. این دیتاست شامل 20 ستون و 9995 رکورد است. نام ستون ها به شرح زیر است :

Order ID ,	Order Date ,	Ship Date ,	Ship Mode ,	Customer ID ,	Customer Name	, Segment ,	Country ,	City ,	State ,	Postal Code ,	Region ,	Product ID ,	Category ,	Sub-Category ,	Product Name ,	Sales ,	Quantity ,	Discount ,	Profit .
<img width="1601" height="25" alt="image" src="https://github.com/user-attachments/assets/6c22d034-c571-4f74-b272-f64d77cca2d3" />


## مراحل انجام کار
1. EDA (Exploratory Data Analysis)  
   - بررسی داده‌ها (missing values, duplicates)  
   - تحلیل تک‌متغیره (توزیع فروش، سود، تعداد سفارش‌ها بر اساس دسته‌بندی کالا)  
   - تحلیل دو متغیره (رابطه بین فروش و سود، کالاها در مناطق مختلف)  
   - تحلیل چندمتغیره (بررسی همزمان چند ویژگی)  
   - رسم نمودارهای متنوع با Matplotlib و Seaborn  

2. سوالات تحلیلی  
   - بیشترین فروش مربوط به کدام دسته کالا بوده است؟  
   - کدام منطقه بیشترین سود را ایجاد کرده است؟  
   - سهم هر گروه مشتری از کل درآمد فروشگاه چقدر است؟  

3. RFM Analysis  
   - محاسبه Recency (آخرین زمان خرید)  
   - محاسبه Frequency (تعداد دفعات خرید)  
   - محاسبه Monetary (میزان کل خرید)  
   - تقسیم‌بندی مشتری‌ها بر اساس امتیاز RFM  
   - شناسایی مشتریان وفادار، مشتریان پرخطر و مشتریان جدید  

## ابزارها
- Python: Pandas, Numpy, Matplotlib, Seaborn  
- تحلیل RFM با استفاده از Pandas  

## نتایج کلیدی
- بیشترین فروش مربوط به دسته Technology است.  
- بیشترین سود از دسته Office Supplies حاصل شده است.  
- مشتریان در منطقه West بیشترین تعداد خرید را داشتند.  
- بخش RFM نشان داد که حدود ۱۵٪ مشتریان در دسته وفادار (Loyal Customers) قرار دارند و ۱۰٪ مشتریان در دسته خطر از دست رفتن (At Risk) شناسایی شدند.  

## دیتاست
- دیتاست اصلی از Kaggle: [Superstore Dataset](https://www.kaggle.com/datasets)
