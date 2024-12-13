# graduation-flyer
project for web application development to create a website to host an event
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jalan's Graduation Party</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Jalan's Graduation Party</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#details">Event Details</a></li>
                <li><a href="#rsvp">RSVP</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About the Event</h2>
        <img src="<a href="https://ibb.co/QMtm2jp"><img src="https://i.ibb.co/jDs4cZb/20240910-224338-A1-D6-E8.jpg" alt="20240910-224338-A1-D6-E8" border="0"></a>" ">
        <p>Join us in celebrating Jalan’s graduation from Emporia State University! A night filled with fun, food, and festivities awaits.</p>
    </section>

    <section id="details">
        <h2>Event Details</h2>
        <table>
            <thead>
                <tr>
                    <th>Item</th>
                    <th>Details</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Date</td>
                    <td>December 15, 2024</td>
                </tr>
                <tr>
                    <td>Time</td>
                    <td>6:00 PM - 10:00 PM</td>
                </tr>
                <tr>
                    <td>Location</td>
                    <td>627 Event Space, Upper Room</td>
                </tr>
                <tr>
                    <td>Dress Code:</td>
                    <td>Casual</td>
                </tr>
            </tbody>
        </table>
        <h3>Activities Planned:</h3>
        <ul>
            <li>Opening Speech</li>
            <li>Dinner and Refreshments</li>
            <li>Live Music</li>
            <li>Gifts and Pictures</li>
        </ul>
    </section>

    <section id="rsvp">
        <h2>RSVP</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required minlength="2" maxlength="50">
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="guests">Number of Guests:</label>
            <input type="number" id="guests" name="guests" required min="1" max="10">

            <label for="comments">Comments:</label>
            <textarea id="comments" name="comments" rows="4" maxlength="200"></textarea>

            <button type="submit">Submit RSVP</button>
        </form>
    </section>

    <section id="contact">
        <h2>Contact Information</h2>
        <p>If you have any questions, feel free to reach out to myself or to my parents!</p>
        <ul>
            <li>Email: jalan@EmporiaUniversity.edu</li>
            <li>Phone: (785) 456-7890</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Jalan's Graduation Party. All rights reserved.</p>
    </footer>
</body>
</html>
