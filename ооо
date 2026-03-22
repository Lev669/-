<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Как сказать «нет» без чувства вины за 7 дней | Яна — астропсихолог</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg-primary: #F8F5F0;
            --bg-secondary: #F0EDE8;
            --text-primary: #3A3A3A;
            --text-secondary: #2C4A3E;
            --accent: #C9A961;
            --accent-soft: #9CAF88;
            --border: #D4C8B5;
            --error: #B85450;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #F8F5F0 0%, #F0EDE8 100%);
            color: var(--text-primary);
            line-height: 1.6;
            overflow-x: hidden;
        }

        .container {
            max-width: 720px;
            margin: 0 auto;
            padding: 0 24px;
        }

        /* Header */
        header {
            padding: 40px 0 60px;
            text-align: center;
            position: relative;
        }

        .author-badge {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            background: white;
            padding: 12px 24px;
            border-radius: 50px;
            box-shadow: 0 4px 20px rgba(44, 74, 62, 0.08);
            margin-bottom: 32px;
            font-size: 14px;
            color: var(--text-secondary);
        }

        .author-avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--accent) 0%, var(--accent-soft) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: 600;
            font-family: 'Cormorant Garamond', serif;
        }

        h1 {
            font-family: 'Cormorant Garamond', serif;
            font-size: clamp(32px, 5vw, 48px);
            font-weight: 600;
            color: var(--text-secondary);
            line-height: 1.2;
            margin-bottom: 16px;
            letter-spacing: -0.02em;
        }

        .subtitle {
            font-size: 18px;
            color: var(--text-primary);
            opacity: 0.8;
            font-weight: 300;
        }

        /* Progress indicator */
        .progress-container {
            position: sticky;
            top: 0;
            background: rgba(248, 245, 240, 0.95);
            backdrop-filter: blur(10px);
            z-index: 100;
            padding: 16px 0;
            border-bottom: 1px solid var(--border);
            margin-bottom: 40px;
        }

        .progress-bar {
            height: 4px;
            background: var(--bg-secondary);
            border-radius: 2px;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, var(--accent) 0%, var(--accent-soft) 100%);
            width: 0%;
            transition: width 0.3s ease;
        }

        .progress-text {
            text-align: center;
            font-size: 12px;
            color: var(--accent);
            margin-top: 8px;
            font-weight: 500;
        }

        /* Sections */
        section {
            margin-bottom: 60px;
            opacity: 1;
            transform: translateY(0);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }

        .intro-box {
            background: white;
            padding: 32px;
            border-radius: 16px;
            box-shadow: 0 4px 24px rgba(44, 74, 62, 0.06);
            margin-bottom: 40px;
            border-left: 4px solid var(--accent-soft);
        }

        .pain-quote {
            font-family: 'Cormorant Garamond', serif;
            font-size: 20px;
            font-style: italic;
            color: var(--text-secondary);
            margin-bottom: 16px;
            padding-left: 20px;
            border-left: 3px solid var(--accent);
        }

        h2 {
            font-family: 'Cormorant Garamond', serif;
            font-size: 28px;
            color: var(--text-secondary);
            margin-bottom: 20px;
            font-weight: 600;
        }

        h3 {
            font-family: 'Cormorant Garamond', serif;
            font-size: 22px;
            color: var(--text-secondary);
            margin: 32px 0 16px;
            font-weight: 600;
        }

        p {
            margin-bottom: 16px;
            font-size: 16px;
            line-height: 1.7;
        }

        .highlight {
            background: linear-gradient(120deg, rgba(201, 169, 97, 0.2) 0%, rgba(156, 175, 136, 0.2) 100%);
            padding: 2px 8px;
            border-radius: 4px;
            font-weight: 500;
        }

        /* Interactive elements */
        .check-list {
            list-style: none;
            margin: 20px 0;
        }

        .check-list li {
            padding: 12px 16px;
            margin-bottom: 8px;
            background: white;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 12px;
            border: 2px solid transparent;
        }

        .check-list li:hover {
            transform: translateX(4px);
            border-color: var(--accent-soft);
            box-shadow: 0 2px 12px rgba(44, 74, 62, 0.08);
        }

        .check-list li.checked {
            background: var(--bg-secondary);
            border-color: var(--accent-soft);
            opacity: 0.7;
        }

        .check-icon {
            width: 24px;
            height: 24px;
            border: 2px solid var(--border);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            transition: all 0.3s ease;
        }

        .check-list li.checked .check-icon {
            background: var(--accent-soft);
            border-color: var(--accent-soft);
            color: white;
        }

        /* Steps */
        .step {
            background: white;
            padding: 32px;
            border-radius: 16px;
            margin-bottom: 24px;
            box-shadow: 0 4px 24px rgba(44, 74, 62, 0.06);
            position: relative;
            overflow: hidden;
        }

        .step::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 4px;
            height: 100%;
            background: linear-gradient(180deg, var(--accent) 0%, var(--accent-soft) 100%);
        }

        .step-number {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, var(--accent) 0%, var(--accent-soft) 100%);
            color: white;
            border-radius: 50%;
            font-weight: 600;
            font-family: 'Cormorant Garamond', serif;
            margin-bottom: 16px;
            font-size: 18px;
        }

        .step h3 {
            margin-top: 0;
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .action-box {
            background: var(--bg-secondary);
            padding: 20px;
            border-radius: 12px;
            margin-top: 20px;
            border-left: 3px solid var(--accent);
        }

        .action-box strong {
            color: var(--text-secondary);
            display: block;
            margin-bottom: 8px;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }

        /* Formula card */
        .formula-card {
            background: linear-gradient(135deg, var(--text-secondary) 0%, var(--accent-soft) 100%);
            color: white;
            padding: 32px;
            border-radius: 16px;
            margin: 32px 0;
            text-align: center;
        }

        .formula-card h3 {
            color: white;
            margin-top: 0;
            font-size: 24px;
        }

        .formula-steps {
            display: flex;
            flex-direction: column;
            gap: 16px;
            margin-top: 24px;
            font-size: 18px;
        }

        .formula-step {
            background: rgba(255, 255, 255, 0.15);
            padding: 16px;
            border-radius: 8px;
            backdrop-filter: blur(10px);
        }

        /* Diary table */
        .diary-table {
            width: 100%;
            border-collapse: collapse;
            margin: 24px 0;
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 24px rgba(44, 74, 62, 0.06);
        }

        .diary-table th {
            background: var(--accent-soft);
            color: white;
            padding: 16px;
            text-align: left;
            font-weight: 500;
            font-size: 14px;
        }

        .diary-table td {
            padding: 16px;
            border-bottom: 1px solid var(--border);
            font-size: 14px;
        }

        .diary-table tr:last-child td {
            border-bottom: none;
        }

        .diary-table tr:hover td {
            background: var(--bg-secondary);
        }

        /* Case study */
        .case-study {
            background: white;
            padding: 32px;
            border-radius: 16px;
            box-shadow: 0 4px 24px rgba(44, 74, 62, 0.06);
            margin: 32px 0;
        }

        .case-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 24px;
            margin-top: 20px;
        }

        .case-box {
            padding: 20px;
            border-radius: 12px;
        }

        .case-before {
            background: #FFF5F5;
            border-left: 4px solid var(--error);
        }

        .case-after {
            background: #F0FFF5;
            border-left: 4px solid var(--accent-soft);
        }

        .case-box h4 {
            font-family: 'Cormorant Garamond', serif;
            margin-bottom: 12px;
            font-size: 18px;
        }

        .case-before h4 {
            color: var(--error);
        }

        .case-after h4 {
            color: var(--accent-soft);
        }

        .stat {
            font-size: 32px;
            font-weight: 600;
            color: var(--text-secondary);
            font-family: 'Cormorant Garamond', serif;
            margin: 8px 0;
        }

        /* Practices CTA */
        .practices-section {
            background: linear-gradient(135deg, var(--text-secondary) 0%, #1a3d32 100%);
            color: white;
            padding: 48px 32px;
            border-radius: 20px;
            margin: 60px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .practices-section::before {
            content: '✦';
            position: absolute;
            top: 20px;
            right: 30px;
            font-size: 60px;
            opacity: 0.1;
            color: var(--accent);
        }

        .practices-section h2 {
            color: white;
            font-size: 32px;
            margin-bottom: 16px;
        }

        .practices-section > p {
            opacity: 0.9;
            margin-bottom: 32px;
            font-size: 16px;
        }

        .practices-grid {
            display: grid;
            gap: 20px;
            margin: 32px 0;
        }

        .practice-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 24px;
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            text-align: left;
            transition: transform 0.3s ease;
        }

        .practice-card:hover {
            transform: translateY(-4px);
            background: rgba(255, 255, 255, 0.15);
        }

        .practice-icon {
            font-size: 32px;
            margin-bottom: 12px;
        }

        .practice-card h3 {
            color: white;
            margin: 0 0 8px 0;
            font-size: 20px;
        }

        .practice-card p {
            margin: 0;
            opacity: 0.9;
            font-size: 14px;
        }

        .cta-button {
            display: inline-block;
            background: linear-gradient(135deg, var(--accent) 0%, #D4B978 100%);
            color: var(--text-secondary);
            padding: 20px 48px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 16px;
            margin-top: 24px;
            box-shadow: 0 8px 24px rgba(201, 169, 97, 0.4);
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }

        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 12px 32px rgba(201, 169, 97, 0.5);
        }

        .cta-note {
            margin-top: 16px;
            font-size: 13px;
            opacity: 0.8;
        }

        /* Breathing exercise */
        .breathing-exercise {
            background: white;
            padding: 40px;
            border-radius: 16px;
            text-align: center;
            margin: 32px 0;
            box-shadow: 0 4px 24px rgba(44, 74, 62, 0.06);
        }

        .breath-circle {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--accent-soft) 0%, var(--accent) 100%);
            margin: 24px auto;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            animation: breathe 8s ease-in-out infinite;
            cursor: pointer;
            box-shadow: 0 4px 20px rgba(156, 175, 136, 0.4);
        }

        @keyframes breathe {
            0%, 100% { transform: scale(1); opacity: 0.8; }
            50% { transform: scale(1.2); opacity: 1; }
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 60px 0 40px;
            border-top: 1px solid var(--border);
            margin-top: 60px;
        }

        .author-signature {
            font-family: 'Cormorant Garamond', serif;
            font-size: 24px;
            color: var(--text-secondary);
            margin-bottom: 8px;
        }

        .author-role {
            font-size: 14px;
            color: var(--accent-soft);
            margin-bottom: 24px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 16px;
            margin-top: 24px;
        }

        .social-link {
            width: 44px;
            height: 44px;
            border-radius: 50%;
            background: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            color: var(--text-secondary);
            box-shadow: 0 2px 12px rgba(44, 74, 62, 0.08);
            transition: all 0.3s ease;
        }

        .social-link:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 20px rgba(44, 74, 62, 0.12);
            background: var(--accent);
        }

        /* Responsive */
        @media (max-width: 640px) {
            .case-grid {
                grid-template-columns: 1fr;
            }
            
            .practices-section {
                padding: 32px 20px;
            }
            
            .step, .intro-box {
                padding: 24px;
            }
        }

        /* Interactive tooltip */
        .tooltip {
            position: relative;
            display: inline-block;
            border-bottom: 2px dotted var(--accent);
            cursor: help;
        }

        .tooltip:hover::after {
            content: attr(data-tip);
            position: absolute;
            bottom: 125%;
            left: 50%;
            transform: translateX(-50%);
            background: var(--text-secondary);
            color: white;
            padding: 8px 12px;
            border-radius: 8px;
            font-size: 13px;
            white-space: nowrap;
            z-index: 10;
        }

        /* Reflection prompt */
        .reflection {
            background: linear-gradient(135deg, rgba(201, 169, 97, 0.1) 0%, rgba(156, 175, 136, 0.1) 100%);
            padding: 24px;
            border-radius: 12px;
            margin: 24px 0;
            border: 2px dashed var(--accent);
        }

        .reflection h4 {
            font-family: 'Cormorant Garamond', serif;
            color: var(--text-secondary);
            margin-bottom: 12px;
            font-size: 18px;
        }

        .reflection textarea {
            width: 100%;
            min-height: 80px;
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 12px;
            font-family: 'Inter', sans-serif;
            font-size: 14px;
            resize: vertical;
            background: white;
            margin-top: 12px;
        }

        .reflection textarea:focus {
            outline: none;
            border-color: var(--accent-soft);
            box-shadow: 0 0 0 3px rgba(156, 175, 136, 0.1);
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <div class="author-badge">
                <div class="author-avatar">Я</div>
                <span>Яна · астропсихолог</span>
            </div>
            <h1>Как сказать «нет» без чувства вины за 7 дней</h1>
            <p class="subtitle">Без конфликтов, оправданий и самокопания</p>
        </div>
    </header>

    <div class="progress-container">
        <div class="container">
            <div class="progress-bar">
                <div class="progress-fill" id="progressFill"></div>
            </div>
            <div class="progress-text" id="progressText">Начните чтение</div>
        </div>
    </div>

    <main class="container">

        <!-- Introduction -->
        <section class="intro-box">
            <div class="pain-quote">
                «Меня опять попросили поработать за двоих, и я согласилась. Внутри всё кипит, а языком сказать не могу»
            </div>
            <div class="pain-quote">
                «Я как выжатый лимон. Встаю утром и уже устала. Работа, дом, дети — я в этом растворяюсь»
            </div>
            <p style="margin-top: 20px;">
                Если вы узнали себя — <span class="highlight">этот материал для вас</span>. Я знаю, как страшно отказать. Кажется, что если вы скажете «нет», вас перестанут любить, сочтут эгоисткой или испортите отношения навсегда.
            </p>
            <p>
                <strong>Но правда в том, что ваше «да» через силу разрушает вас изнутри.</strong>
            </p>
        </section>

        <!-- Quick Check -->
        <section>
            <h2>🎯 Проверьте себя</h2>
            <p>Отметьте то, что вам знакомо:</p>
            <ul class="check-list" id="checkList">
                <li onclick="toggleCheck(this)">
                    <div class="check-icon">✓</div>
                    <span>Соглашаюсь на неудобные просьбы, а потом злюсь на себя</span>
                </li>
                <li onclick="toggleCheck(this)">
                    <div class="check-icon">✓</div>
                    <span>Боюсь, что меня перестанут любить, если откажу</span>
                </li>
                <li onclick="toggleCheck(this)">
                    <div class="check-icon">✓</div>
                    <span>Чувствую вину, когда делаю что-то для себя</span>
                </li>
                <li onclick="toggleCheck(this)">
                    <div class="check-icon">✓</div>
                    <span>Не могу попросить о помощи, даже когда очень нужно</span>
                </li>
                <li onclick="toggleCheck(this)">
                    <div class="check-icon">✓</div>
                    <span>Постоянно устаю и чувствую, что «тащу всё на себе»</span>
                </li>
            </ul>
            <p style="text-align: center; color: var(--accent-soft); font-size: 14px; margin-top: 16px;">
                Отмечено: <span id="checkCount">0</span> из 5
            </p>
        </section>

        <!-- Story -->
        <section>
            <h2>История Анны</h2>
            <p>
                Анна, 34 года, руководитель отдела. Брала работу на выходные, потому что «не могла подвести команду». Итог: <span class="highlight">панические атаки по воскресеньям</span> и желание уволиться.
            </p>
            <p>
                Она пыталась терпеть, делать всё быстрее, жаловаться подругам. Становилось только хуже.
            </p>
            <div class="action-box">
                <strong>💡 Инсайт</strong>
                Анна боялась не конфликта, а ощущения, что она «плохая». Она путала профессионализм с самопожертвованием.
            </div>
            <p>
                Когда Анна научилась говорить «нет», мир не рухнул. Коллеги приняли её ответ. <strong>У неё появилось 5 часов на себя в выходные.</strong>
            </p>
            <p style="font-family: 'Cormorant Garamond', serif; font-size: 20px; font-style: italic; text-align: center; color: var(--text-secondary); margin: 24px 0;">
                «Границы — это не стена. Это дверь, которой управляете вы»
            </p>
        </section>

        <!-- Steps -->
        <section>
            <h2>5 шагов к свободе говорить «нет»</h2>

            <div class="step">
                <div class="step-number">1</div>
                <h3>Поймайте сигнал тела</h3>
                <p>
                    Прежде чем сказать «да», остановитесь на 3 секунды. <span class="highlight">Ваше тело знает ответ раньше мозга.</span>
                </p>
                <p>Задайте себе вопросы:</p>
                <ul style="margin: 16px 0; padding-left: 24px;">
                    <li>Сжатые челюсти?</li>
                    <li>Ком в животе?</li>
                    <li>Внутреннее напряжение?</li>
                </ul>
                <p>Если есть хоть один признак — это сигнал <strong>«СТОП»</strong>.</p>
                
                <div class="reflection">
                    <h4>📝 Задание на сегодня</h4>
                    <p>В ближайшие 24 часа отследите 3 момента, когда вам хочется отказаться, но вы молчите. Что вы чувствуете в теле?</p>
                    <textarea placeholder="Запишите свои наблюдения..."></textarea>
                </div>
            </div>

            <div class="step">
                <div class="step-number">2</div>
                <h3>Возьмите паузу</h3>
                <p>
                    Самая большая ошибка — отвечать мгновенно. Когда вас о чем-то просят, давление момента заставляет соглашаться автоматически.
                </p>
                <div class="formula-card" style="margin: 20px 0;">
                    <h3>Ваша новая мантра</h3>
                    <div class="formula-steps">
                        <div class="formula-step">«Мне нужно проверить свой график»</div>
                        <div class="formula-step">«Я отвечу вам через час»</div>
                        <div class="formula-step">«Дайте мне время подумать»</div>
                    </div>
                </div>
                <p>
                    Это не ложь. Это время подумать: <span class="highlight">хочу ли я это делать? Есть ли у меня ресурс?</span>
                </p>
            </div>

            <div class="step">
                <div class="step-number">3</div>
                <h3>Используйте формулу «Мягкий отказ»</h3>
                <p>Отказ не должен быть грубым. Он должен быть твердым.</p>
                
                <div class="formula-card">
                    <h3>Идеальная формула</h3>
                    <div class="formula-steps">
                        <div class="formula-step">🙏 <strong>Благодарность</strong> + <strong>Отказ</strong> + <strong>Альтернатива</strong></div>
                    </div>
                </div>

                <h4 style="margin: 20px 0 12px; font-family: 'Cormorant Garamond', serif; color: var(--text-secondary);">Примеры:</h4>
                
                <div class="action-box" style="margin-bottom: 12px;">
                    <strong>Для работы:</strong>
                    <p style="margin: 0; font-size: 15px;">«Спасибо за доверие. Я не смогу взять эту задачу сейчас, так как загружена текущим проектом. Могу посмотреть её во вторник или передать коллеге»</p>
                </div>

                <div class="action-box">
                    <strong>Для друзей:</strong>
                    <p style="margin: 0; font-size: 15px;">«Я ценю приглашение. В эти выходные я планирую отдыхать и не смогу прийти. Давайте созвонимся на следующей неделе?»</p>
                </div>
            </div>

            <div class="step">
                <div class="step-number">4</div>
                <h3>Не оправдывайтесь</h3>
                <p>
                    <span class="highlight">Оправдания приглашают к дискуссии.</span> Когда вы говорите: «Я не могу, потому что у меня заболела кошка...», собеседник слышит: «Если бы кошка не заболела, ты бы смогла».
                </p>
                <div class="breathing-exercise">
                    <p style="margin-bottom: 16px; font-weight: 500;">Ваше «нет» не требует обоснования</p>
                    <div class="breath-circle" onclick="toggleBreath(this)">🌿</div>
                    <p style="font-size: 14px; color: var(--accent-soft);">Нажмите на круг, чтобы успокоиться</p>
                </div>
                <p style="text-align: center; font-style: italic; color: var(--text-secondary);">
                    Вы имеете право не хотеть. Точка.
                </p>
            </div>

            <div class="step">
                <div class="step-number">5</div>
                <h3>Проживите вину и отпустите</h3>
                <p>
                    После отказа вы почувствуете укол вины. <span class="highlight">Это нормально.</span> Это не значит, что вы сделали что-то плохое. Это значит, что вы ломаете старую привычку быть «удобной».
                </p>
                <h4 style="margin: 20px 0 12px; font-family: 'Cormorant Garamond', serif;">Техника «Стоп-вина»:</h4>
                <ol style="padding-left: 24px; margin: 16px 0;">
                    <li>Признайте: «Я чувствую вину»</li>
                    <li>Скажите себе: «Я имею право беречь свой ресурс»</li>
                    <li>Переключите внимание на дело, которое приносит вам радость</li>
                </ol>
                <div class="action-box">
                    <strong>⚠️ Важно</strong>
                    <p style="margin: 0;">Если после отказа человек обижается и давит — это маркер токсичных отношений. Здоровые люди уважают границы.</p>
                </div>
            </div>
        </section>

        <!-- Diary -->
        <section>
            <h2>📓 Дневник границ</h2>
            <p>Заполняйте эту таблицу в течение 7 дней:</p>
            
            <table class="diary-table">
                <thead>
                    <tr>
                        <th>Ситуация</th>
                        <th>Моя реакция</th>
                        <th>Ощущения</th>
                        <th>Что улучшить</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Пример: Начальник</td>
                        <td>Взяла паузу</td>
                        <td>Тревога, но прошла</td>
                        <td>Ответила четко через час</td>
                    </tr>
                    <tr>
                        <td style="color: var(--border);">День 1...</td>
                        <td style="color: var(--border);">-</td>
                        <td style="color: var(--border);">-</td>
                        <td style="color: var(--border);">-</td>
                    </tr>
                    <tr>
                        <td style="color: var(--border);">День 2...</td>
                        <td style="color: var(--border);">-</td>
                        <td style="color: var(--border);">-</td>
                        <td style="color: var(--border);">-</td>
                    </tr>
                </tbody>
            </table>

            <div class="reflection">
                <h4>🎯 Задание на неделю</h4>
                <p>Скажите осознанное «нет» минимум 3 раза. Это может быть: лишняя встреча, звонок, который не хотите принимать, просьба друга.</p>
                <p style="margin-top: 12px; font-style: italic; color: var(--accent-soft);">
                    Помните: каждый отказ — это акт любви к себе.
                </p>
            </div>
        </section>

        <!-- Case Study -->
        <section class="case-study">
            <h2>Результат Елены</h2>
            <p>38 лет, предприниматель. Запрос: «Не умею отказывать клиентам, работаю 24/7, выгорела».</p>
            
            <div class="case-grid">
                <div class="case-box case-before">
                    <h4>До работы</h4>
                    <div class="stat">60+ часов</div>
                    <p>в неделю</p>
                    <div class="stat" style="color: var(--error);">9/10</div>
                    <p>уровень стресса</p>
                </div>
                <div class="case-box case-after">
                    <h4>После</h4>
                    <div class="stat">40 часов</div>
                    <p>в неделю</p>
                    <div class="stat" style="color: var(--accent-soft);">3/10</div>
                    <p>уровень стресса</p>
                    <div class="stat" style="color: var(--accent);">+30%</div>
                    <p>доход</p>
                </div>
            </div>

            <p style="font-family: 'Cormorant Garamond', serif; font-size: 20px; font-style: italic; text-align: center; margin-top: 24px; color: var(--text-secondary);">
                «Я боялась, что клиенты уйдут. Они не ушли. Они начали уважать мое время ещё больше»
            </p>
        </section>

        <!-- Practices CTA -->
        <section class="practices-section">
            <h2>🌟 3 практики для глубокой работы</h2>
            <p>Вы научились говорить «нет». Но часто за неумением отказывать стоят глубинные убеждения: «Я должна заслужить любовь», «Я не имею права на отдых».</p>
            
            <p style="font-size: 18px; margin-bottom: 24px;"><strong>Приглашаю вас пройти 3 трансформационные практики:</strong></p>

            <div class="practices-grid">
                <div class="practice-card">
                    <div class="practice-icon">🌊</div>
                    <h3>1. Очищение от негатива</h3>
                    <p>Избавьтесь от чужих установок, чувства вины и эмоционального груза, который тянет вас вниз. Освободите место для нового.</p>
                </div>

                <div class="practice-card">
                    <div class="practice-icon">🙏</div>
                    <h3>2. Практика благодарности</h3>
                    <p>Научитесь принимать хорошее без чувства вины. Развивайте навык замечать и ценить то, что у вас есть, без самобичевания.</p>
                </div>

                <div class="practice-card">
                    <div class="practice-icon">🌳</div>
                    <h3>3. Проработка рода</h3>
                    <p>Разберитесь с семейными сценариями «быть удобным» и «жертвовать собой». Верните себе право жить свою жизнь.</p>
                </div>
            </div>

            <button class="cta-button" onclick="scrollToPractices()">
                Начать трансформацию
            </button>
            
            <p class="cta-note">
                ⏳ Ближайший поток стартует через 3 дня<br>
                Осталось 5 мест
            </p>
        </section>

        <!-- Key Takeaways -->
        <section>
            <h2>🎯 3 главных вывода</h2>
            <div class="step" style="margin-bottom: 16px;">
                <p style="margin: 0; font-size: 17px;"><strong>1. Отказ ≠ Конфликт.</strong> Это защита ваших ресурсов и проявление уважения к себе.</p>
            </div>
            <div class="step" style="margin-bottom: 16px;">
                <p style="margin: 0; font-size: 17px;"><strong>2. Пауза — ваше главное оружие.</strong> Не отвечайте мгновенно, дайте себе время почувствовать.</p>
            </div>
            <div class="step">
                <p style="margin: 0; font-size: 17px;"><strong>3. Вина пройдет.</strong> Это цена за вашу свободу. С каждым разом будет легче.</p>
            </div>
        </section>

    </main>

    <footer>
        <div class="container">
            <div class="author-signature">С заботой, Яна</div>
            <div class="author-role">Астропсихолог · Помогаю людям возвращать себе право на жизнь без чувства вины</div>
            
            <p style="font-size: 14px; color: var(--text-primary); opacity: 0.8; max-width: 400px; margin: 0 auto;">
                В моей практике более 500 часов консультаций. Работаю с проблемами людей через призму психологии и астрологии, но всегда — с научным подходом и без эзотерики.
            </p>

            <div class="social-links">
                <a href="#" class="social-link" title="Instagram">📸</a>
                <a href="#" class="social-link" title="Telegram">✈️</a>
                <a href="#" class="social-link" title="WhatsApp">💬</a>
            </div>

            <p style="margin-top: 32px; font-size: 12px; color: var(--border);">
                © 2024 Яна · Все права защищены
            </p>
        </div>
    </footer>

    <script>
        // Progress bar
        window.onscroll = function() {
            let winScroll = document.body.scrollTop || document.documentElement.scrollTop;
            let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
            let scrolled = (winScroll / height) * 100;
            document.getElementById("progressFill").style.width = scrolled + "%";
            
            // Update progress text
            const sections = document.querySelectorAll('section');
            let currentSection = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (pageYOffset >= (sectionTop - 200)) {
                    currentSection = section.querySelector('h2')?.textContent || '';
                }
            });
            
            if (currentSection) {
                document.getElementById("progressText").textContent = currentSection.substring(0, 30) + (currentSection.length > 30 ? '...' : '');
            } else {
                document.getElementById("progressText").textContent = 'Начните чтение';
            }
        };

        // Check list
        function toggleCheck(item) {
            item.classList.toggle('checked');
            const checkedItems = document.querySelectorAll('.check-list li.checked').length;
            document.getElementById('checkCount').textContent = checkedItems;
            
            if (checkedItems >= 3) {
                setTimeout(() => {
                    alert('💡 Похоже, вам действительно пора учиться говорить «нет». Продолжайте читать — впереди практические шаги!');
                }, 500);
            }
        }

        // Breathing exercise
        let isBreathing = false;
        function toggleBreath(element) {
            isBreathing = !isBreathing;
            if (isBreathing) {
                element.style.animationPlayState = 'running';
                element.textContent = '🌿';
            } else {
                element.style.animationPlayState = 'paused';
                element.textContent = '';
            }
        }

        // Smooth scroll to practices
        function scrollToPractices() {
            document.querySelector('.practices-section').scrollIntoView({ behavior: 'smooth' });
        }

        // Add subtle parallax effect to header
        window.addEventListener('scroll', () => {
            const scrolled = window.pageYOffset;
            const header = document.querySelector('header');
            header.style.transform = `translateY(${scrolled * 0.5}px)`;
            header.style.opacity = 1 - (scrolled / 500);
        });

        // Track engagement
        let timeOnPage = 0;
        setInterval(() => {
            timeOnPage++;
            if (timeOnPage === 60) { // After 1 minute
                console.log('User engaged for 1 minute');
            }
        }, 1000);

        // Intersection Observer for sections (for future animations if needed)
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -100px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        document.querySelectorAll('section').forEach(section => {
            observer.observe(section);
        });
    </script>
</body>
</html>
