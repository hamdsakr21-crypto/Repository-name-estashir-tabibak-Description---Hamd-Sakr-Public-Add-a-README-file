# Repository-name-estashir-tabibak-Description---Hamd-Sakr-Public-Add-a-README-file
تطبيق استشارات طبيقه وتقديم  نصائح وتحليل شكوى المريض، كما يمكن قراءة التحاليل الطبيه والاشاعات ورسم القلب 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>استشير طبيبك</title>
<script src="https://sdk.minepi.com/pi-sdk.js"></script>
<style>
body{font-family:tahoma;background:#eef6ff;margin:0;padding:12px}
.card{background:white;border-radius:22px;padding:14px;margin-bottom:14px;box-shadow:0 6px 18px rgba(0,0,0,.12)}
.banner{width:100%;border-radius:22px}
.logo{width:130px;height:130px;border-radius:50%;border:4px solid #4CAF50;display:block;margin:0 auto 10px}
.btn{background:#43A047;color:white;padding:14px;border:none;border-radius:14px;width:100%;font-size:18px;font-weight:bold;margin-top:8px}
.btn2{background:#1E88E5}
</style>
</head>
<body>

<div class="card" style="padding:0;overflow:hidden">
<img src="banner.jbg.jpg" class="banner">
</div>

<div class="card" style="text-align:center">
<img src="logo.jbg.jpg" class="logo">
<h2>أهلاً بيك في استشير طبيبك 👩‍⚕️</h2>
<p>برعاية حمد صقر - رعاية صحية موثوقة</p>
<img src="inside.jbg.jpg" style="width:100%;border-radius:16px;margin:10px 0">
<button class="btn" onclick="Pi.authenticate(['username'], a=>alert('أهلاً '+a.user.username))">🔐 تسجيل دخول بـ Pi</button>
<button class="btn btn2" onclick="alert('جاهز! ارفع التحليل')">🩺 ابدأ الاستشارة</button>
<p style="font-size:11px;color:gray;margin-top:10px">تنبيه: المحتوى تثقيفي فقط وليس تشخيص طبي</p>
</div>

<script>Pi.init({version:"2.0"})</script>
</body>
</html>
