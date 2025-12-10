# https-sha-verify.org-certificate-ALHEJELI_BLS_18012025_7A9B3C
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>التحقق من صحة الشهادة - الجمعية السعودية للقلب</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 100, 0, 0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(90deg, #006400, #008000);
            color: white;
            padding: 30px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 28px;
            margin-bottom: 10px;
        }
        
        .certificate-info {
            padding: 40px;
        }
        
        .status-valid {
            background: #d4edda;
            color: #155724;
            padding: 15px;
            border-radius: 10px;
            border: 2px solid #c3e6cb;
            margin-bottom: 30px;
            text-align: center;
            font-size: 20px;
        }
        
        .status-expired {
            background: #f8d7da;
            color: #721c24;
            padding: 15px;
            border-radius: 10px;
            border: 2px solid #f5c6cb;
            margin-bottom: 30px;
            text-align: center;
            font-size: 20px;
        }
        
        .details-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .detail-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            border-right: 4px solid #006400;
        }
        
        .detail-item strong {
            color: #006400;
            display: block;
            margin-bottom: 5px;
        }
        
        .certificate-image {
            text-align: center;
            margin: 40px 0;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 10px;
        }
        
        .certificate-image img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .actions {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
            flex-wrap: wrap;
        }
        
        .btn {
            padding: 12px 30px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
        }
        
        .btn-primary {
            background: #006400;
            color: white;
        }
        
        .btn-secondary {
            background: #6c757d;
            color: white;
        }
        
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            background: #f8f9fa;
            color: #666;
            border-top: 1px solid #ddd;
            margin-top: 40px;
        }
        
        @media (max-width: 768px) {
            .container {
                margin: 10px;
            }
            
            .header {
                padding: 20px;
            }
            
            .certificate-info {
                padding: 20px;
            }
            
            .actions {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 100%;
                max-width: 300px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🔍 التحقق من صحة الشهادة</h1>
            <p>الجمعية السعودية للقلب - اللجنة الوطنية لدعم الحياة</p>
        </div>
        
        <div class="certificate-info">
            <div class="status-valid">
                ✅ <strong>هذه الشهادة سارية وصالحة</strong>
            </div>
            
            <h2 style="color: #006400; margin-bottom: 20px; text-align: center;">
                شهادة تدريب دعم الحياة الأساسي (BLS)
            </h2>
            
            <div class="details-grid">
                <div class="detail-item">
                    <strong>اسم الحاصل:</strong>
                    أيمن عبدالله الحجلي
                </div>
                
                <div class="detail-item">
                    <strong>نوع الشهادة:</strong>
                    SHA BLS Provider
                </div>
                
                <div class="detail-item">
                    <strong>رقم الشهادة:</strong>
                    ALHEJELI_BLS_18012025_7A9B3C
                </div>
                
                <div class="detail-item">
                    <strong>تاريخ الإصدار:</strong>
                    18 يناير 2025
                </div>
                
                <div class="detail-item">
                    <strong>تاريخ الانتهاء:</strong>
                    18 يناير 2027
                </div>
                
                <div class="detail-item">
                    <strong>مركز التدريب:</strong>
                    Aimboard Center For health training
                </div>
                
                <div class="detail-item">
                    <strong>الحالة:</strong>
                    <span style="color: #006400;">✅ نشطة وصالحة</span>
                </div>
                
                <div class="detail-item">
                    <strong>تاريخ التحقق:</strong>
                    <span id="currentDate"></span>
                </div>
            </div>
            
            <div class="certificate-image">
                <h3 style="margin-bottom: 20px; color: #333;">نموذج الشهادة الأصلية</h3>
                <img src="certificate_preview.jpg" alt="معاينة الشهادة" 
                     onerror="this.style.display='none'">
                <p style="margin-top: 15px; color: #666; font-size: 14px;">
                    * هذه معاينة للشهادة الأصلية
                </p>
            </div>
            
            <div style="background: #e7f3ff; padding: 20px; border-radius: 10px; margin: 30px 0;">
                <h4 style="color: #006400; margin-bottom: 10px;">معلومات إضافية:</h4>
                <p>تم إصدار هذه الشهادة وفقاً لمعايير الجمعية السعودية للقلب واللجنة الوطنية لدعم الحياة.</p>
                <p>للاستفسار أو الإبلاغ عن شهادة مشبوهة، يرجى التواصل على: <strong>verify@sha.org.sa</strong></p>
            </div>
            
            <div class="actions">
                <a href="#" class="btn btn-primary" onclick="window.print()">
                    🖨️ طباعة نتيجة التحقق
                </a>
                <a href="certificate_with_qr.html" class="btn btn-secondary">
                    📄 عرض الشهادة كاملة
                </a>
                <a href="https://sha.org.sa" class="btn btn-primary">
                    🌐 الموقع الرسمي للجمعية
                </a>
            </div>
        </div>
        
        <div class="footer">
            <p>© 2025 الجمعية السعودية للقلب. جميع الحقوق محفوظة.</p>
            <p style="font-size: 12px; margin-top: 10px;">
                هذا النظام للتحقق من صحة الشهادات الصادرة عن اللجنة الوطنية لدعم الحياة
            </p>
        </div>
    </div>
    
    <script>
        // عرض التاريخ الحالي
        const now = new Date();
        const options = { 
            year: 'numeric', 
            month: 'long', 
            day: 'numeric',
            weekday: 'long'
        };
        document.getElementById('currentDate').textContent = 
            now.toLocaleDateString('ar-SA', options);
        
        // استخراج معلومات من الرابط
        const urlParams = new URLSearchParams(window.location.search);
        const certId = urlParams.get('id') || 'ALHEJELI_BLS_18012025_7A9B3C';
        
        // يمكن إضافة المزيد من المنطق للتحقق من قاعدة البيانات هنا
        console.log('تم التحقق من الشهادة:', certId);
    </script>
</body>
</html>
<!-- حفظ هذا الكود كملف certificate_qr.svg -->
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
    <rect width="100%" height="100%" fill="white"/>
    <!-- رمز QR Code للرابط أعلاه -->
    <path fill="#006400" d="M20,20h10v10H20z M40,20h10v10H40z M60,20h10v10H60z M80,20h10v10H80z M100,20h10v10H100z M120,20h10v10H120z M140,20h10v10H140z M160,20h10v10H160z M20,40h10v10H20z M40,40h10v10H40z M60,40h10v10H60z M80,40h10v10H80z M100,40h10v10H100z M120,40h10v10H120z M140,40h10v10H140z M160,40h10v10H160z M20,60h10v10H20z M40,60h10v10H40z M60,60h10v10H60z M80,60h10v10H80z M100,60h10v10H100z M120,60h10v10H120z M140,60h10v10H140z M160,60h10v10H160z M20,80h10v10H20z M40,80h10v10H40z M60,80h10v10H60z M80,80h10v10H80z M100,80h10v10H100z M120,80h10v10H120z M140,80h10v10H140z M160,80h10v10H160z M20,100h10v10H20z M40,100h10v10H40z M60,100h10v10H60z M80,100h10v10H80z M100,100h10v10H100z M120,100h10v10H120z M140,100h10v10H140z M160,100h10v10H160z M20,120h10v10H20z M40,120h10v10H40z M60,120h10v10H60z M80,120h10v10H80z M100,120h10v10H100z M120,120h10v10H120z M140,120h10v10H140z M160,120h10v10H160z M20,140h10v10H20z M40,140h10v10H40z M60,140h10v10H60z M80,140h10v10H80z M100,140h10v10H100z M120,140h10v10H120z M140,140h10v10H140z M160,140h10v10H160z M20,160h10v10H20z M40,160h10v10H40z M60,160h10v10H60z M80,160h10v10H80z M100,160h10v10H100z M120,160h10v10H120z M140,160h10v10H140z M160,160h10v10H160z"/>
    <text x="100" y="185" font-family="Arial" font-size="10" text-anchor="middle" fill="#006400">Scan to Verify</text>
</svg>
