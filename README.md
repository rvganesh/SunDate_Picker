SunDate Picker
=================

** کتابخونه ای برای انتخاب تاریخ شمسی در اندروید.

![](/screen-shot.jpg)


استفاده
---------

1. کتابخونه رو در برنامتون وارد کنید

2. OnDateSetListener رو در فایل جاوا خود Implement کنید

2. کد های زیر رو بنویسید

    ```java
    // ایجاد یک نمونه.
    DatePickerDialog dp = DatePickerDialog.newInstance(this, false);

    // انتخاب رنگ اصلی و فرعی
    dp.setMainColor(color);
	dp.setSecondColor(color);
	
	// کد درخواست
	dp.setRequestID(requestID);
	
	// ویبره هنگام کلیک
	dp.setVibrate(vibrate);
	
	// کمترین و بیشترین سالی که باید نمایش داده شود
	dp.setYearRange(minYear, maxYear);
	
	// انتخاب فونت
	dp.setTypeFace(typeface);
	
	// تاریخی که در ابتدا باید نمایش داده شود
	dp.setInitialDate(year, month, day);
	
	// و در آخر نمایش
	dp.show(getSupportFragmentManager(), "");
    ```

نمونه
----------

در پروژه برنامه ی نمونه ی نوشته شده که کار با این کتابخونه رو نمایش میده

برنامه هایی که از این کتابخونه استفاده می کنند
---------------

* [مکتـب](http://cafebazaar.ir/app/com.afkar.maktab)
* [COL Reminder](https://play.google.com/store/apps/details?id=com.colapps.reminder)
* از این کتابخانه استفاده می کنید؟ کافیست [به من توئیت بزنید](https://twitter.com/alireza_afkar) یا [یک ایمیل ارسال کنید](mailto:pesiran@gmail.com)

License
----------

    Copyright 2014 Alireza Afkar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
