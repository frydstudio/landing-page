<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>סטודיו פריד - דף נחיתה</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            direction: rtl;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .hero {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://via.placeholder.com/1920x800');
            background-size: cover;
            background-position: center;
            padding: 100px 20px;
            color: white;
            text-align: center;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
            animation: fadeInDown 1s;
        }

        .hero p {
            font-size: 1.8rem;
            margin: 20px 0 40px;
        }

        .hero button {
            background-color: #ff6f61;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.2rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .hero button:hover {
            background-color: #e0554f;
        }

        .services {
            text-align: center;
            margin: 50px 0;
        }

        .services h2 {
            font-size: 2.5rem;
            color: #007BFF;
            margin-bottom: 20px;
        }

        .services-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .service-item {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
            flex: 1 1 calc(33% - 40px);
            max-width: 300px;
            transition: transform 0.3s;
        }

        .service-item:hover {
            transform: scale(1.05);
        }

        .service-item img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .service-item h3 {
            margin: 15px 0;
            font-size: 1.5rem;
        }

        .portfolio {
            margin: 50px 0;
            text-align: center;
        }

        .portfolio h2 {
            font-size: 2.5rem;
            color: #007BFF;
            margin-bottom: 20px;
        }

        .portfolio-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .portfolio-item {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s;
        }

        .portfolio-item:hover {
            transform: scale(1.05);
        }

        .portfolio-item img {
            width: 100%;
            height: auto;
        }

        .portfolio-item h3 {
            margin: 15px;
            font-size: 1.5rem;
        }

        .contact {
            background: #007BFF;
            color: white;
            padding: 50px 20px;
            text-align: center;
            border-radius: 8px;
        }

        .contact h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-form input,
        .contact-form textarea,
        .contact-form button {
            width: 100%;
            margin-bottom: 15px;
            padding: 10px;
            font-size: 1rem;
            border: none;
            border-radius: 5px;
        }

        .contact-form button {
            background-color: #ff6f61;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .contact-form button:hover {
            background-color: #e0554f;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="hero">
            <h1>סטודיו פריד - עיצוב שמגשימים</h1>
            <p>חדשנות, יצירתיות ומקצועיות במקום אחד. בואו ליצור איתנו את החלום שלכם.</p>
            <button>צרו קשר עכשיו</button>
        </div>

        <section class="services">
            <h2>השירותים שלנו</h2>
            <div class="services-list">
                <div class="service-item">
                    <img src="https://via.placeholder.com/300" alt="עיצוב גרפי">
                    <h3>עיצוב גרפי</h3>
                    <p>הפיכת רעיונות לעיצובים מדהימים.</p>
                </div>
                <div class="service-item">
                    <img src="https://via.placeholder.com/300" alt="מיתוג עסקי">
                    <h3>מיתוג עסקי</h3>
                    <p>יצירת מותגים חזקים ומבודלים.</p>
                </div>
                <div class="service-item">
                    <img src="https://via.placeholder.com/300" alt="עיצוב דיגיטלי">
                    <h3>עיצוב דיגיטלי</h3>
                    <p>עיצוב אתרים ואפליקציות שמדברים לקהל שלך.</p>
                </div>
            </div>
        </section>

        <section class="portfolio">
            <h2>העבודות שלנו</h2>
            <div class="portfolio-list">
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/300" alt="פרויקט 1">
                    <h3>פרויקט 1</h3>
                </div>
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/300" alt="פרויקט 2">
                    <h3>פרויקט 2</h3>
                </div>
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/300" alt="פרויקט 3">
                    <h3>פרויקט 3</h3>
                </div>
            </div>
        </section>

        <section class="contact">
            <h2>צרו קשר</h2>
            <div class="contact-form">
                <form>
                    <input type="text" name="name" placeholder="שם מלא" required>
                    <input type="email" name="email" placeholder="אימייל" required>
                    <textarea name="message" placeholder="ספרו לנו איך נוכל לעזור" rows="5" required></textarea>
                    <button type="submit">שלח הודעה</button>
                </form>
            </div>
        </section>
    </div>
</body>
</html>
