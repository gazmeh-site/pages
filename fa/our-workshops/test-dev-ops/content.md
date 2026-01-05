---
title: کارگاه تجمیع پیوسته و تضمین کیفیت سورس کد
description: آموزش طراحی و پیاده‌سازی CI/CD با Jenkins، Docker و SonarQube برای تست پیوسته و ارزیابی کیفیت سورس کد
navigation.icon: i-lucide-git-branch
---

::callout{icon="i-lucide-info"}
در این کارگاه، فرآیند **تجمیع پیوسته (CI/CD)** و **تضمین کیفیت سورس کد** با تمرکز بر Jenkins، Docker و SonarQube به‌صورت عملی آموزش داده می‌شود.
::

## مراحل کلی کارگاه

::steps{level="3"}

### آشنایی با مفاهیم CI/CD و زیرساخت
درک مفاهیم پایه تجمیع پیوسته، خودکارسازی و زیرساخت به‌عنوان کد.

### پیاده‌سازی Pipelineهای عملی
طراحی و پیاده‌سازی Pipelineهای Jenkins برای پروژه‌های واقعی با استفاده از Docker.

### تضمین کیفیت و تحلیل سورس کد
ارزیابی کیفیت سورس کد و یکپارچه‌سازی ابزارهای تحلیل استاتیک در چرخه CI/CD.

::

## معرفی کارگاه

برای اجرای **تست پیوسته و خودکار** در پروژه‌های نرم‌افزاری، وجود یک چارچوب **تجمیع پیوسته (CI/CD)** ضروری است.  
در این کارگاه، مفاهیم و ابزارهای اصلی CI/CD بررسی شده و شرکت‌کنندگان با نحوه طراحی، پیاده‌سازی و مدیریت Pipelineهای خودکار آشنا می‌شوند.

یکی از محورهای کلیدی این کارگاه، **ارزیابی کیفیت سورس کد** در زبان‌ها و فناوری‌های مختلف و یکپارچه‌سازی این فرآیند با چرخه توسعه نرم‌افزار است.

## سرفصل‌های کارگاه

::accordion

:::accordion-item{label="مفاهیم پایه CI/CD و Jenkins"}
- مفاهیم پایه تجمیع پیوسته و تحویل پیوسته  
- مقدمه‌ای بر Jenkins  
- نصب و راه‌اندازی Jenkins  
:::

:::accordion-item{label="Docker و خودکارسازی ساخت"}
- مقدمه‌ای بر Docker  
- ساخت یک اپلیکیشن نمونه در Jenkins با استفاده از Docker  
- اجرای تست و Build در Docker Containerها  
:::

:::accordion-item{label="زیرساخت به‌عنوان کد و Jenkins Job DSL"}
- مقدمه‌ای بر Infrastructure as Code  
- مفاهیم Jenkins Job DSL  
- استفاده از Jenkins Job DSL در ساخت اپلیکیشن‌ها  
:::

:::accordion-item{label="Pipeline در Jenkins"}
- مقدمه‌ای بر Pipelineها در Jenkins  
- تفاوت Pipelineها و Jenkins Job DSL  
- بررسی مثال Pipeline در پروژه:
  - Java + Maven  
  - Node.js  
:::

:::accordion-item{label="یکپارچه‌سازی Jenkins با ابزارها"}
- یکپارچه‌سازی Jenkins با GitHub  
- یکپارچه‌سازی Jenkins با GitLab  
- یکپارچه‌سازی Jenkins با Bitbucket  
- اتصال Jenkins به پروژه‌های Java با Maven یا Gradle  
:::

:::accordion-item{label="Jenkins Agentها و مدیریت دسترسی"}
- مقدمه‌ای بر Jenkins Slave / Agent  
- راه‌اندازی Agent با استفاده از SSH  
- بررسی Blue Ocean  
- Authentication و Authorization در Jenkins  
:::

:::accordion-item{label="تضمین کیفیت سورس کد با SonarQube"}
- راه‌اندازی SonarQube  
- شناخت مولفه‌های SonarQube  
- تحلیل سورس کد پروژه‌های Maven و Gradle  
- یکپارچه‌سازی SonarQube با Jenkins  
- یکپارچه‌سازی SonarQube با IDEهای توسعه  
:::

::
