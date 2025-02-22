<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>طلب تسجيل الإنترنت الفضائي</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>طلب تسجيل الإنترنت الفضائي</h1>
        <form id="registrationForm">
            <label for="fullName">الاسم الثلاثي:</label>
            <input type="text" id="fullName" name="fullName" required>

            <label for="phone">رقم الهاتف:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="address">عنوان المنزل:</label>
            <input type="text" id="address" name="address" required>

            <button type="submit">إرسال الطلب</button>
        </form>
    </div>

    <script src="script.js"></script>
</body>
</html>
