# گیت ریپازیتوری رو کلون می‌کنیم
git clone https://github.com/username/username.github.io
cd username.github.io  # وارد پوشه ریپازیتوری می‌شی

# فایل portfolio.html رو به پوشه ریپازیتوری اضافه کن
# (این فایل باید در همون جایی باشه که ترمینال باز کردی)
mv /path/to/your/portfolio.html ./index.html  # فایل رو به اسم index.html تغییر میدیم

# فایل‌های جدید رو استیج می‌کنیم (برای commit)
git add .

# تغییرات رو commit می‌کنیم
git commit -m "Add portfolio site"

# تغییرات رو به ریپازیتوری GitHub push می‌کنیم
git push origin main
