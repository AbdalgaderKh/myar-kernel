# نواة MyAR

![Build Status](https://github.com/AbdalgaderKh/myar-kernel/actions/workflows/build.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

نواة نظام تشغيل مفتوحة المصدر مستوحاة من Windows XP، تهدف إلى توفير بيئة تعليمية وتجريبية للمطورين المهتمين بأنظمة التشغيل.

## المميزات

- دعم تعدد المعالجات (SMP)
- نظام ملفات FAT32 متكامل
- واجهة مستخدم رسومية أساسية
- تصميم معياري وقابل للتوسعة

## البدء السريع

```bash
git clone https://github.com/AbdalgaderKh/myar-kernel.git
cd myar-kernel
make && make run
```

## متطلبات البناء

```bash
sudo apt-get install build-essential nasm grub-pc-bin qemu-system-x86
```

## المساهمة

نرحب بجميع المساهمين! الرجاء قراءة [CONTRIBUTING.md](CONTRIBUTING.md) قبل إرسال Pull Request.

## الرخصة

هذا المشروع مرخص تحت رخصة MIT. انظر [LICENSE](LICENSE) للمزيد من التفاصيل.
