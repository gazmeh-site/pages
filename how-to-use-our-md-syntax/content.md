# هدر اول (عنوان)
در این نوشته برخی از قواعد MD برای نوشتن مقاله‌های سایت گزمه بررسی می‌شود. این مقاله را می‌توانید با لینک زیر بصورت رندر شده در سایت گزمه ببنید:
[پیش‌نمایش یک فایل نمونه MD در سایت گزمه](http://www.gazmeh.ir/preview?md-url=https%253A%252F%252Fraw.githubusercontent.com%252Fgazmeh-site%252Fgeneral-docs%252Fmain%252Fhow-to-use-our-md-syntax%252Fcontent.md&base-url=&info-url=)
همچنین می‌توانید برای لینک عنوان نگذارید، در اینصورت آدرس لینک همان عنوان لینک است. برای نمایش فایل‌های MD خود می‌توانید در سایت <http://gazmeh.ir> از قسمت «پیش‌نمایش» استفاده کنید.


## هدر دوم (برای عنوان هر فصل یا بخش اصلی)
ابتدا بهتر است قواعد کلی MD را بررسی کنید:
- آشنایی با [مارک‌دون](https://daringfireball.net/projects/markdown/)


### قواعد اصلی
این **بولد**، این _کج‌شده_ و این ~~خط خورده~~ است.

- آیتم اول لیست بدون شماره
- آیتم دوم لیست بدون شماره
- آیتم سوم لیست بدون شماره

1. آیتم اول لیست شماره‌گذاری شده
2. آیتم دوم لیست شماره‌گذاری شده
3. آیتم سوم لیست شماره‌گذاری شده

> این نقل قول است
> > نقل داخلی (نقل قول داخل یک نقل قول)
> - استفاده از لیست در نقل قول (آیتم اول)
> - استفاده از لیست در نقل قول (آیتم دوم)


برای اضافه کردن یک عکس بدون کپشن، می‌توان همچون زیر عمل کرد:

![Alt text for screen readers](https://raw.githubusercontent.com/gazmeh-site/general-docs/main/how-to-use-our-md-syntax/resources/img.png "Just a sample image")

برای اضافه کردن یک عکس با یک کپشن اختصاصی، مانند زیر عمل می‌کنیم:

![Alt text for screen readers](https://raw.githubusercontent.com/gazmeh-site/general-docs/main/how-to-use-our-md-syntax/resources/img.png "Just a smaple image with a caption")

برای خط جداکننده افقی از سه دش استفاده می‌کنیم:

---



## قواعد کد و بلاک کد
این یک `کد اینلاین` است. متغیر `x‍` یک متغیر جنرال است.

```js
const test = 'hello';
const other = 'world';
console.log(test, other);
```

بلاک کد می‌تواند عنوان داشته باشد:

```
[label Output]
Could not connect to server: Connection refused
```

برای اضافه کردن شماره خط از `line_numbers` استفاده میکنیم:
```line_numbers,js
const test = 'hello';
const other = 'world';
console.log(test, other);
```
### کادرهای پیام

در ادامه کادرهای پیام‌ برای نکته، اخطار، توضیح و پیش‌نویس را می‌بینید:

::: note
این یک **نکته** است
:::

::: warning
این یک **اخطار** است
:::

::: info
این یک **توضیح** است
:::

::: draft
این یک **پیش‌نویس** است
:::
