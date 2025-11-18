# Use Case Diagram — کلینیک دامپزشکی

```mermaid
usecaseDiagram
    actor "پذیرش" as Reception
    actor "دامپزشک" as Doctor
    actor "صاحب حیوان" as Owner

    Reception --> (ثبت نوبت)
    Reception --> (ثبت حیوان جدید)
    Reception --> (صدور صورتحساب)

    Doctor --> (مشاهده پرونده حیوان)
    Doctor --> (ثبت سوابق درمان)
    Doctor --> (نوشتن نسخه)

    Owner --> (رزرو نوبت)
    Owner --> (پرداخت هزینه‌ها)
