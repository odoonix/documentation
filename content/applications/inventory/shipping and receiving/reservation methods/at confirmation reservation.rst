:nosearch:
:show-content:
:hide-page-toc:
:show-toc:


=================================
شیوه ی تایید اندوخته
=================================

روش رزرو هنگام تایید، محصولات را تنها زمانی رزرو می کند که سفارش فروش (SO) تایید شود، و اگر موجودی کافی از محصولات موجود در  :abbr:`SO (Sales Order)` موجود باشد.



پیکربندی
----------------------------------------
برای تنظیم روش رزرو روی تأیید، به برنامه :menuselection:`انبار --> پیکربندی --> انواع عملیات` بروید. سپس، نوع عملیات مورد نظر را برای پیکربندی انتخاب کنید، یا با کلیک بر روی جدید، یک مورد جدید ایجاد کنید.

در برگه عمومی در فرم نوع عملیات، قسمتروش رزرو  را پیدا کرده و در تأیید را انتخاب کنید.


.. image:: ./img/reservationmethods/r1.jpg
    :align: center
    :alt: انبار

جریان کار
---------------------------------------------------
برای مشاهده عملکرد **روش رزرو** در تأیید، با رفتن به برنامه فروش ‣ جدید، یک سفارشفروش  جدید ایجاد کنید.

در قسمت مشتری یک مشتری اضافه کنید. سپس، در تب خطوط سفارش، روی افزودن یک محصول کلیک کنید و محصولی را برای افزودن به پیش فاکتور از منوی کشویی انتخاب کنید. در نهایت در ستون تعداد مقدار مورد نظر محصول را برای فروش تنظیم کنید.
پس از آماده شدن، برای تأیید سفارش فروش، روی تأیید کلیک کنید.

روی نماد 📈 (نمودار منطقه) در خط محصول کلیک کنید تا راهنمای ابزار در دسترس بودن محصول نشان داده شود، که تعداد واحدهای رزرو شده برای این سفارش را نشان می دهد.

.. image:: ./img/reservationmethods/r2.jpg
    :align: center
    :alt: انبار


.. note::
    اگر مقدار موجودی کافی برای محصول موجود در(سفارش فروش) SO وجود نداشته باشد، نماد 📈 (گراف ناحیه) به جای سبز، قرمز است.

    به‌جای فاش کردن تعداد واحدهای رزرو شده برای سفارش، راهنمای ابزار در درسترس، موجود را می‌خواند و تعداد واحدهای موجود (مثلاً 0 واحد) را نشان می‌د

    .. image:: ./img/reservationmethods/r3.jpg
        :align: center
        :alt: انبار


.. admonition:: گزارش پیش بینی شده

   برای مشاهده همه عواملی که بر رزرو محصول تأثیر می گذارد، روی پیکان پیوند داخلی مشاهده پیش بینی کلیک کنید تا داشبورد گزارش پیش بینی شده را مشاهده کنید.

   گزارش پیش‌بینی‌شده اطلاعات پیش‌بینی محصول(های) موجود در سفارش فروش را نمایش می‌دهد. یعنی، هر گونه رسید زنده از محصول، و هر گونه سفارش فروش فعال، که در ستون استفاده شده توسط فهرست شده است. نحوه انجام هر سفارش را در ستون شارژ مجدد مشاهده کنید.

   علاوه بر این، مقدار پیش‌بینی‌شده در بالای صفحه با اضافه کردن مقدار موجود  و ورودی  و کم کردن مقدار خروجی، مانند شکل زیر محاسبه می‌شود:

   .. image:: ./img/reservationmethods/r4.jpg
        :align: center
        :alt: انبار

   اگر یک سفارش باید نسبت به سفارش دیگر اولویت داشته باشد، روی دکمه Unreserve در خط سفارش مربوطه در ستون شارژ مجدد کلیک کنید.   


برای تحویل محصولات روی دکمه هوشمند تحویل در بالای فرم سفارش فروش کلیک کنید. برای تأیید اینکه رزرو به درستی انجام شده است، مطمئن شوید که قسمت «در دسترس بودن محصول» موجود است (در متن سبز رنگ)، و اعداد موجود در ستون‌های تقاضا و مقدار مطابقت دارند.


.. image:: ./img/reservationmethods/r5.jpg
    :align: center
    :alt: انبار

پس از آماده شدن، روی تایید اعتبار کلیک کنید.   


.. seealso::
   - :doc:`manual reservation`
   - :doc:`before scheduled date reservation`