<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currency Converter Web App</title>
</head>
<body>
    <header>
        <h1>Currency Converter Web App</h1>
    </header>

    <div>
        <h2>Overview</h2>
        <p>The Currency Converter Web App is a responsive and intuitive app built with React.js and integrated with a live exchange rate API. It allows users to convert between different currencies in real-time with an easy-to-use interface.</p>
    </div>

    <div>
        <h3>Features</h3>
        <ul>
            <li><strong>Real-time Currency Conversion:</strong> Fetches live exchange rates using the ExchangeRate-API.</li>
            <li><strong>Responsive Design:</strong> Fully responsive UI that adapts to all screen sizes.</li>
            <li><strong>Currency Swap:</strong> Easily swap between the "From" and "To" currencies.</li>
            <li><strong>Custom Input Components:</strong> Reusable input box components for handling both amount and currency selections.</li>
            <li><strong>Clean UI/UX:</strong> Styled using Tailwind CSS for a sleek, modern, and user-friendly design.</li>
        </ul>
    </div>

    <div>
        <h3>Tech Stack</h3>
        <ul>
            <li><strong>Frontend:</strong> React.js, Tailwind CSS</li>
            <li><strong>API:</strong> <a href="https://www.exchangerate-api.com/" target="_blank">ExchangeRate-API</a></li>
            <li><strong>Deployment:</strong> Vercel (CI/CD)</li>
            <li><strong>Docker:</strong> Used for containerization</li>
        </ul>
    </div>

    <div>
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

    <div>
        <h3>Deployment</h3>
        <p>The project is deployed on <strong>Vercel</strong>. You can access the live app here:</p>
        <p><a href="https://your-app.vercel.app" target="_blank">Live Demo</a></p>
    </div>

    <div>
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

    <div>
        <h3>CI/CD with GitHub Actions</h3>
        <p>The project uses GitHub Actions for CI/CD. Every push to the <code>main</code> branch triggers the build and deployment process, ensuring that the latest changes are automatically reflected in the live app.</p>
    </div>

    <div>
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

    <div>
        <h3>License</h3>
        <p>This project is open-source and available under the <a href="LICENSE" target="_blank">MIT License</a>.</p>
    </div>

    <footer>
        <p>Developed by Your Name © 2024</p>
    </footer>
</body>
</html>
