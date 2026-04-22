<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Official webpage of Harmony Heights, featuring our latest music, tour dates, and exclusive content for our fans.">
    <title>Harmony Heights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background: #f9f9f9;
        }
        .header {
            text-align: center;
            padding: 40px 0;
            background: #fff;
            margin-bottom: 40px;
            border-bottom: 3px solid #007bff;
        }
        h1 {
            color: #007bff;
            font-size: 2.5em;
            margin: 0 0 10px 0;
        }
        .intro {
            font-size: 1.2em;
            color: #666;
            max-width: 600px;
            margin: 0 auto;
        }
        h2 {
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
            margin: 40px 0 20px 0;
        }
        .members {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .member {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .member img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 15px;
        }
        .member-name {
            font-weight: bold;
            font-size: 1.1em;
            margin-bottom: 5px;
        }
        .member-role {
            color: #666;
            font-size: 0.95em;
        }
        audio, video {
            width: 100%;
            max-width: 600px;
            margin: 20px 0;
            display: block;
        }
        .tour-list {
            list-style: none;
            padding: 0;
        }
        .tour-item {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .tour-date {
            font-weight: bold;
        }
        .ticket-btn {
            background: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .social {
            text-align: center;
            background: #e9ecef;
            padding: 30px;
            border-radius: 8px;
            margin: 30px 0;
        }
        .social-links a {
            display: block;
            margin: 10px 0;
            color: #007bff;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
        }
        form {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            max-width: 600px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background: #007bff;
            color: white;
            border: none;
            font-weight: bold;
            cursor: pointer;
        }
        footer {
            text-align: center;
            margin-top: 50px;
            color: #666;
            padding: 20px;
            border-top: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Harmony Heights</h1>
        <p class="intro">We are Harmony Heights, a band that blends genres to create unique sounds. Our journey through music has been incredible, and we're excited to share it with you.</p>
    </div>

    <h2>Meet the Band</h2>
    <div class="members">
        <div class="member">
            <img src="https://edube.org/uploads/media/default/0001/04/band-photo.jpg" alt="Harmony Heights Band Photo">
            <div class="member-name">Harmony Heights</div>
        </div>
        <div class="member">
            <img src="https://edube.org/uploads/media/default/0001/04/member1-amy.jpg" alt="Harmony Heights Vocals/Sampling: Amy Duncan">
            <div class="member-name">Amy Duncan</div>
            <div class="member-role">Vocals/Sampling</div>
        </div>
        <div class="member">
            <img src="https://edube.org/uploads/media/default/0001/04/member2-john.jpg" alt="Harmony Heights Bass/Guitars: John Smith">
            <div class="member-name">John Smith</div>
            <div class="member-role">Bass/Guitars</div>
        </div>
        <div class="member">
            <img src="https://edube.org/uploads/media/default/0001/04/member3-trevor.jpg" alt="Harmony Heights Drums: Trevor G.">
            <div class="member-name">Trevor G.</div>
            <div class="member-role">Drums</div>
        </div>
    </div>

    <h2>Listen to Our Latest Tracks</h2>
    <audio controls>
        <source src="https://edube.org/uploads/media/default/0001/04/track1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <h2>Watch Our Performances</h2>
    <video controls width="640" height="360">
        <source src="https://edube.org/uploads/media/default/0001/04/performance1.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>

    <h2>Upcoming Tour Dates</h2>
    <ul class="tour-list">
        <li class="tour-item">
            <span class="tour-date">March 12, 2027 - Binakayan Palengke</span>
            <a href="https://example.com/purchase-tickets-harmony-heights-orlando" target="_blank" class="ticket-btn">Get Tickets</a>
        </li>
        <li class="tour-item">
            <span class="tour-date">March 14, 2027 - Imus Cavite</span>
            <a href="https://example.com/purchase-tickets-harmony-heights-slc" target="_blank" class="ticket-btn">Get Tickets</a>
        </li>
    </ul>

    <div class="social">
        <h2>Follow Us</h2>
        <p>Stay updated with our latest news and releases:</p>
        <div class="social-links">
            <a href="https://www.facebook.com/jaym.omega.5">Facebook</a>
        </div>
    </div>

    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        
        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject">
        
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
        
        <input type="submit" value="Send">
    </form>

    <footer>
        <p>Villanueva, Jay-m O.</p>
    </footer>
</body>
</html>
