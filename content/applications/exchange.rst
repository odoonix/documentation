========
Exchange
========
TODO : sanaz, 2024: translate

TODO: sanaz, 2024: create links

Moonsun Exchange برنامه ای برای مدیریت spot در یک فروشگاه صرافی است. با کمک این برنامه می توانید با توجه به نیاز شرکت و قوانین کشور شرکت، گزارش های مربوطه را دریافت کنید.
Moonsun Exchange شامل بخش های تماس، کاربران، spot، حسابداری، پرتال، گزارش و داشبورد است که در زیر به تفصیل توضیح داده شده است.

شروع کنید
----------

در اولین گام برنامه MoonSunExchange را نصب کنید .

.. note::
   برای نصب میتوانید از این لینک کمک بگیرید

در گام دوم یک spot بسازید. منظور از spot یک حواله است که طی آن مقداری وجه نقد با یک ارز به ارز دیگری تبدیل میشود
انواع حواله به شرح زیر است.

- Transfer : زمانی که دو طرف یک حواله (مشتری و ذینفع )‌ یک نفر باشد.
- Exchange : زمانی که دو طرف یک حواله (مشتری و ذینفع )‌ متفاوت باشد.

Customer و beneficiary را تعریف کنید. 
- customer : فردی است که به صرافی شما مراجعه کرده و مقداری وجه نقد را در اختیار شما قرار داده است. 
- beneficaiy : فردی است که قرار است همان وجه نقد را با ارز دیگری دریافت کند.

.. note::
  برای ساخت customer و beneficiary به این لینک مراجعه کنید.

در صورت انتخاب customer و beneficiary حساب های بانکی آن ها برای شما فعال میشود و شما میتوانید حساب بانکی مد نظر خود را انتخاب کنید.

هر spot می تواند بر اساس یک Quotation باشد که قبلاً در برنامه sale تولید شده است
اگر Quotation ای بسازید که مشتری آن همان مشتری spotباشد میتوانید از این گزینه استفاده کنید .

.. note::
    To create a quotation, you can use `this link <https://www.odoo.com/documentation/17.0/applications/sales/sales/send_quotations/quote_template.html>`_

در ادامه میتوانید برای spot خود دلیل، کامنت و توضیحات اضافه کنید و بر اساس اهمیت spot به آن ستاره دهید.

بخش اصلی یک حواله تعیین مقدار ارز ورودی و خروجی است. برای اینکار از تب transaction میتوانید نوع ارز ورودی و خروجی و میزان آن را مشخص کنید. 

.. note::
    In order to continue working, it is necessary to have another currency active in addition to the company's currency. To manage active currencies in Udo, refer to `this link <https://www.odoo.com/documentation/17.0/applications/finance/accounting/get_started/multi_currency.html>`_

.. note::
   جزئیات بخش transactionدر این لینک قرار دارد .

تبریک میگویم شما یک spot را با موفقیت ثبت کردید. spot شما در مرحله draft قرار دارد جهت اطلاع از مراحل یک spot و confirm کردن آن به این لینک مراجعه کنید.


.. toctree::
    exchange/contacts/contacts_details
    exchange/users/users_details
    exchange/spot/spot_details
    exchange/accounting/accounting_details
    exchange/reports/reports_details
    exchange/portal/portal_details
    exchange/dashboard/dashboard_details
    exchange/website/website_details



