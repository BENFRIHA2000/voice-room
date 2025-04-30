<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>غرفة الدردشة الصوتية</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #fff;
      text-align: center;
      padding: 40px;
    }
    .room {
      background-color: #1e1e1e;
      border-radius: 10px;
      padding: 30px;
      max-width: 500px;
      margin: auto;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.1);
    }
    .mic-btn {
      margin-top: 20px;
      padding: 15px 30px;
      font-size: 18px;
      border: none;
      border-radius: 30px;
      background-color: #4caf50;
      color: white;
      cursor: pointer;
    }
    .mic-btn:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="room">
    <h2>مرحبا بك في غرفة الصوت</h2>
    <p>اضغط على الميكروفون للانضمام</p>
    <button class="mic-btn" onclick="startVoice()">تشغيل الميكروفون</button>
  </div>

  <script>
    function startVoice() {
      alert("تم تفعيل الميكروفون (وهمياً). يمكنك الآن إضافة الاتصال بـ Agora أو WebRTC!");
    }
  </script>
</body>
</html>
