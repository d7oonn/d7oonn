<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة تنار العقارية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #007BFF;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            background-color: #fff;
            padding: 20px;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
        }
        .logo {
            max-width: 100px;
            margin-bottom: 20px;
        }
        .links a {
            display: block;
            color: #007BFF;
            text-decoration: none;
            margin: 5px 0;
        }
        .footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            color: #333;
        }
        .form-group input, .form-group select {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo">ضع الشعار</div>
        <h1> شركة تنار العقارية</h1>
    </div>
    <div class="container">
        <h2>مرحبًا بك في شركة تنار العقارية </h2>
        <p>حقق حلمك بامتلاك منزل العمر مع حلولنا المتنوعة في التمويل العقاري.</p>
        <div class="links">
            <a href="YOUR_LINK_1">رابط 1</a>
            <a href="YOUR_LINK_2">رابط 2</a>
            <a href="YOUR_LINK_3">رابط 3</a>
            <a href="https://wa.me/message/MMHXZBCJCJQNP1">تواصل معنا عبر واتساب</a>
        </div>
        <form action="process_form.php" method="post">
            <div class="form-group">
                <label for="full-name">الاسم الكامل</label>
                <input type="text" id="full-name" name="full-name" required>
            </div>
            <div class="form-group">
                <label for="salary">الراتب</label>
                <input type="text" id="salary" name="salary" required>
            </div>
            <div class="form-group">
                <label for="phone">رقم الهاتف</label>
                <input type="text" id="phone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="sector">قطاع العمل</label>
                <select id="sector" name="sector" required>
                    <option value="الحكومي">الحكومي</option>
                    <option value="الخاص">الخاص</option>
                    <option value="العسكري">العسكري</option>
                    <option value="شبه الحكومي">شبه الحكومي</option>
                </select>
            </div>
            <div class="form-group">
                <label for="bank">البنك</label>
                <select id="bank" name="bank" required>
                    <option value="البنك الأهلي">البنك الأهلي</option>
                    <option value="بنك الرياض">بنك الرياض</option>
                    <option value="بنك البلاد">بنك البلاد</option>
                    <option value="البنك السعودي الفرنسي">البنك السعودي الفرنسي</option>
                    <option value="بنك الجزيرة">بنك الجزيرة</option>
                    <option value="البنك العربي">البنك العربي</option>
                    <option value="البنك السعودي للاستثمار">البنك السعودي للاستثمار</option>
                    <option value="بنك ساب">بنك ساب</option>
                    <option value="بنك الإنماء">بنك الإنماء</option>
                    <option value="بنك سامبا">بنك سامبا</option>
                </select>
            </div>
            <button type="submit">إرسال</button>
        </form>
    </div>
    <div class="footer">
        <p>حقوق الطبع والنشر &copy; 2024 شركة تنار العقارية. جميع الحقوق محفوظة.</p>
    </div>
</body>
</html>
