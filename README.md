<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>تحذير اختراق</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: black;
        }
        .container {
            position: relative;
            text-align: center;
        }
        .warning {
            position: absolute;
            top: 20%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: red;
            font-size: 24px;
            font-weight: bold;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }
    </style>
    <script>
        window.onload = function() {
            alert("🚨 تحذير: تم تسجيل الدخول إلى جهازك! 🚨\n\nهناك شخص غير مصرح له يحاول الوصول إلى بياناتك.\n\nيرجى التحقق من أمان جهازك على الفور!");
        }
    </script>
</head>
<body>
    <div class="container">
        <img src="https://via.placeholder.com/600x400" alt="تحذير" />
        <div class="warning">🚨 تم اختراق جهازك! 🚨</div>
    </div>
</body>
</html>
