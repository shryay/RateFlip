<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Currency Converter Web App built with React and deployed on Vercel">
    <title>Currency Converter Web App</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background: #0073e6;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #0073e6;
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        h3 {
            color: #333;
            font-size: 1.4rem;
            margin-bottom: 15px;
        }

        ul {
            margin: 10px 0;
            padding-left: 20px;
        }

        li {
            font-size: 1.1rem;
            margin: 5px 0;
        }

        .card {
            background: #f9f9f9;
            padding: 20px;
            margin: 15px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
        }

        .card h3 {
            font-size: 1.3rem;
        }

        .button {
            background: #0073e6;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }

        .button:hover {
            background: #005bb5;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 10px;
            background: #f4f4f4;
        }
    </style>
</head>
<body>

<header>
    <h1>Currency Converter Web App</h1>
</header>

<div class="container">
    <h2>Overview</h2>
    <p>The Currency Converter Web App is a responsive and intuitive app built with <strong>React.js</strong> and integrated with a live exchange rate API. It allows users to convert between different currencies in real-time with an easy-to-use interface.</p>

    <div class="card">
        <h3>Features</h3>
        <ul>
            <li><strong>Real-time Currency Conversion:</strong> Fetches live exchange rates using the ExchangeRate-API.</li>
            <li><strong>Responsive Design:</strong> Fully responsive UI that adapts to all screen sizes.</li>
            <li><strong>Currency Swap:</strong> Easily swap between the "From" and "To" currencies.</li>
            <li><strong>Custom Input Components:</strong> Reusable input box components for handling both amount and currency selections.</li>
            <li><strong>Clean UI/UX:</strong> Styled using Tailwind CSS for a sleek, modern, and user-friendly design.</li>
        </ul>
    </div>

    <div class="card">
        <h3>Tech Stack</h3>
        <ul>
            <li><strong>Frontend:</strong> React.js, Tailwind CSS</li>
            <li><strong>API:</strong> <a href="https://www.exchangerate-api.com/" target="_blank">ExchangeRate-API</a></li>
            <li><strong>Deployment:</strong> Vercel (CI/CD)</li>
            <li><strong>Docker:</strong> Used for containerization</li>
        </ul>
    </div>

    <div class="card">
        <h3>Installation</h3>
        <p>Follow the steps below to set up the project locally:</p>
        <ul>
            <li><strong>Clone the repository:</strong>
                <pre><code>git clone https://github.com/your-username/currency-converter.git</code></pre>
            </li>
            <li><strong>Install dependencies:</strong>
                <pre><code>npm install</code></pre>
            </li>
            <li><strong>Run the app locally:</strong>
                <pre><code>npm start</code></pre>
                <p>The app will be accessible at <code>http://localhost:3000</code>.</p>
            </li>
        </ul>
    </div>

    <div class="card">
        <h3>Deployment</h3>
        <p>The project is deployed on <strong>Vercel</strong>. You can access the live app here:</p>
        <p><a href="https://your-app.vercel.app" class="button" target="_blank">Live Demo</a></p>
    </div>

    <div class="card">
        <h3>Docker Setup</h3>
        <p>This project is containerized using Docker. To run the project inside a Docker container:</p>
        <ul>
            <li><strong>Build the Docker image:</strong>
                <pre><code>docker build -t currency-converter .</code></pre>
            </li>
            <li><strong>Run the Docker container:</strong>
                <pre><code>docker run -p 3000:80 currency-converter</code></pre>
            </li>
            <li>The app will be accessible at <code>http://localhost:3000</code>.</li>
        </ul>
    </div>

    <div class="card">
        <h3>CI/CD with GitHub Actions</h3>
        <p>The project uses GitHub Actions for CI/CD. Every push to the <code>main</code> branch triggers the build and deployment process, ensuring that the latest changes are automatically reflected in the live app.</p>
    </div>

    <div class="card">
        <h3>Contributions</h3>
        <p>Contributions are welcome! If you'd like to contribute to this project, follow the steps below:</p>
        <ul>
            <li>Fork the repository.</li>
            <li>Create your feature branch: <code>git checkout -b feature-name</code></li>
            <li>Commit your changes: <code>git commit -am 'Add new feature'</code></li>
            <li>Push to the branch: <code>git push origin feature-name</code></li>
            <li>Create a new Pull Request.</li>
        </ul>
    </div>

    <div class="card">
        <h3>License</h3>
        <p>This project is open-source and available under the <a href="LICENSE" target="_blank">MIT License</a>.</p>
    </div>
</div>

<footer class="footer">
    <p>Developed by <strong>Your Name</strong> &copy; 2024</p>
</footer>

</body>
</html>
