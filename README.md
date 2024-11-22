<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BossBuilder - Build Your Future</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header class="hero">
        <div class="container">
            <h1>BossBuilder</h1>
            <p>Your Future, Your Business, Built Today</p>
            <a href="#quiz" class="cta">Take the Quiz</a>
        </div>
    </header>

    <main>
        <!-- Quiz Section -->
        <section id="quiz" class="quiz-section">
            <h2>Find Your Perfect Business Idea</h2>
            <p>Answer a few quick questions, and we'll craft a tailored business idea for you.</p>
            <form id="businessQuiz">
                <label for="time">How much time can you dedicate per week?</label>
                <select id="time" name="time">
                    <option value="5">Up to 5 hours</option>
                    <option value="10">5–10 hours</option>
                    <option value="20">10–20 hours</option>
                    <option value="40">Full-time</option>
                </select>

                <label for="skills">What skills do you have?</label>
                <textarea id="skills" name="skills" placeholder="e.g., writing, coding, photography"></textarea>

                <label for="investment">How much can you invest?</label>
                <select id="investment" name="investment">
                    <option value="0">None</option>
                    <option value="100">$100–$500</option>
                    <option value="1000">$500–$1000</option>
                    <option value="5000">$1000+</option>
                </select>

                <button type="submit">Get My Ideas</button>
            </form>
        </section>

        <!-- Results Section -->
        <section id="results" class="results-section hidden">
            <h2>Your Tailored Business Ideas</h2>
            <div id="resultsContainer">
                <!-- Results will be dynamically inserted here -->
            </div>
            <a href="#payment" class="cta">Unlock Full Plan</a>
        </section>

        <!-- Payment Section -->
        <section id="payment" class="payment-section">
            <h2>Ready to Start Your Journey?</h2>
            <p>Access detailed business plans for just $10/month or $90/year.</p>
            <form action="https://your-payment-gateway.com" method="POST">
                <button type="submit" class="cta">Subscribe Now</button>
            </form>
        </section>
    </main>

    <footer>
        <p>© 2024 BossBuilder. All Rights Reserved.</p>
    </footer>
</body>
</html>
