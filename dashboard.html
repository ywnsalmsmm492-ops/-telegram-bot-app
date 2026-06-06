<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>التزام برو - لوحة التحكم الذكية</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        :root {
            --bg-dark: #131b24;
            --bg-card: #1e293b;
            --text-color: #ffffff;
            --hint-color: #7e8b9a;
            --gold-color: #cca43b;
            --danger-bg: rgba(239, 68, 68, 0.15);
            --danger-border: rgba(239, 68, 68, 0.3);
            --success-color: #22c55e;
            --danger-color: #ef4444;
        }

        body {
            font-family: 'Cairo', sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-color);
            margin: 0;
            padding: 12px;
            box-sizing: border-box;
            -webkit-user-select: none;
            user-select: none;
        }

        .webapp-container {
            width: 100%;
            max-width: 450px;
            margin: 0 auto;
        }

        .logo-section {
            text-align: center;
            margin-bottom: 12px;
        }
        .logo-box {
            width: 100px;
            height: 100px;
            background: #ffffff;
            border-radius: 50%;
            display: inline-flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
            border: 2px solid var(--gold-color);
            font-weight: 800;
            color: #0b141c;
            font-size: 16px;
            text-align: center;
            flex-direction: column;
            line-height: 1.3;
        }
        .logo-icon {
            font-size: 36px;
            margin-bottom: 2px;
        }

        .user-card {
            background: linear-gradient(135deg, #1e293b, #0f172a);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 16px;
            padding: 14px;
            margin-bottom: 14px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }
        .user-header {
            display: flex;
            justify-content: space-between;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            padding-bottom: 6px;
            margin-bottom: 8px;
            font-size: 13px;
        }
        .badge-premium {
            background: linear-gradient(135deg, #f59e0b, #d97706);
            color: #000;
            padding: 1px 8px;
            border-radius: 20px;
            font-weight: 700;
            font-size: 11px;
        }
        .stats-title {
            font-size: 13px;
            font-weight: 700;
            color: var(--gold-color);
            margin: 6px 0;
        }
        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 8px;
        }
        .stat-item {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            padding: 6px 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 12px;
        }
        .stat-label { color: var(--hint-color); }
        .stat-value { font-weight: 700; }

        /* الصفحات والتنقل */
        .page {
            display: none;
            animation: fadeIn 0.25s ease-in-out;
        }
        .page.active {
            display: block;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(6px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .grid-layout {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }
        .full-width {
            grid-column: span 2;
        }
        .btn-item {
            background: #1e293b;
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 12px;
            padding: 12px;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: flex-start;
            gap: 10px;
            text-align: right;
            transition: background 0.2s, transform 0.1s;
        }
        .btn-item:active {
            transform: scale(0.98);
            background: #334155;
        }
        .btn-icon {
            font-size: 18px;
        }
        .btn-text {
            font-size: 13px;
            font-weight: 600;
            color: #f8fafc;
        }

        /* تم تعديل لون زر الصناديق ليكون ذهبياً مميزاً */
        .btn-item.boxes-trigger {
            background: linear-gradient(135deg, #cca43b, #9a7822);
            border: none;
        }
        .btn-item.boxes-trigger .btn-text {
            color: #0b141c;
        }

        .btn-item.all-services-trigger {
            background: linear-gradient(135deg, #3b82f6, #1d4ed8);
            border: none;
        }
        .btn-item.all-services-trigger:active {
            background: #1e40af;
        }

        .back-btn {
            grid-column: span 2;
            background: var(--danger-bg);
            border: 1px solid var(--danger-border);
            border-radius: 12px;
            padding: 11px;
            color: #ef4444;
            font-size: 13px;
            font-weight: 600;
            font-family: 'Cairo', sans-serif;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 6px;
            margin-top: 6px;
        }
        .back-btn:active {
            background: rgba(239, 68, 68, 0.3);
        }

        /* ستايل بطاقة الصندوق الداكنة المتناسقة */
        .box-container-card {
            background: #1e293b;
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 18px;
            padding: 16px;
            margin-bottom: 12px;
        }
        .box-header-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(255,255,255,0.08);
            padding-bottom: 10px;
            margin-bottom: 12px;
        }
        .box-card-title {
            font-size: 15px;
            font-weight: 700;
            color: var(--gold-color);
        }
        .box-card-icon {
            font-size: 20px;
        }
        .box-balance-item {
            display: flex;
            justify-content: space-between;
            padding: 6px 0;
            font-size: 14px;
            font-weight: 600;
        }
        .box-balance-converted {
            font-size: 12px;
            color: var(--success-color);
            margin-top: 8px;
            border-top: 1px dashed rgba(255,255,255,0.1);
            padding-top: 8px;
            text-align: left;
        }
        .box-card-actions {
            display: flex;
            justify-content: space-between;
            gap: 8px;
            margin-top: 14px;
        }
        .box-action-sub-btn {
            flex: 1;
            background: rgba(255, 255, 255, 0.04);
            border: 1px solid rgba(255, 255, 255, 0.08);
            padding: 8px;
            border-radius: 10px;
            color: #f8fafc;
            font-size: 12px;
            font-weight: 600;
            cursor: pointer;
            text-align: center;
            font-family: 'Cairo', sans-serif;
        }
        .box-action-sub-btn:active {
            background: rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body>

    <div class="webapp-container">
        
        <div class="logo-section">
            <div class="logo-box">
                <span class="logo-icon">📊</span>
                التزام برو
            </div>
        </div>

        <div class="user-card">
            <div class="user-header">
                <div>👤 المستخدم: <strong>المدير (admin)</strong></div>
                <span class="badge-premium">💼 خطة مميزة</span>
            </div>
            <div style="font-size: 12px; margin-bottom: 6px;">🎁 نقاطك: <strong style="color: var(--gold-color);">0</strong></div>
            
            <div class="stats-title">📌 الإحصائيات:</div>
            <div class="stats-grid">
                <div class="stat-item"><span class="stat-label">💰 الرصيد النقدي</span><span class="stat-value" style="color:var(--success-color);">0 يمني</span></div>
                <div class="stat-item"><span class="stat-label">📉 إجمالي عليكم</span><span class="stat-value" style="color:var(--danger-color);">0</span></div>
                <div class="stat-item"><span class="stat-label">👥 الحسابات</span><span class="stat-value">0</span></div>
                <div class="stat-item"><span class="stat-label">📝 المعاملات</span><span class="stat-value">0</span></div>
            </div>
        </div>

        <div id="mainPage" class="page active">
            <div class="grid-layout">
                <button class="btn-item boxes-trigger full-width" onclick="switchPage('boxesPage')">
                    <span class="btn-icon">🏦</span><span class="btn-text">📦 عرض الصناديق المحاسبية</span>
                </button>
                
                <button class="btn-item" onclick="sendAction('add_account')">
                    <span class="btn-icon">➕</span><span class="btn-text">إضافة حساب</span>
                </button>
                <button class="btn-item" onclick="sendAction('account_statement')">
                    <span class="btn-icon">📋</span><span class="btn-text">كشف حساب</span>
                </button>
                <button class="btn-item full-width" onclick="sendAction('add_entry')">
                    <span class="btn-icon">📝</span><span class="btn-text">إضافة قيد</span>
                </button>
                <button class="btn-item" onclick="sendAction('accounts')">
                    <span class="btn-icon">👤</span><span class="btn-text">الحسابات</span>
                </button>
                <button class="btn-item" onclick="sendAction('reports')">
                    <span class="btn-icon">📊</span><span class="btn-text">التقارير</span>
                </button>
                <button class="btn-item" onclick="sendAction('redeem_points')">
                    <span class="btn-icon">🎁</span><span class="btn-text">استبدال النقاط</span>
                </button>
                <button class="btn-item" onclick="sendAction('referral_link')">
                    <span class="btn-icon">🔗</span><span class="btn-text">رابط الإحالة</span>
                </button>
                <button class="btn-item" onclick="sendAction('main_menu')">
                    <span class="btn-icon">🔙</span><span class="btn-text">القائمة الرئيسية</span>
                </button>
                
                <button class="btn-item all-services-trigger" onclick="switchPage('servicesPage')">
                    <span class="btn-icon">📂</span><span class="btn-text" style="color: white;">جميع الخدمات</span>
                </button>
                
                <button class="btn-item full-width" onclick="sendAction('control_panel')">
                    <span class="btn-icon">📱</span><span class="btn-text">لوحة التحكم</span>
                </button>
            </div>
        </div>

        <div id="boxesPage" class="page">
            <div style="font-size: 14px; font-weight: 700; color: var(--gold-color); margin-bottom: 10px;">📋 كشف الصناديق الحالية:</div>
            
            <div class="box-container-card">
                <div class="box-header-row">
                    <div class="box-card-title">الصندوق الرئيسي</div>
                    <div class="box-card-icon">🏦</div>
                </div>
                <div class="box-balance-item">
                    <span style="color: var(--hint-color);">الريال اليمني</span>
                    <span style="color: var(--success-color);">لكم 0.0 يمني</span>
                </div>
                <div class="box-balance-item">
                    <span style="color: var(--hint-color);">الريال السعودي</span>
                    <span style="color: var(--danger-color);">عليكم 0.0 سعودي</span>
                </div>
                <div class="box-balance-item">
                    <span style="color: var(--hint-color);">الدولار الأمريكي</span>
                    <span style="color: var(--danger-color);">عليكم 0.0 دولار</span>
                </div>
                <div class="box-balance-converted">
                    الرصيد بالمقابل لكم 0.0 يمني
                </div>
                
                <div class="box-card-actions">
                    <button class="box-action-sub-btn" onclick="sendAction('box_edit')">🖊️ تعديل</button>
                    <button class="box-action-sub-btn" onclick="sendAction('box_transfer')">📈 تحويل</button>
                    <button class="box-action-sub-btn" onclick="sendAction('box_exchange')">🛒 صرف</button>
                </div>
            </div>

            <button class="back-btn" onclick="switchPage('mainPage')">
                <span>↩️</span> رجوع للوحة التحكم الرئيسية
            </button>
        </div>

        <div id="servicesPage" class="page">
            <div class="grid-layout">
                <button class="btn-item" onclick="sendAction('receipt_payment')">
                    <span class="btn-icon">💵</span><span class="btn-text">سند قبض / صرف</span>
                </button>
                <button class="btn-item" onclick="sendAction('accounts_services')">
                    <span class="btn-icon">👥</span><span class="btn-text">الحسابات</span>
                </button>
                <button class="btn-item" onclick="sendAction('currency_exchange')">
                    <span class="btn-icon">💱</span><span class="btn-text">مصارفة</span>
                </button>
                <button class="btn-item" onclick="sendAction('transfer_accounts')">
                    <span class="btn-icon">🔄</span><span class="btn-text">تحويل بين الحسابات</span>
                </button>
                <button class="btn-item" onclick="sendAction('items')">
                    <span class="btn-icon">📦</span><span class="btn-text">الأصناف</span>
                </button>
                <button class="btn-item" onclick="sendAction('stores')">
                    <span class="btn-icon">🏠</span><span class="btn-text">المخازن</span>
                </button>
                <button class="btn-item" onclick="sendAction('electricity_bills')">
                    <span class="btn-icon">💡</span><span class="btn-text">فواتير الكهرباء</span>
                </button>
                <button class="btn-item" onclick="sendAction('invoices')">
                    <span class="btn-icon">🧾</span><span class="btn-text">الفواتير</span>
                </button>
                <button class="btn-item" onclick="sendAction('reports_services')">
                    <span class="btn-icon">📊</span><span class="btn-text">التقارير</span>
                </button>
                <button class="btn-item" onclick="sendAction('transfers')">
                    <span class="btn-icon">📩</span><span class="btn-text">الحوالات</span>
                </button>
                <button class="btn-item" onclick="sendAction('debt_tracking')">
                    <span class="btn-icon">📈</span><span class="btn-text">متابعة الديون</span>
                </button>
                <button class="btn-item" onclick="sendAction('staff_management')">
                    <span class="btn-icon">👥</span><span class="btn-text">إدارة الموظفين</span>
                </button>
                <button class="btn-item full-width" onclick="sendAction('settings')">
                    <span class="btn-icon">⚙️</span><span class="btn-text">الإعدادات</span>
                </button>

                <button class="back-btn" onclick="switchPage('mainPage')">
                    <span>↩️</span> رجوع للقائمة الرئيسية
                </button>
            </div>
        </div>

    </div>

    <script>
        const tg = window.Telegram.WebApp;
        tg.ready();
        tg.expand();

        function switchPage(pageId) {
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });
            document.getElementById(pageId).classList.add('active');
        }

        function sendAction(actionName) {
            tg.sendData(JSON.stringify({ action: actionName, system: 'التزام_برو' }));
        }
    </script>
</body>
</html>
