---
name: فرم گزارش آزمایش سوم
about: برای نوشتن گزارش آزمایشگاه از این تمپلیت استفاده کنید
title: Session 3 Report
labels: documentation
assignees: amirhossein1376

---

Team Name: `[FILL HERE]`

Student Name of member 1: `[کسرا دماوندی اصلی]`
Student No. of member 1: `[96101602]`

Student Name of member 2: `[رضا امینی مجد]`
Student No. of member 2: `[97101275]`

- [ ] Read Session Contents.

### Section 3.3.1
- [ ] Investigate the /proc/ directory
    1. [ ] `[![1](https://user-images.githubusercontent.com/33892567/184600475-6069c446-f82e-4c55-b478-159810f3056a.png)
]`

### Section 3.3.2

- [ ] Do 5 subtasks from 1 to 5:
    1. [ ] `[نسخه لینوکس مورد استفاده و نسخه gcc استفاده شده برای کامپایل هسته سیستم عامل را نشان میدهد. ]`
    1. [ ] `[cpuinfo: اطلاعات سی پی یو سیستم را نمایش میدهد.    
    2. meminfo: اطلاعات راجع به مقدار حافظه استفاده شده را نمایش میدهد
    3. 
    4. ![2-1](https://user-images.githubusercontent.com/33892567/184621187-511f9af7-0020-4af8-8671-2733b57cb775.png)
![2-2](https://user-images.githubusercontent.com/33892567/184621193-c3ff8363-4baa-4409-bc49-67bbf251d864.png)
]`

    5. [ ] `[]![3](https://user-images.githubusercontent.com/33892567/184632110-31dbf0ce-e0f6-4193-b61b-9dbef5dd44c1.PNG)
`
]`
]`
    6. [ ] `[FILL HERE with screen capture from your programs execution.]`
    7. [ ] `[اجازه این کار را نمیدهد زیرا نیازمند سطح دسترسی root می باشد.]`

## Section 3.3.3

- [ ] Write (in English or Persian) about each file in /proc/(PID) directory:
    1. `[این فایل خط فرمان یک پردازه را نشان میدهد.]`
    1. `[این فایل متغیر های محیطی برنامه را نشان میدهد.]`
    1. `[اطلاعات یک پردازه مانند نام، وضعیت و.. را به شکل نا خوانا برای کاربر نمایش میدهد.]`
    1. `[این فایل شامل اطلاعات فیلهای stat و statm به شکلی خوانا و قابل فهم برای کاربر است.]`
    1. `[این فایل شامل اطلاعات راجع به حافظه مصرف شده توسط پردازه در واحد صفحه است.]`
    1. `[یک لینک به دایرکتوری پردازه فعلی را نشان میدهد.]`
    1. `[یک لینک نمادین به فایل باینری پردازه مورد نظر می باشد.]`
    1. `[لینکی به دایرکتوری root این پردازه می باشد]`

- [ ] Place your script for shwoing PID of running porcesses and their name here:
    - [ ] `[pstree -cp]`

- [ ] Place your source code for a program that shows details of a program by receiving PID:
    - [ ] `[![4](https://user-images.githubusercontent.com/33892567/184637446-30250ff2-8a12-4e74-b01e-5c5f3921bd84.PNG)
]`

### Section 3.3.4

- [ ] Write (in English or Persian) about each file in /proc/ directory:
    1. `[اطلاعات مصرف حافظه را نشان میدهد]`
    1. `[نسخه لینوکس مورد استفاده و gcc استفاده شده برای کامپایل هسته سیستم عامل را نشان میدهد.]`
    1. `[زمانی که هسته روشن بوده است و همچنین زمانی که در حالت idle بوده است را نشان میدهد.]`
    1. `[اطلاعات مربوط به فعالیت هسته سیستم عامل را نشان میدهد.]`
    1. `[وضعیت تمام فایل های بارگذاری شده را نشان میدهد.]`
    1. `[اطلاعات و آمار مربوط به شبکه را نگه داری میکند]`
    1. `[بار متوسط بر روی سیستم از نظر IO و CPU را نشان میدهد.]`
    1. `[تعداد interrupt ها را به ازای هر پردازنده نشان میدهد]`
    1. `[شامل پورت های رجیستر شده و در حال استفاده می باشد.]`
    1. `[شامل بایل سیستم هایی است که هسته سیستم عامل از آنها پشتیبانی میکند.]`
    1. `[اطلاعات مربوط به پردازنده را نشان میدهد.]`
    1. `[شامل آرگومان هایی است که به هسته در زمان شروع به کار پاس داده میشود.]`

- [ ] Place your source code for a program that shows details of processor:
    - [ ] `[![5](https://user-images.githubusercontent.com/33892567/184643423-5f190870-6d1c-426f-b27d-9cc00fe7b8cb.PNG)
]`

- [ ] Place your source code for a program that shows details of memory management sub-system:
    - [ ] `[![6](https://user-images.githubusercontent.com/33892567/184644700-d353228c-8972-4284-ba40-62a2978f3727.PNG)
]`

- [ ] Write your description about five important files at /proc/sys/kernel:
    - [ ] `[threads-max: بیشینه تعداد ریسه هایی که میتوان توسط دستور فورک ایجاد کرد]`
    - [ ] `[فایل panic_on_oops: رفتار هسته را زمانی که با یک باگ یا مشکل مواجه میشود مشخص میکند]`
    - [ ] `[فایل pid_max: بیشینه مقدار pid را مشخص میکند به این ترتیب که یک پردازه مقدار pid_max و مقادیر بیشتر از آن را نمیتواند داشته باشد]`
    - [ ] `[مقدار shmall بیشینه مقدار حافظه اشتراکی در سیستم عامل را مشخص میکند]`
    - [ ] `[مقدار ostype و osrelease نوع سیستم عامل و نسخه آن را مشخص میکند.]`

- [ ] Write your description about /proc/self file
    - [ ] `[لینکی به پردازه در حال اجرا را به دست میدهد و باعث میشود پردازه بدون داشتن شماره پردازه اطلاعات مورد نیاز خود را بدست آورد]`


## Source Code Submission

please submit all your codes in a zip file

 - [ [code.zip](https://github.com/Sharif-OS-Lab/session-3-4/files/9337648/code.zip)
] `Zip File HERE`
