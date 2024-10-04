# IT_Project_Richfield
(DONATION,PAYMENT,HOME & MATCH UP)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><img src="logo.jpg">Kindred Hearts - Donation Platform</title>
    <style>
	.title_container{
	display:flex;
	align-items:center;
	}
	.title_container img{
	margin-right:20pz;
	}
	.image-text-container {
            display: flex;
            align-items: center; 
        }
        .image-text-container img {
            margin-right: 15px; 
        }
        .image-text-container p {
            margin: 0; 
        }
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #ede8f5;
            color: #333;
            scroll-behavior: smooth;
        }

        /* Header */
        header {
            background-color: #e98074;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #fff;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }

        .login a {
            text-decoration: none;
            color: #fff;
            background-color: #eae7dc;
            padding: 10px 20px;
            border-radius: 20px;
        }

        header a:hover {
            opacity: 0.8;
        }

        /* Main Content */
        main {
            padding: 20px;
        }

        section {
            margin-bottom: 50px;
        }

        h2 {
            margin-bottom: 20px;
            color: #e98074;
        }

        /* Donation Section */
        #donate-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
			background-color:#eae7dc ;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        #donate-form input, #donate-form select, #donate-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        /* Payment Section */
        #payment-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
			background-color:#eae7dc ;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        #payment-form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        /* Match Up Section */
        #matchup-form {
            background-color: #fff;
            padding: 20px;
			background-color:#eae7dc ;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        #matchup-form input, #matchup-form select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
			
            border: 1px solid #ccc;
        }

        /* Buttons */
        button {
            padding: 10px 20px;
            background-color: #e98074;
            color: #fff;
            border: none;
            border-radius: 20px;
            cursor: pointer;
            font-weight: bold;
        }

        button:hover {
            opacity: 0.9;
        }

        /* Footer */
        footer {
            background-color: #e98074;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: flex-start;
            }

            nav ul {
                flex-direction: column;
                gap: 10px;
            }

            button, input, textarea {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
		<img src="logo.jpg"  width="50" height="50"><a href="#home" style="color: inherit; text-decoration: none;">Kindred Hearts</a></div>
        <nav>
            <ul>
                <li><a href="#donate">Donation</a></li>
                <li><a href="#payment">Payment</a></li>
                <li><a href="#home">Home</a></li>
                <li><a href="#matchup">Match Up</a></li>
            </ul>
        </nav>
        <div class="login"><a href="#">Log In</a></div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Home Section -->
        <section id="home">
            <h2>Welcome to Kindred Hearts</h2>
            <p>We connect generous donors with children in need. Learn more about our causes and how you can contribute.</p>
        </section>

        <!-- Donation Section -->
        <section id="donate">
            <h2>Donation Form</h2>
			</div>
			<div class="image-text-container">
            <img src="donat.png" width="1000" height="500" >
			<p><b>WHY</br> DONATE?</br></br>you can make a difference in the</br>   lives of these children and help</br>ensure they have access to they<br> need to thrive.</b></p>
        </div>
            <form id="donate-form">
			                <label for="donor-name">Donor Name:</label>
                <input type="text" id="donor-name" name="donor-name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="donation-type">Type of Donation:</label>
                <select id="donation-type" name="donation-type">
                    <option value="money">Money</option>
                    <option value="toys">Toys</option>
                    <option value="clothes">Clothes</option>
                    <option value="school-supplies">School Supplies</option>
                </select>

                <label for="message">Message (Optional):</label>
                <textarea id="message" name="message" rows="4"></textarea>

                <button type="submit">Submit Donation</button>
            </form>
			
        </section>

        <!-- Payment Section -->
        <section id="payment">
            <h2>Payment Form</h2>
            <form id="payment-form">
                <label for="payer-name">Payer Name:</label>
                <input type="text" id="payer-name" name="payer-name" required>

                <label for="payment-amount">Payment Amount:</label>
                <input type="number" id="payment-amount" name="payment-amount" required>

                <label for="payment-method">Payment Method:</label>
                <select id="payment-method" name="payment-method">
                    <option value="credit-card">Credit Card</option>
                    <option value="debit-card">Debit Card</option>
                    <option value="bank-transfer">Bank Transfer</option>
                </select>

                <button type="submit">Make Payment</button>
            </form>
        </section>

        <!-- Match Up Section -->
        <section id="matchup">
            <h2>Match Up Form</h2>
            <form id="matchup-form">
                <label for="parent-name">Parent Name:</label>
                <input type="text" id="parent-name" name="parent-name" required>

                <label for="child-age">Child's Age:</label>
                <input type="number" id="child-age" name="child-age" required>

                <label for="preferences">Match Preferences:</label>
                <select id="preferences" name="preferences">
                    <option value="age-group">Age Group</option>
                    <option value="location">Location</option>
                    <option value="support">Type of Support</option>
                </select>

                <button type="submit">Submit Match Up</button>
            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2035 Kindred Hearts. All rights reserved.</p>
        <p>Contact us: info@kindredhearts.com | 123-555-5555</p>
    </footer>
</body>
</html>

E-SERVICE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Children Adoption Awareness</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ede8f5;
            margin: 0;
            padding: 20px;
        }
        header {
            background-color: #e98074;
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 8px;
        }
        main {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 600px;
        }
        h2 {
            color: #333;
        }
        p {
            line-height: 1.6;
        }
        button {
            background-color: #e98074;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #d37065;
        }
        .adoption-info {
            display: none;
            margin-top: 20px;
            background-color: #f9f5f5;
            border: 1px solid #e98074;
            padding: 15px;
            border-radius: 5px;
        }
		  .link-thumbnail {
            display: inline-block; 
            text-align: center; 
            width: 150px;
            margin: 20px;
            text-decoration: none; 
            color: #333; 
            font-family: Arial, sans-serif;
        }

        .link-thumbnail img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
        }

        .link-thumbnail span {
            display: block; 
            margin-top: 10px;
            font-size: 16px;
        }
    </style>
