<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NIDAL-AI - نسخ سهل</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }
        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }
        .header h1 {
            font-size: 28px;
            margin-bottom: 10px;
        }
        .header p {
            font-size: 16px;
            opacity: 0.9;
        }
        .button-section {
            padding: 20px;
            text-align: center;
            background: #f8f9fa;
            border-bottom: 2px solid #e0e0e0;
        }
        .copy-btn {
            background: #4CAF50;
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 16px;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: bold;
            margin: 5px;
        }
        .copy-btn:hover {
            background: #45a049;
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(76, 175, 80, 0.3);
        }
        .copy-btn:active {
            transform: scale(0.98);
        }
        .content {
            padding: 30px;
            max-height: 600px;
            overflow-y: auto;
            background: white;
        }
        .content textarea {
            width: 100%;
            height: 500px;
            padding: 15px;
            border: 2px solid #667eea;
            border-radius: 8px;
            font-family: 'Courier New', monospace;
            font-size: 14px;
            resize: vertical;
            background: #f5f5f5;
        }
        .info-box {
            background: #e3f2fd;
            border-right: 5px solid #667eea;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
            line-height: 1.8;
        }
        .success-message {
            display: none;
            background: #4CAF50;
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin: 10px 0;
            text-align: center;
            animation: slideIn 0.3s ease;
        }
        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .footer {
            background: #f8f9fa;
            padding: 20px;
            text-align: center;
            color: #666;
            border-top: 2px solid #e0e0e0;
        }
        .dev-info {
            background: #fff3e0;
            border-right: 5px solid #ff9800;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
        }
        .dev-info h3 {
            color: #ff9800;
            margin-bottom: 10px;
        }
        .dev-info p {
            margin: 8px 0;
            line-height: 1.8;
        }
        .feature-list {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin: 20px 0;
        }
        .feature-item {
            background: #f5f5f5;
            padding: 15px;
            border-radius: 8px;
            border-right: 4px solid #667eea;
        }
        .feature-item strong {
            color: #667eea;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🚀 NIDAL-AI | My.AI Project Information</h1>
            <p>معلومات المشروع - سهل النسخ والاستخدام</p>
        </div>

        <div class="button-section">
            <button class="copy-btn" onclick="copyAllText()">📋 انسخ جميع المعلومات</button>
            <button class="copy-btn" onclick="copyDevInfo()">👨‍💼 انسخ معلومات المطور فقط</button>
            <button class="copy-btn" onclick="copyContact()">📞 انسخ معلومات التواصل</button>
            <div id="successMsg" class="success-message">✅ تم النسخ بنجاح!</div>
        </div>

        <div class="content">
            <!-- معلومات المطور -->
            <div class="dev-info">
                <h3>👨‍💼 معلومات المطور | DEVELOPER INFORMATION</h3>
                <p><strong>الاسم الكامل | Full Name:</strong> NIDAL WATFA</p>
                <p><strong>البريد الإلكتروني | Email:</strong> nidalwatfa99@gmail.com</p>
                <p><strong>رقم الهاتف | Phone:</strong> +963 99 885 4450</p>
                <p><strong>ORCID Profile:</strong> https://orcid.org/0009-0003-2462-6630</p>
                <p><strong>ORCID ID:</strong> 0009-0003-2462-6630</p>
            </div>

            <!-- ملخص المشروع -->
            <div class="info-box">
                <h3>📋 ملخص المشروع | PROJECT SUMMARY</h3>
                <p><strong>اسم المشروع | Project Name:</strong> My.AI</p>
                <p><strong>الإصدار | Version:</strong> 1.0.0</p>
                <p><strong>تاريخ الإطلاق | Release Date:</strong> September 26, 2024</p>
            </div>

            <!-- الميزات -->
            <h3>✨ الميزات الرئيسية | KEY FEATURES</h3>
            <div class="feature-list">
                <div class="feature-item">
                    <strong>🧮 الحاسبة العلمية</strong><br>
                    Scientific Calculator
                </div>
                <div class="feature-item">
                    <strong>📐 محرر المعادلات</strong><br>
                    Math Editor (LaTeX)
                </div>
                <div class="feature-item">
                    <strong>📊 الرسوم البيانية</strong><br>
                    Data Visualization
                </div>
                <div class="feature-item">
                    <strong>🗺️ الخرائط التفاعلية</strong><br>
                    Interactive Maps
                </div>
                <div class="feature-item">
                    <strong>🔄 محول الوحدات</strong><br>
                    Unit Converter
                </div>
                <div class="feature-item">
                    <strong>💬 المحادثة الذكية</strong><br>
                    AI Chat Interface
                </div>
                <div class="feature-item">
                    <strong>🎤 ميزات الصوت</strong><br>
                    Voice Features
                </div>
                <div class="feature-item">
                    <strong>📝 دعم Markdown</strong><br>
                    Markdown Support
                </div>
                <div class="feature-item">
                    <strong>🎨 نظام المواضع</strong><br>
                    Dark/Light Theme
                </div>
                <div class="feature-item">
                    <strong>🌍 دعم اللغات</strong><br>
                    Arabic & English
                </div>
            </div>

            <!-- الملفات -->
            <div class="info-box">
                <h3>📦 الملفات المسلمة | DELIVERABLES</h3>
                <p><strong>1. NIDAL-AI-My.AI-Application.html</strong> - التطبيق الكامل (76 KB)</p>
                <p><strong>2. README.md</strong> - دليل احترافي (15 KB)</p>
                <p><strong>3. LICENSE</strong> - ترخيص MIT (2.6 KB)</p>
                <p><strong>4. DESCRIPTION-AR.md</strong> - وصف عربي (21 KB)</p>
                <p><strong>5. DESCRIPTION-EN.md</strong> - وصف إنكليزي (25 KB)</p>
                <p><strong>6. FILES-GUIDE.txt</strong> - دليل الملفات (17 KB)</p>
                <p><strong>7. README-AR.txt</strong> - ملخص عربي (3.2 KB)</p>
                <p><strong>8. PROJECT-CONTENTS.txt</strong> - هيكل المشروع (6.6 KB)</p>
                <p><strong>9. SUMMARY.txt</strong> - ملخص شامل (17 KB)</p>
                <p><strong>10. COPY-EASY.txt</strong> - نسخ سهل (30 KB)</p>
            </div>

            <!-- متطلبات النظام -->
            <div class="info-box">
                <h3>⚙️ متطلبات النظام | SYSTEM REQUIREMENTS</h3>
                <p><strong>المتصفح | Browser:</strong> Chrome 60+, Firefox 55+, Safari 12+, Edge 79+</p>
                <p><strong>نظام التشغيل | OS:</strong> Windows 7+, macOS 10.12+, Linux</p>
                <p><strong>الذاكرة | RAM:</strong> 512 MB (موصى به 2GB+)</p>
                <p><strong>التخزين | Storage:</strong> 100 MB</p>
            </div>

            <!-- طريقة الاستخدام -->
            <div class="info-box">
                <h3>🚀 طريقة الاستخدام | HOW TO USE</h3>
                <p><strong>الخطوة 1:</strong> حمّل ملف NIDAL-AI-My.AI-Application.html</p>
                <p><strong>الخطوة 2:</strong> انقر نقراً مزدوجاً على الملف</p>
                <p><strong>الخطوة 3:</strong> سيفتح في متصفحك مباشرة</p>
                <p><strong>الخطوة 4:</strong> اختر اللغة والمظهر من الإعدادات</p>
                <p><strong>الخطوة 5:</strong> ابدأ باستخدام الميزات</p>
            </div>

            <!-- الترخيص -->
            <div class="info-box">
                <h3>⚖️ الترخيص | LICENSE</h3>
                <p><strong>نوع الترخيص:</strong> MIT License</p>
                <p><strong>الاستخدام:</strong> مفتوح المصدر وحر تماماً</p>
                <p><strong>المتطلب الوحيد:</strong> الإشارة للمطور (NIDAL WATFA)</p>
            </div>

            <!-- الأمان -->
            <div class="info-box">
                <h3>🔒 الأمان والخصوصية | SECURITY & PRIVACY</h3>
                <p>✅ جميع البيانات محلية - All data local</p>
                <p>✅ بدون إرسال للخادم - No server upload</p>
                <p>✅ بدون تتبع - No tracking</p>
                <p>✅ يعمل بدون إنترنت - Works offline</p>
                <p>✅ مفتوح المصدر - Open source</p>
            </div>

            <!-- معلومات الدعم -->
            <div class="dev-info">
                <h3>📞 معلومات الدعم والتواصل | SUPPORT INFORMATION</h3>
                <p><strong>📧 البريد الإلكتروني | Email:</strong></p>
                <p style="padding-right: 20px;">nidalwatfa99@gmail.com</p>
                <p><strong>📱 الهاتف/واتس | Phone/WhatsApp:</strong></p>
                <p style="padding-right: 20px;">+963 99 885 4450</p>
                <p><strong>🔗 ملف ORCID | ORCID Profile:</strong></p>
                <p style="padding-right: 20px;">https://orcid.org/0009-0003-2462-6630</p>
            </div>

            <!-- الإحصائيات -->
            <div class="info-box">
                <h3>📊 إحصائيات المشروع | PROJECT STATISTICS</h3>
                <p>عدد الملفات: 10 | Number of Files: 10</p>
                <p>الحجم الإجمالي: 200+ KB | Total Size: 200+ KB</p>
                <p>أسطر التوثيق: 2,150+ | Documentation Lines: 2,150+</p>
                <p>أسطر الأكواد: 5,000+ | Lines of Code: 5,000+</p>
                <p>مكونات الواجهة: 40+ | UI Components: 40+</p>
                <p>الدوال: 150+ | Functions: 150+</p>
                <p>اللغات: 2 | Languages: 2</p>
            </div>
        </div>

        <div class="footer">
            <p>✨ صُنع بـ ❤️ من قبل نضال وتفا | Made with ❤️ by NIDAL WATFA</p>
            <p>الإصدار 1.0.0 | Version 1.0.0 | 26 سبتمبر 2024 | September 26, 2024</p>
        </div>
    </div>

    <script>
        function showSuccess() {
            const msg = document.getElementById('successMsg');
            msg.style.display = 'block';
            setTimeout(() => {
                msg.style.display = 'none';
            }, 3000);
        }

        function copyAllText() {
            const text = `
================================================================================
                    NIDAL-AI | My.AI PROJECT INFORMATION
================================================================================

معلومات المطور | DEVELOPER INFORMATION
================================================================================
الاسم: NIDAL WATFA
البريد: nidalwatfa99@gmail.com
الهاتف: +963 99 885 4450
ORCID: https://orcid.org/0009-0003-2462-6630
ORCID ID: 0009-0003-2462-6630

================================================================================
ملخص المشروع | PROJECT SUMMARY
================================================================================
اسم المشروع: My.AI
الإصدار: 1.0.0
تاريخ الإطلاق: 26 سبتمبر 2024 | September 26, 2024

================================================================================
الميزات الرئيسية | KEY FEATURES
================================================================================
🧮 الحاسبة العلمية | Scientific Calculator
📐 محرر المعادلات | Math Editor (LaTeX)
📊 الرسوم البيانية | Data Visualization
🗺️ الخرائط التفاعلية | Interactive Maps
🔄 محول الوحدات | Unit Converter
💬 المحادثة الذكية | AI Chat Interface
🎤 ميزات الصوت | Voice Features
📝 دعم Markdown | Markdown Support
🎨 نظام المواضع | Dark/Light Theme
🌍 دعم اللغات | Arabic & English

================================================================================
الملفات المسلمة | DELIVERABLES (10 FILES)
================================================================================
1. NIDAL-AI-My.AI-Application.html - التطبيق (76 KB)
2. README.md - دليل احترافي (15 KB)
3. LICENSE - ترخيص MIT (2.6 KB)
4. DESCRIPTION-AR.md - وصف عربي (21 KB)
5. DESCRIPTION-EN.md - وصف إنكليزي (25 KB)
6. FILES-GUIDE.txt - دليل الملفات (17 KB)
7. README-AR.txt - ملخص عربي (3.2 KB)
8. PROJECT-CONTENTS.txt - هيكل المشروع (6.6 KB)
9. SUMMARY.txt - ملخص شامل (17 KB)
10. COPY-EASY.txt - نسخ سهل (30 KB)

================================================================================
متطلبات النظام | SYSTEM REQUIREMENTS
================================================================================
المتصفح: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
نظام التشغيل: Windows 7+, macOS 10.12+, Linux
الذاكرة: 512 MB (موصى به 2GB+)
التخزين: 100 MB

================================================================================
طريقة الاستخدام | HOW TO USE
================================================================================
1. حمّل ملف NIDAL-AI-My.AI-Application.html
2. انقر نقراً مزدوجاً على الملف
3. سيفتح في متصفحك مباشرة
4. اختر اللغة والمظهر من الإعدادات
5. ابدأ باستخدام الميزات

================================================================================
التقنيات المستخدمة | TECHNOLOGY STACK
================================================================================
Frontend: React.js, Tailwind CSS, KaTeX, Plotly.js, Three.js, Leaflet.js
Backend: Python 3.x, Flask/FastAPI
Databases: LocalStorage (Browser)

================================================================================
الترخيص | LICENSE
================================================================================
نوع الترخيص: MIT License
الاستخدام: مفتوح المصدر وحر
المتطلب: الإشارة للمطور (NIDAL WATFA)

================================================================================
الأمان والخصوصية | SECURITY & PRIVACY
================================================================================
✅ جميع البيانات محلية
✅ بدون إرسال للخادم
✅ بدون تتبع
✅ يعمل بدون إنترنت
✅ مفتوح المصدر

================================================================================
معلومات الدعم | SUPPORT INFORMATION
================================================================================
📧 البريد: nidalwatfa99@gmail.com
📱 الهاتف/واتس: +963 99 885 4450
🔗 ORCID: https://orcid.org/0009-0003-2462-6630

================================================================================
إحصائيات المشروع | PROJECT STATISTICS
================================================================================
عدد الملفات: 10
الحجم الإجمالي: 200+ KB
أسطر التوثيق: 2,150+
أسطر الأكواد: 5,000+
مكونات الواجهة: 40+
الدوال: 150+
اللغات: 2 (عربي + إنكليزي)

================================================================================
شكراً لاستخدامك My.AI | Thank You for Using My.AI
================================================================================

صُنع بـ ❤️ من قبل نضال وتفا | Made with ❤️ by NIDAL WATFA
الإصدار 1.0.0 | Version 1.0.0
26 سبتمبر 2024 | September 26, 2024

================================================================================
            `;
            navigator.clipboard.writeText(text).then(() => {
                showSuccess();
            });
        }

        function copyDevInfo() {
            const text = `الاسم: NIDAL WATFA
البريد: nidalwatfa99@gmail.com
الهاتف: +963 99 885 4450
ORCID: https://orcid.org/0009-0003-2462-6630`;
            navigator.clipboard.writeText(text).then(() => {
                showSuccess();
            });
        }

        function copyContact() {
            const text = `📧 البريد الإلكتروني: nidalwatfa99@gmail.com
📱 الهاتف/واتس: +963 99 885 4450
🔗 ORCID: https://orcid.org/0009-0003-2462-6630`;
            navigator.clipboard.writeText(text).then(() => {
                showSuccess();
            });
        }
    </script>
</body>
</html>
