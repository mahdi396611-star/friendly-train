<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <title>وب اپ تلگرام</title>
</head>
<body>
    <h1>سلام! 🎉 وب اپ شما آماده است</h1>
    <button id="sendBtn">ارسال پیام به ربات</button>

    <script>
        // دسترسی به وب اپ تلگرام
        const tg = window.Telegram.WebApp;

        document.getElementById('sendBtn').addEventListener('click', () => {
            tg.sendData("سلام از وب اپ!");
            alert("پیام ارسال شد!");
        });
    </script>
</body>
</html>
