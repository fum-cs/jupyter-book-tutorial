<div dir="rtl" markdown="1">

# سایت‌سازهای استاتیک

در این مجموعه آموزشی با **سایت‌سازهای استاتیک** و کاربردهای آن‌ها آشنا می‌شوید. سایت‌ساز استاتیک ابزاری است که به شما اجازه می‌دهد صفحات وب را به صورت فایل‌های ساده (مانند Markdown یا HTML) ایجاد و سپس آن‌ها را به یک وب‌سایت کامل تبدیل کنید. این صفحات نهایی، بدون نیاز به پایگاه داده یا پردازش سمت سرور، به صورت فایل‌های ثابت (Static) روی هاست قرار می‌گیرند.

- یک مثال: 
  [مطالب درس یادگیری ماشین](https://fum-cs.github.io/machine-learning/)

## چرا سایت‌ساز استاتیک؟

- سادگی و سرعت: صفحات به صورت فایل‌های ساده ذخیره می‌شوند و بارگذاری آن‌ها بسیار سریع است.
- امنیت بالا: به دلیل نبود پایگاه داده و کدهای سمت سرور، احتمال حملات امنیتی بسیار کمتر است.
- هزینه پایین: می‌توانید سایت خود را روی سرویس‌های رایگان مانند GitHub Pages یا Netlify منتشر کنید.
- قابلیت کنترل نسخه: با استفاده از گیت (Git) می‌توانید تغییرات سایت را مدیریت و نسخه‌بندی کنید.

---

## دسته‌بندی سایت‌سازهای استاتیک و پوسته‌ها 

سایت‌سازهای استاتیک معمولاً به دو دسته تقسیم می‌شوند:

### ۱. موتورهای سایت‌ساز (Static Site Generators)

این ابزارها فایل‌های متنی (مانند Markdown) را به صفحات HTML تبدیل می‌کنند:

- [MkDocs](https://www.mkdocs.org/) — مخصوص مستندسازی پروژه‌ها با Markdown. (زبان: Python)
- [GitBook](https://www.gitbook.com/) — ساخت مستندات و کتاب‌های آنلاین. (زبان: Node.js/JavaScript)
- [Docusaurus](https://docusaurus.io/) — مناسب برای مستندسازی و وب‌سایت‌های پروژه‌های متن‌باز. (زبان: Node.js/React)
- [Jekyll](https://jekyllrb.com/) — محبوب و سازگار با GitHub Pages. (زبان: Ruby)
- [Jupyter Book](https://jupyterbook.org/) — ساخت کتاب و مستندات علمی با پشتیبانی از نوت‌بوک‌های ژوپیتری. (زبان: Python)
- [Hugo](https://gohugo.io/) — سریع و قدرتمند با زبان Go. (زبان: Go)
- [Hexo](https://hexo.io/) — مناسب برای وبلاگ‌نویسی و مبتنی بر Node.js. (زبان: Node.js)
- [Pelican](https://getpelican.com/) — مبتنی بر Python. (زبان: Python)

### ۲. پوسته‌ها و قالب‌های آماده

برخی ابزارها یا قالب‌ها بر پایه سایت‌سازهای بالا ساخته شده‌اند و ظاهر و امکانات خاصی را ارائه می‌دهند:

- [Just-the-docs](https://just-the-docs.github.io/just-the-docs/) — قالب ساده و زیبا برای مستندسازی، قابل استفاده با Jekyll.
- [Alfolio](https://alfolio.github.io/) — قالب حرفه‌ای برای Jekyll، مناسب برای رزومه و سایت شخصی.
- [Make-the-docs](https://github.com/Make-the-docs/make-the-docs) — قالبی برای مستندسازی با MkDocs.

برای مشاهده فهرست کامل سایت‌سازها و قالب‌ها به [jamstack.org/generators](https://jamstack.org/generators/) مراجعه کنید.

---

## نمونه سایت‌های ساخته‌شده با سایت‌سازهای استاتیک

- [سایت علوم کامپیوتر فردوسی](https://fumcs.github.io/)
- [سایت آزمایشگاه گراف](https://gta-lab.github.io/)
- [سایت شخصی امین‌طوسی](https://mamintoosi.github.io/)

---

## نمونه‌هایی از برنامه درسی و درس‌ها با سایت‌سازهای مختلف

- [برنامه درسی علوم کامپیوتر با MkDocs](http://cs-um.github.io/docs)
- [برنامه درسی با GitBook](https://cs-um.gitbook.io/curr/)
- [برنامه درسی با Docusaurus](https://fum-cs.github.io/)

### نمونه درس‌ها

- [یادگیری عمیق با Just-the-docs](https://fum-cs.github.io/dl-fall-2023/)
- [Modern C++ با Just-the-docs](https://fum-cs.github.io/modern-cpp/)
- [شبکه‌های عصبی با Jupyter Book](https://fum-cs.github.io/neural-networks/)
- [سایر درسها](https://mamintoosi.github.io/teaching/)

---

## منابع بیشتر

برای مطالعه بیشتر و آشنایی با نحوه ساخت سایت شخصی با سایت‌سازهای استاتیک، به سایت زیر مراجعه کنید:  
[چگونه سایت شخصی خود را بسازیم؟ (قسمت اول)](https://aprd.ir/create-your-own-website-part1/)

</div>

## References

```{bibliography}
```