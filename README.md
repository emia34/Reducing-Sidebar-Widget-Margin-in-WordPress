# Reducing-Sidebar-Widget-Margin-in-WordPress
When working with WordPress themes, you may notice that the default spacing between widgets—or between a widget title and its content—is larger than you prefer. Fortunately, you can easily reduce this extra space by adding a small CSS snippet to your site.
اگر در قالب سایت وردپرسی شما، بین هر ابزارک فضای خالی زیادی وجود دارد و قابلیت کم کردن این فضا در قالب سایت وجود ندارد روشی که میگویم را انجام بدهید.

برای کم کردن این فاصله باید از یک کد استفاده کنید که این کد را باید در بخش کدهای سفارشی CSS بگذارید.

به بخش سفارشی سازی بروید، سپس در بخش css اضافی، کد زیر را قرار بدهید:

/* فاصله بین ابزارک‌ها */

.sidebar .widget,

.widget-area .widget,

aside .widget {

margin-bottom: 15px !important;

}

مشکل برطرف خواهد شد.
