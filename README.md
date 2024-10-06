# IT_Project_Richfield
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
		.clickable-name{
		cursor:pointer;
		text-decoration:underline;
		}
		
        nav ul {
            list-style: none;
            display: flex;
			overflow: hidden;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
			display:block;
            font-weight: bold;
        }
		.nav a: hover{
		color:#eae7dc;
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
		.line-container{
		display:flex;
		align-item:center;
		}
		.word{
		margin-right;50px;
		
		}
		.dot-listing{
		list-style-type:disc;
		}
		.dpt-listing li{
		display:inline:
		margin-right:10px;
		}

        /* Donation Section */
        #donate-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
			background-color:#eae7dc ;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
			padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 600px;
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
			padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 600px;
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
			padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 600px;
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
		.form-container{
		display:none;
		padding:20px;
		border:1px solid #ccc;
		margin-top:10px;
		}
		.subtopic{
		cursor:pointer;
		color:blue;
		text-decoderation:underline;
		}
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
		.grid-container{
		display:grid;
		grid-template-columns:1fr 1fr 1fr;
		grid-template-rows:auto;
		gap:10px;
		}
		.grid-item{
		padding:20px;
		text-aign:center;
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
                <li><a href="#donate" class="clickable-name" onclick="show Donation Form()">Donation</a></li>
                <li><a href="#payment" class="clickable-name" onclick="show Payment form()">Payment</a></li>
                <li><a href="#home" class="clickable-name" onclick="show home()">Home</a></li>
                <li><a href="#matchup" class="clickable-name" onclick="show matchup form()">Match Up</a></li>
            </ul>
        </nav>
        <div class="login"><a href="#">Log In</a></div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Home Section -->
        <section id="home">
            <h2>Welcome to Kindred Hearts</h2>
            <p strong><b>We connect generous donors with</br> children in need. Learn more about our</br> causes and how you can contribute</b></p strong>
        </section>
<!-- image section-->
<div class="image-text-container" >
            <img src="donat.png" width="400" height="400" >
			<p><b>WHY</br> DONATE?</br></br>you can make a difference in the</br>   lives of these children and help</br>ensure they have access to they<br> need to thrive.</b></p>
        </div></br></br></br>
		
		<body>
<title>Children Adoption Awareness</title>
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
		
		<div class="grid-container">	<a href="https://www.motherschoice.org " class="link-thumbnail"target="_blank"><img src="motherschoice.png">MothersChoice In Adoption</a></div>
			<div class="grid-item"><a href="https://www,savethechildren,org.za" class="link-thumbnail"><img src="save.png">Become A Volunteer</a></div>
			<div class="grid-item"><a href="https://www.psychologytoday,com " class="link-thumbnail"target="_blank"><img src="child.png">I Have Adopted Child</a></div>
			<div class="grid-item"><a href="https://www.verywellmind.com" class="link-thumbnail"><img src="national.png">Mental Health Effects</a></div>
			<div class="grid-item"><a href="https://www.bbc.com " class="link-thumbnail"target="_blank"><img src="thrive.png">Adopted Children Thrive</a></div>
			<div class="grid-item"><a href="https://www.allforkids.org" class="link-thumbnail"><img src="adopt.png">Your Adopted Child's Emotional</a></div>
			</div>
    </div>
</main>
        <!-- Donation Section -->
				<div class="line-container">
				
			<span class="word">We Accept?&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
			<ul class="dot-listing">
			<li>Baby Essentials</li>
			<li>Toys</li>
			<li>School Essentials</li>
			<li>Food</li>
			<li>Vouchers</li>
			</ul></div></br></br></br>
		<div id="form-container" >
        <section id="donate">
		            <h2 align="center">Donation Form</h2>
			
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
					<option value="vouchers">vouchers</option>
					<option value="Baby Essentials">Baby Essentials</option>
                </select>

                <label for="message">Message (Optional):</label>
                <textarea id="message" name="message" rows="4"></textarea>
				<button type="submit">Submit Donation</button>
				<div class="line-container">
				<span class="word" ><strong><b> Contribute&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span></strong></b>
		<div class="line-container">
		  <p><u>We Accept Currency</u></br></br><b>Bank Name:</b>FNB</br><b>Account Name:</b>Kindred Money</br><b>Account Number:</b> 00000 000 000</br><b>Branch:</b> 00000</br><b>Account Type:</b>Savings Account</br></p></div>
		  

                
            </form>
			</div>
        </section>

        <!-- Payment Section -->
        <section id="payment">
            <h2 align="center">Payment Form</h2>
            <form id="payment-form"align="center">
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
            <h2 align="center">Match Up Form</h2>
           
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2035 Kindred Hearts. All rights reserved.</p>
        <p>Contact us: info@kindredhearts.com | 123-555-5555</p>
			<img src="logo.jpg"  width="70" height="70"><a href="#home" style="color: inherit; text-decoration: none;">
    </footer>
	
</body>
<script>
    document.getElementById('infoButton').addEventListener('click', function() {
        const adoptionInfo = document.getElementById('adoptionInfo');
        adoptionInfo.style.display = adoptionInfo.style.display === 'none' || adoptionInfo.style.display === '' ? 'block' : 'none';
    });
</script>
</html>

# IT_Project_Richfield_admin

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
			background-image: url('logo.jpg'); /* Path to your image */
            background-size: cover; /* Cover the entire viewport */
            background-position: center; /* Center the image */
			
        }
        nav {
            margin-bottom: 20px;
        }
        nav button {
            margin-right: 10px;
            padding: 10px 15px;
           background-color: #e98074;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        nav button:hover {
            background-color: #ede8f5;
        }
        .form-section {
            display: none; /* Hide all sections by default */
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="text"], input[type="email"], input[type="number"] {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button.submit {
            padding: 10px 15px;
            background-color:#e98074  ;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button.submit:hover {
            background-color: #ede8f5;
        }
		  
    </style>
</head>
<body >

<h1>Admin Dashboard</h1>

<nav>
    <button onclick="showSection('manageUsers')">Manage Users</button>
    <button onclick="showSection('manageChildren')">Manage Children</button>
    <button onclick="showSection('manageAdoption')">Manage Adoption</button>
    <button onclick="showSection('generateReports')">Generate Reports</button>
    <button onclick="showSection('logout')">Log Out</button>
</nav>

<!-- Manage Users Section -->
<div id="manageUsers" class="form-section">
    <h2>Manage Users</h2>
    <form>
        <input type="text" name="username" placeholder="Username" required>
        <input type="email" name="email" placeholder="Email" required>
        <button type="submit" class="submit">Add User</button>
    </form>
</div>

<!-- Manage Children Section -->
<div id="manageChildren" class="form-section">
    <h2>Manage Children</h2>
    <form>
        <input type="text" name="childName" placeholder="Child's Name" required>
        <input type="number" name="age" placeholder="Age" required>
        <input type="text" name="gender" placeholder="Gender" required>
        <button type="submit" class="submit">Add Child</button>
    </form>
</div>

<!-- Manage Adoption Section -->
<div id="manageAdoption" class="form-section">
    <h2>Manage Adoption</h2>
    <form>
        <input type="text" name="adoptiveParent" placeholder="Adoptive Parent's Name" required>
        <input type="text" name="childToAdopt" placeholder="Child's Name" required>
        <button type="submit" class="submit">Process Adoption</button>
    </form>
</div>

<!-- Generate Reports Section -->
<div id="generateReports" class="form-section">
    <h2>Generate Reports</h2>
    <form>
        <input type="text" name="reportType" placeholder="Report Type (e.g., Adoption, Children)" required>
        <button type="submit" class="submit">Generate Report</button>
    </form>
</div>

<!-- Log Out Section -->
<div id="logout" class="form-section">
    <h2>Log Out</h2>
    <form>
        <button type="submit" class="submit">Log Out</button>
    </form>
</div>

<script>
    function showSection(sectionId) {
        // Hide all sections
        const sections = document.querySelectorAll('.form-section');
        sections.forEach(section => section.style.display = 'none');
        
        // Show the selected section
        document.getElementById(sectionId).style.display = 'block';
    }
</script>

</body>
</html>
