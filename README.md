<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conscious Beauty Finder</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f2ec;
            color: #333;
        }

        header {
            background-color: #ffad8e;
            color: #fff;
            text-align: center;
            padding: 2em;
        }

        section {
            max-width: 800px;
            margin: 2em auto;
            padding: 2em;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 0.5em;
            font-weight: bold;
            color: #333;
        }

        input {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            box-sizing: border-box;
        }

        button {
            background-color: #77bb6c;
            color: #fff;
            border: none;
            padding: 0.5em 1em;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #5f995e;
        }
    </style>
</head>
<body>

    <header>
        <h1>Conscious Beauty Finder</h1>
        <p>Discover accessible, sustainable, and inclusive beauty salons near you!</p>
    </header>

    <section>
        <h2>Join Our Directory</h2>
        <p>Be part of the Conscious Beauty Finder! Fill out the form below to receive more information when we launch.</p>

        <form id="salonForm">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="businessName">Business Name:</label>
            <input type="text" id="businessName" name="businessName" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="location">Location:</label>
            <input type="text" id="location" name="location" required>

            <button type="submit">Submit</button>
        </form>
    </section>

    <script>
        document.getElementById('salonForm').addEventListener('submit', function(event) {
            event.preventDefault();

            // You can add logic here to handle the form data, for example, send it to a backend server.
            // For now, let's just display a success message.
            alert('Thank you! We will contact you with more information when the Conscious Beauty Finder launches.');
        });
    </script>

</body>
</html>
