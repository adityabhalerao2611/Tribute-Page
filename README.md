<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tribute to Dr. APJ Abdul Kalam</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Pacifico&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>Tribute to Dr. APJ Abdul Kalam</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#qualities">Admirable Qualities</a></li>
                <li><a href="#gallery">Gallery</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Dr. APJ Abdul Kalam</h2>
        <img src="apj.jpg" alt="Dr. APJ Abdul Kalam" class="profile-img">
        <p>
            Dr. Avul Pakir Jainulabdeen Abdul Kalam, fondly known as the "Missile Man of India," was a visionary scientist, a dedicated teacher, and the 11th President of India. Born on October 15, 1931, in Rameswaram, Tamil Nadu, he rose from humble beginnings to become one of the most respected figures in the world. His contributions to India's space and defense programs, particularly his work with ISRO and DRDO, have left an indelible mark on the nation's scientific achievements.
        </p>
        <p>
            Beyond his scientific prowess, Dr. Kalam was a beacon of inspiration for millions. He believed in the power of dreams and encouraged young minds to think big and work hard. His humility, wisdom, and unwavering commitment to education and innovation continue to inspire generations. Dr. Kalam passed away on July 27, 2015, but his legacy lives on through his books, speeches, and the countless lives he touched.
        </p>
    </section>

    <section id="qualities">
        <h2>Admirable Qualities</h2>
        <ul>
            <li><strong>Visionary Leadership:</strong> Dr. Kalam played a pivotal role in India's Pokhran-II nuclear tests and the development of ballistic missile technology, showcasing his ability to lead and innovate.</li>
            <li><strong>Humility:</strong> Despite his numerous achievements, he remained grounded and approachable, earning him the title of the "People's President."</li>
            <li><strong>Passion for Education:</strong> He was a lifelong learner and a passionate advocate for education, often interacting with students and encouraging them to dream big.</li>
            <li><strong>Simplicity:</strong> Dr. Kalam lived a simple life, free from materialistic desires, and always prioritized the welfare of others.</li>
            <li><strong>Inspirational Speaker:</strong> His speeches and writings, such as <em>Wings of Fire</em> and <em>Ignited Minds</em>, continue to motivate people across the globe.</li>
        </ul>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-container">
            <img src="Apj Abdul kalam.jpg" alt="Dr. Kalam with students">
            <img src="Apj Abdul kalam speech.jpg" alt="Dr. Kalam during a speech">
            <img src="Kalam at isro.webp" alt="Dr. Kalam at ISRO">
        </div>
    </section>

    <footer>
        <p>Created with admiration by [Aditya Bhalerao].</p>
    </footer>
</body>
</html>

<!--CSS Code-->
/* General Styles */
body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.8;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background-color: #2c3e50;
    color: #fff;
    padding: 30px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 3rem;
    font-family: 'Pacifico', cursive;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1rem;
}

/* Sections */
section {
    padding: 30px;
    margin: 20px auto;
    max-width: 800px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
}

section h2 {
    color: #2c3e50;
    border-bottom: 2px solid #2c3e50;
    padding-bottom: 10px;
    font-size: 2rem;
    font-family: 'Pacifico', cursive;
}

.profile-img {
    display: block;
    margin: 20px auto;
    border-radius: 50%;
    width: 200px;
    height: 200px;
    object-fit: cover;
    border: 5px solid #2c3e50;
}

p {
    font-size: 1.1rem;
    text-align: justify;
}

ul {
    list-style-type: square;
    padding-left: 20px;
}

ul li {
    margin-bottom: 10px;
    font-size: 1.1rem;
}

/* Gallery */
.gallery-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.gallery-container img {
    width: 30%;
    margin: 10px 0;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.gallery-container img:hover {
    transform: scale(1.05);
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background-color: #2c3e50;
    color: #fff;
    margin-top: 20px;
    font-size: 1rem;
}
