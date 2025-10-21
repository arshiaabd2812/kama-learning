
### 1) *An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale (ViT)*
*نویسندگان:* Alexey Dosovitskiy و همکاران  
*محل انتشار / سال:* ICLR (نسخه arXiv: 2020)  
*لینک:* https://arxiv.org/abs/2010.11929  | کد: https://github.com/google-research/vision_transformer  
*Citation:* 75314  
*Impact Factor:* — (کنفرانسی)  
*خلاصه ساده:* ViT نشان داد می‌شود تصویر را مثل «دنباله‌ای از پچ‌ها» به ترنسفورمر داد و بدون CNN هم به دقت عالی رسید؛ با پیش‌آموزش بزرگ‌مقیاس و فاین‌تیون دقیق، روی ImageNet عالی عمل می‌کند.  
*دیتاست / داده‌ها:* JFT-300M (پیش‌آموزش بزرگ)، ImageNet و بنچمارک‌های کلاسیک برای ارزیابی  
*پلتفرم اجرا:* معمولاً JAX/Flax یا PyTorch (ریپو رسمی: PyTorch/JAX)

---

### 2) *Swin Transformer: Hierarchical Vision Transformer using Shifted Windows*
*نویسندگان:* Ze Liu و همکاران  
*محل انتشار / سال:* ICCV 2021 (arXiv:2103.14030)  
*لینک:* https://arxiv.org/abs/2103.14030  | کد: https://github.com/microsoft/Swin-Transformer  
*Citation:* 24313  
*Impact Factor:* — (کنفرانسی)  
*خلاصه ساده:* با «پنجره‌های شیفت‌شونده» محاسبات attention را محلی و کارآمد می‌کند، اما ارتباط بین‌پنجره‌ای را هم حفظ می‌کند؛ یک ستون‌فقرات همه‌منظوره برای طبقه‌بندی، آشکارسازی و Segmentation.  
*دیتاست / داده‌ها:* ImageNet-1K (کلاس‌بندی)، COCO (آشکارسازی/تقسیم‌بندی)، ADE20K (تقسیم‌بندی معنایی)  
*پلتفرم اجرا:* PyTorch (ریپوی رسمی مایکروسافت)

---

### 3) *Masked Autoencoders Are Scalable Vision Learners (MAE)*
*نویسندگان:* Kaiming He و همکاران  
*محل انتشار / سال:* CVPR 2022 (arXiv:2111.06377)  
*لینک:* https://arxiv.org/abs/2111.06377  | کد: https://github.com/facebookresearch/mae  
*Citation:* 8846  
*Impact Factor:* — (کنفرانسی)  
*خلاصه ساده:* بخش بزرگی از پچ‌های تصویر را ماسک می‌کند و مدل را مجبور به بازسازی می‌کند؛ یک پیش‌آموزش «خودنظارتی» ساده و بسیار مؤثر که انتقال‌پذیری عالی می‌دهد.  
*دیتاست / داده‌ها:* ImageNet-1K (برای پیش‌آموزش خودنظارتی و ارزیابی)، انتقال به وظایف پایین‌دستی  
*پلتفرم اجرا:* PyTorch (پیاده‌سازی رسمی متا)

---

### 4) *Segment Anything (SAM)*
*نویسندگان:* Alexander Kirillov و همکاران  
*محل انتشار / سال:* ICCV 2023 (arXiv:2304.02643)  
*لینک:* https://arxiv.org/abs/2304.02643  | کد: https://github.com/facebookresearch/segment-anything | سایت: https://segment-anything.com/  
*Citation:* 9223  
*Impact Factor:* — (کنفرانسی)  
*خلاصه ساده:* یک «مدل پایهٔ تقسیم‌بندی» که با «پرامپت» (نقطه/کادر/متن) برای هر تصویر، تقریباً هر شیء را جدا می‌کند؛ روی دیتاست غول‌آسای *SA-1B* با بیش از ۱ میلیارد ماسک آموزش داده شده است.  
*دیتاست / داده‌ها:* SA-1B (۱۱ میلیون تصویر، ۱ میلیارد ماسک)  
*پلتفرم اجرا:* PyTorch (ریپو رسمی متا)

---

### 5) *DINOv2: Learning Robust Visual Features without Supervision*
*نویسندگان:* Maxime Oquab و همکاران  
*محل انتشار / سال:* arXiv 2023 (پیش‌چاپ پژوهشی مدل پایه)  
*لینک:* https://arxiv.org/abs/2304.07193  | کد: https://github.com/facebookresearch/dinov2  
*Citation:* 4734  
*Impact Factor:* — (پیش‌چاپ)  
*خلاصه ساده:* با *Self-Supervised* و دیتاست بزرگِ «گزینش‌شده و پاک‌سازی‌شده»، ویژگی‌های «همه‌منظوره» (general-purpose) تولید می‌کند که بدون فاین‌تیون هم روی طیف وسیعی از وظایف قوی‌اند.  
*دیتاست / داده‌ها:* ~142M تصویر گزینش‌شده و متنوع (بدون برچسب)  
*پلتفرم اجرا:* PyTorch (ریپوی رسمی متا)

