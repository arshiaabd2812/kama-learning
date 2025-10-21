> تمرکز: الگوریتم‌های کلاسیک و بسیار پراستفاده‌ی ML برای داده‌های جدولی — XGBoost, LightGBM, CatBoost, Gradient Boosting, Random Forests

---

## ✨ مقالات پیشنهادی با خلاصه ساده و لینک

### 1) *XGBoost: A Scalable Tree Boosting System*  
*نویسندگان:* Tianqi Chen, Carlos Guestrin  
*محل انتشار / سال:* KDD, 2016  
*لینک:* https://dl.acm.org/doi/10.1145/2939672.2939785  
*Citation:* 64653  
*Impact Factor:* — (کنفرانسی)  
*خلاصه به زبان ساده:*  
پیاده‌سازی بسیار بهینه‌ی Gradient Boosting روی درخت‌ها با نوآوری‌هایی مثل *Weighted Quantile Sketch* و *Sparsity-aware* که روی داده‌های بزرگ و پراکنده هم سریع و دقیق است.  
*دیتاست / داده‌ها:* مجموعه‌های عمومی و رقابت‌های Kaggle/UCI (مطالعات بنچمارک متنوع)  
*پلتفرم اجرا:* C++ هسته، رابط‌های Python/R/…  
*کد / گیت‌هاب:* https://github.com/dmlc/xgboost  

---

### 2) *LightGBM: A Highly Efficient Gradient Boosting Decision Tree*  
*نویسندگان:* Guolin Ke و همکاران  
*محل انتشار / سال:* NeurIPS, 2017  
*لینک:* https://papers.nips.cc/paper/6907-lightgbm-a-highly-efficient-gradient-boosting-decision-tree.pdf  
*Citation:* 20058  
*Impact Factor:* — (کنفرانسی)  
*خلاصه به زبان ساده:*  
با ایده‌های *GOSS* (نمونه‌گیری بر پایه گرادیان) و *EFB* (باندل‌کردن ویژگی‌ها)، یادگیری GBDT را به‌طور چشمگیری سریع‌تر می‌کند بدون افتِ معنی‌دار دقت.  
*دیتاست / داده‌ها:* بنچمارک‌های عمومی (Image/Click/CTR/… در مقاله)  
*پلتفرم اجرا:* C++/Python  
*کد / گیت‌هاب:* https://github.com/microsoft/LightGBM  

---

### 3) *CatBoost: Unbiased Boosting with Categorical Features*  
*نویسندگان:* Liudmila Prokhorenkova و همکاران  
*محل انتشار / سال:* NeurIPS, 2018  
*لینک:* https://papers.nips.cc/paper/7898-catboost-unbiased-boosting-with-categorical-features.pdf  
*Citation:* 6722  
*Impact Factor:* — (کنفرانسی)  
*خلاصه به زبان ساده:*  
برای *ویژگی‌های دسته‌ای* راه‌حل اصولی ارائه می‌دهد (Target Leakage را با *Ordered Boosting* و *Ordered Target Statistics* مهار می‌کند) و روی بسیاری از دیتاست‌های جدولی دقت بالایی دارد.  
*دیتاست / داده‌ها:* مجموعه‌های عمومی متنوع (طبقه‌بندی/رگرسیون)  
*پلتفرم اجرا:* C++/Python  
*کد / گیت‌هاب:* https://github.com/catboost/catboost  

---

### 4) *Greedy Function Approximation: A Gradient Boosting Machine*  
*نویسندگان:* Jerome H. Friedman  
*محل انتشار / سال:* Annals of Statistics, 2001  
*لینک:* https://projecteuclid.org/journals/annals-of-statistics/volume-29/issue-5/Greedy-function-approximation-A-gradient-boosting-machine/10.1214/aos/1013203451.full  
*Citation:* 37113  
*Impact Factor:* — (ژورنال آماری؛ بسته به سال متغیر)  
*خلاصه به زبان ساده:*  
مبنای نظری *Gradient Boosting* را می‌گذارد: ساخت مدل به‌صورت افزایشی با حداقل‌سازی تدریجی خطا روی توابع پایه (مثل درخت‌ها). پایه‌ای‌ترین مرجع برای boosting در ML.  
*دیتاست / داده‌ها:* مثال‌های عددی/تجربی در مقاله  
*پلتفرم اجرا:* — (مقالهٔ نظری/پایه)  
*کد / گیت‌هاب:* پیاده‌سازی‌های مرجع در sklearn / XGBoost / LightGBM  

---

### 5) *Random Forests*  
*نویسندگان:* Leo Breiman  
*محل انتشار / سال:* Machine Learning, 2001  
*لینک:* https://link.springer.com/article/10.1023/A%3A1010933404324  
*Citation:* 165991  
*Impact Factor:* — (ژورنال ML؛ بسته به سال متغیر)  
*خلاصه به زبان ساده:*  
میانگین‌گیری روی تعداد زیادی درختِ تصادفیِ کم‌همبسته باعث کاهش واریانس و بهبود تعمیم می‌شود؛ الگوریتمی پایدار، کم‌حساس به تنظیمات و بسیار قوی برای داده‌های جدولی.  
*دیتاست / داده‌ها:* مثال‌های کلاسیک (UCI و …)  
*پلتفرم اجرا:* پیاده‌سازی‌های متعدد (scikit-learn و …)  
*کد / گیت‌هاب:* https://github.com/scikit-learn/scikit-learn  

---

## 📊 جدول خلاصه مقالات

| # | نوع مقاله | سال | محل انتشار | موضوع اصلی | دیتاست | پلتفرم اجرا | کد | Citation |
|---|-----------|-----|------------|------------|--------|-------------|-----|----------|
| 1 | پژوهشی | 2016 | KDD | تقویتیِ درختی با بهینه‌سازی مقیاس‌پذیر | عمومی/Kaggle | C++/Python | [XGBoost](https://github.com/dmlc/xgboost) | 64653 |
| 2 | پژوهشی | 2017 | NeurIPS | GBDT بسیار سریع (GOSS/EFB) | عمومی | C++/Python | [LightGBM](https://github.com/microsoft/LightGBM) | 20058 |
| 3 | پژوهشی | 2018 | NeurIPS | Boosting ویژهٔ ویژگی‌های دسته‌ای | عمومی | C++/Python | [CatBoost](https://github.com/catboost/catboost) | 6722 |
| 4 | نظری/پایه | 2001 | Ann. Stat. | بنیان نظری Gradient Boosting | مثال‌های عددی | — | (sklearn/…) | 37113 |
| 5 | پژوهشی | 2001 | Machine Learning | جنگل تصادفی (کاهش واریانس با تجمیع) | مثال‌های کلاسیک | — | [scikit-learn](https://github.com/scikit-learn/scikit-learn) | 165991 |
