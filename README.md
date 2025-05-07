<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ssbdin - منصة الخدمات الرقمية</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 1rem;
      text-align: center;
      border-bottom-left-radius: 25px;
      border-bottom-right-radius: 25px;
    }
    section {
      padding: 2rem 1rem;
      text-align: center;
    }
    .btn {
      display: inline-block;
      padding: 0.8rem 1.5rem;
      margin: 0.5rem;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 10px;
      text-decoration: none;
      font-size: 1rem;
    }
    .features, .products-section, .payment-section, .delivery-section {
      margin-top: 1rem;
    }
    .feature, .product-category, .payment-form, .delivery-box {
      background: white;
      padding: 1rem;
      border-radius: 12px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      margin: 1rem auto;
      max-width: 400px;
    }
    input, select, button {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1rem;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
    }
    .product {
      background: #f0f0f0;
      padding: 1rem;
      border-radius: 8px;
      text-align: start;
      margin-top: 1rem;
    }
    .product h4, .product p {
      margin: 0.3rem 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>مرحبا بك في ssbdin</h1>
    <p>منصة الخدمات الرقمية المصغرة</p>
  </header>  <section class="intro">
    <h2>خدمات احترافية بثمن مناسب</h2>
    <p>اكتشف منتجات رقمية متنوعة مقدمة من محترفين.</p>
    <a href="#login" class="btn">تسجيل الدخول</a>
    <a href="#products" class="btn">تصفح المنتجات</a>
    <a href="#payment" class="btn">الدفع</a>
    <a href="#delivery" class="btn">استلام المنتج</a>
  </section>  <section class="features">
    <div class="feature">
      <h3>سهولة الاستخدام</h3>
      <p>تصميم مخصص للموبايل لتجربة مريحة وسريعة.</p>
    </div>
    <div class="feature">
      <h3>دفع آمن</h3>
      <p>بايبال و بطائق الائتمان لتسوق بثقة.</p>
    </div>
    <div class="feature">
      <h3>تسليم فوري</h3>
      <p>تحصل على منتجك الرقمي مباشرة بعد الدفع.</p>
    </div>
  </section>  <section class="login-form" id="login">
    <h2>تسجيل الدخول</h2>
    <form>
      <input type="email" placeholder="البريد الإلكتروني" required>
      <input type="password" placeholder="كلمة المرور" required>
      <button type="submit">دخول</button>
    </form>
  </section>  <section class="products-section" id="products">
    <h2>المنتجات الرقمية</h2>
    <div class="product-category">
      <h3>كتب رقمية</h3>
      <div class="product">
        <h4>دليل العمل الحر</h4>
        <p>وصف: كتاب يرشدك لبداية مشوارك كمستقل</p>
        <p>السعر: 49 درهم</p>
      </div>
    </div>
    <div class="product-category">
      <h3>قصص قصيرة</h3>
      <div class="product">
        <h4>قصة الهروب من الواقع</h4>
        <p>وصف: قصة قصيرة مستوحاة من أحداث واقعية</p>
        <p>السعر: 29 درهم</p>
      </div>
    </div>
    <div class="product-category">
      <h3>بودكاست</h3>
      <div class="product">
        <h4>نصائح لرواد الأعمال</h4>
        <p>وصف: تسجيل صوتي حول إدارة المشاريع الصغيرة</p>
        <p>السعر: 19 درهم</p>
      </div>
    </div>
  </section>  <section class="payment-section" id="payment">
    <h2>الدفع</h2>
    <form class="payment-form">
      <input type="text" placeholder="الاسم الكامل" required>
      <input type="email" placeholder="البريد الإلكتروني" required>
      <select required>
        <option value="">اختر طريقة الدفع</option>
        <option value="paypal">بايبال</option>
        <option value="card">بطاقة ائتمان</option>
      </select>
      <button type="submit">تأكيد الدفع</button>
    </form>
  </section>  <section class="delivery-section" id="delivery">
    <h2>استلام المنتج</h2>
    <div class="delivery-box">
      <p>شكراً على طلبك! بعد تأكيد الدفع، يمكنك تحميل منتجك الرقمي من الرابط أدناه:</p>
      <a href="#" class="btn">تحميل المنتج</a>
      <p>سيتم إرسال نسخة من المنتج أيضاً إلى بريدك الإلكتروني.</p>
    </div>
  </section>
</body>
</html>