</head>
<body>

<header>
    <h1>Children Adoption Awareness</h1>
</header>

<main>
    <h2>Understanding Child Adoption</h2>
    <p>
        Adoption is a legal process that allows individuals or couples to become the legal parents of a child who is not biologically their own. 
        It provides children with a stable and loving family environment and offers them a chance for a better future.
    </p>
    <button id="infoButton">Learn More</button>
    <div id="adoptionInfo" class="adoption-info">
        <h3>How Adoption Works</h3>
        <p><strong>1. Types of Adoption:</strong> There are various types of adoption including domestic, international, and foster care adoption.</p>
        <p><strong>2. The Process:</strong> The adoption process typically involves home studies, background checks, and legal proceedings.</p>
        <p><strong>3. Support Systems:</strong> Many agencies offer resources and support for prospective adoptive parents.</p>
        <p><strong>4. Post-Adoption:</strong> Ongoing support can help families adjust after adoption and maintain healthy relationships.</p>
		
			<a href="https://www.motherschoice.org " class="link-thumbnail"target="_blank"><img src="motherschoice.png">MothersChoice In Adoption</a>
			<a href="https://www,savethechildren,org.za" class="link-thumbnail"><img src="save.png">Become A Volunteer</a>
			<a href="https://www.psychologytoday,com " class="link-thumbnail"target="_blank"><img src="child.png">I Have Adopted Child</a>
			<a href="https://www.verywellmind.com" class="link-thumbnail"><img src="national.png">Mental Health Effects</a>
			<a href="https://www.bbc.com " class="link-thumbnail"target="_blank"><img src="thrive.png">Adopted Children Thrive</a>
			<a href="https://www.allforkids.org" class="link-thumbnail"><img src="adopt.png">Your Adopted Child's Emotional</a>
    </div>
</main>

<script>
    document.getElementById('infoButton').addEventListener('click', function() {
        const adoptionInfo = document.getElementById('adoptionInfo');
        adoptionInfo.style.display = adoptionInfo.style.display === 'none' || adoptionInfo.style.display === '' ? 'block' : 'none';
    });
</script>

</body>
</html>