---

## 📊 جدول خلاصه مقالات

| # | نوع مقاله | سال | محل انتشار | موضوع اصلی | دیتاست | کد | Citation |
|---|-----------|-----|------------|------------|--------|-----|----------|
| 1 | پژوهشی | 2020/2021 | ICLR / arXiv | معرفی ViT (ترنسفورمرِ بینایی) | JFT-300M, ImageNet | [vision_transformer](https://github.com/google-research/vision_transformer) | 75314 |
| 2 | پژوهشی | 2021 | ICCV / arXiv | ستون‌فقرات سلسله‌مراتبی با پنجره‌های شیفتی | ImageNet, COCO, ADE20K | [Swin-Transformer](https://github.com/microsoft/Swin-Transformer) | 24313 |
| 3 | پژوهشی | 2022 | CVPR / arXiv | پیش‌آموزش خودنظارتی با بازسازی پچ‌ها | ImageNet-1K | [mae](https://github.com/facebookresearch/mae) | 8846 |
| 4 | پژوهشی | 2023 | ICCV / arXiv | مدل پایهٔ تقسیم‌بندی با SA-1B | SA-1B (۱B ماسک) | [segment-anything](https://github.com/facebookresearch/segment-anything) | 9223 |
| 5 | پژوهشی | 2023 | arXiv | ویژگی‌های بصری همه‌منظوره (Self-Supervised) | ~142M تصویر بدون برچسب | [dinov2](https://github.com/facebookresearch/dinov2) | 4734 |

---

## 🧠 چرا این پنج‌تا «همگرا» هستن؟
- همگی روی *DL/AI خالص* متمرکزند  
- محور مشترک: *ترنسفورمرها و مدل‌های پایه در بینایی ماشین*  
- زنجیرهٔ کامل: ViT پایه → سازمان‌دهی کارآمد (Swin) → پیش‌آموزش خودنظارتی (MAE) → مدل پایهٔ کاربردی در Segmentation (SAM) → ویژگی‌های همه‌منظورهٔ بدون نظارت (DINOv2)

---

## 🔗 منابع کلیدی
- ViT (arXiv + صفحه ICLR/OpenReview): «Cited by 75314»  
- Swin (Semantic Scholar / arXiv): «24313 citations»  
- MAE (Semantic Scholar / arXiv): «8846 citations»  
- SAM (Semantic Scholar / ICCV 2023): «9223 citations»  
- DINOv2 (Semantic Scholar / arXiv): «4734 citations»



## 🧠 ۵ واژه‌ی کلیدی اصلی

1. *Transformer Architecture*  
   > ساختار شبکه‌ای مبتنی بر attention که جایگزین CNN شده و پایه‌ی مدل‌های مدرن بینایی و زبانی در هوش مصنوعی است.  
   > در همه‌ی مقالات (ViT, Swin, MAE, SAM, DINOv2) به‌عنوان هسته‌ی مدل استفاده شده.

2. *Self-Supervised Learning*  
   > یادگیری از داده‌های بدون برچسب از طریق پیش‌وظایف (masking, reconstruction, contrastive).  
   > محور MAE و DINOv2 و بخش مهمی از آموزش SAM.

3. *Representation Learning*  
   > توانایی مدل برای استخراج ویژگی‌های کلی و انتقال‌پذیر از داده‌های خام؛ هدف نهایی مدل‌های پایه مثل DINOv2 و MAE.

4. *Foundation Models*  
   > مدل‌های بزرگ و عمومی که می‌توانند بدون بازآموزی گسترده در حوزه‌های مختلف استفاده شوند (SAM و DINOv2 مصداق کامل‌اند).

5. *Vision Transformer (ViT)*  
   > رویکردی که تصویر را به پچ‌های ترتیبی تقسیم می‌کند تا مثل متن در ترنسفورمر پردازش شود؛ آغازگر موج جدید در یادگیری عمیق بینایی.

---

### 💬 چرا این ۵ واژه انتخاب شدند؟
- *Transformer Architecture* → بنیان مشترک همه‌ی مدل‌ها  
- *Self-Supervised Learning* → مسیر اصلی یادگیری مدرن بدون داده‌ی برچسب‌خورده  
- *Representation Learning* → هدف کلّی استخراج دانش عمومی از داده  
- *Foundation Models* → گام بعدی در تعمیم و چندمنظوره‌بودن AI  
- *Vision Transformer* → نقطه‌ی آغاز تحول در بینایی ماشین و الهام‌بخش سایر مدل‌ها  

---

> 📚 این پنج کلیدواژه در مجموع بیانگر سیر تحول هوش مصنوعی از «مدل‌های عمیق اختصاصی» به «مدل‌های پایه‌ی عمومی و چندمنظوره» هستند — از ViT تا SAM و DINOv2
