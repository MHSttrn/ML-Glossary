---
layout: word
word: Selection Bias
translation: سوگیری انتخاب
tags:
  - word
  - S
---
علت بروز خطا در نتیجه‌گیری از داده‌های نمونه‌گیری شده، فرایند انتخاب است که ضمن آن تفاوت‌های سیستماتیک بین نمونه‌های مشاهده شده در مجموعه داده‌ها و موارد مشاهده نشده ایجاد می‌شود.

اشکال زیر از سوگیری انتخاب وجود دارد:

سوگیری پوشش: جمعیت نشان داده شده در مجموعه داده‌ها با جمعیتی که مدل یادگیری ماشین پیش بینی کرده است مطابقت ندارد.

سوگیری نمونه‌‌برداری: داده‌ها به صورت تصادفی از گروه هدف جمع آوری نمی‌شوند.

سوگیری عدم پاسخگویی یا سوگیری مشارکت: کاربران گرو‌‌ه‌های خاصی نسبت به کاربران گروه‌های دیگر از نظرسنجی انصراف می‌دهند.

برای مثال، فرض کنید قرار است یک مدل یادگیری ماشین طراحی کنید که میزان علاقه مردم به یک فیلم را پیش‌بینی می‌کند. برای جمع آوری داده‌های آموزشی، نظرسنجی را برای همه افرادی که در ردیف اول سالن نمایش فیلم هستند، انجام می دهید. به صورت ناخواسته، ممکن است این روش منطقی برای جمع آوری مجموعه داده به نظر برسد. با این حال، این شکل از جمع آوری داده‌ها ممکن است اشکال زیر از سوگیری انتخاب را ایجاد کند:

* سوگیری پوشش: با نمونه‌گیری از جمعیتی که تماشای فیلم را انتخاب کرده‌اند، ممکن است  پیش‌بینی‌های(خروجی) مدل به افرادی که قبلاً آن میزان علاقه به فیلم را ابراز نکرده‌اند تعمیم ندهد.
* سوگیری نمونه‌برداری: به جای نمونه برداری تصادفی از جمعیت مورد نظر (همه افراد حاضر در فیلم)، فقط از افرادی که در ردیف اول هستند نمونه برداری کردید. این احتمال وجود دارد که افراد حاضر در ردیف اول،  بیشتر از کسانی که در ردیف‌های دیگر بودند به فیلم علاقه مند باشند.
* سوگیری بدون پاسخ: به طور کلی افرادی با نظرات قوی‌تر، بیشتر از افرادی که نظرات ملایم دارند به نظرسنجی های اختیاری پاسخ می‌دهند. از آنجا که نظرسنجی فیلم به صورت اختیاری انجام می‌شود، محتمل است پاسخ‌ها یک [توزیع دو](https://wikipedia.org/wiki/Multimodal_distribution) بعدی تشکیل دهند تا یک توزیع معمولی (به شکل زنگ).