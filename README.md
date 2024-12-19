# **Currency Converter Web App**

## **Overview**

The **Currency Converter Web App** is a responsive and intuitive application built with React.js and integrated with a live exchange rate API. This app allows users to convert between different currencies in real-time with a clean and user-friendly interface.

---

## **Features**

- **Real-time Currency Conversion**: The app fetches live exchange rates using the [ExchangeRate-API](https://www.exchangerate-api.com/).
- **Responsive Design**: The UI is fully responsive, ensuring a smooth experience on all screen sizes, from mobile to desktop.
- **Currency Swap**: Users can easily swap the "From" and "To" currencies with a single click.
- **Custom Input Components**: The app features reusable input box components for both amount and currency selection, promoting clean and modular code.
- **Clean UI/UX**: The interface is styled using Tailwind CSS for a modern and user-friendly design that adapts to user needs.

---

## **Tech Stack**

- **Frontend**: React.js, Tailwind CSS
- **API**: [ExchangeRate-API](https://www.exchangerate-api.com/)
- **Deployment**: Vercel (CI/CD for seamless updates)
- **Containerization**: Docker for efficient containerization of the app

---

## **Installation Guide**

Follow these steps to set up the project locally:

**Clone the repository**:
```bash
git clone https://github.com/your-username/currency-converter.git
```

Install the dependencies:
```bash
npm install
```
Run the app locally:
```bash
npm start
```
Once the app starts, it will be available at: http://localhost:3000.

**Deployment**
The project is deployed on Vercel. You can access the live version of the app here:https://rate-flip.vercel.app/

**Docker Setup**
This project is containerized using Docker. To run the project inside a Docker container:

Build the Docker image:
```bash
docker build -t currency-converter .
```

Run the Docker container:
```bash
docker run -p 3000:80 currency-converter
```

Once the container is running, the app will be accessible at: http://localhost:3000.

**CI/CD with GitHub Actions**
This project uses GitHub Actions for continuous integration and continuous deployment (CI/CD). With every push to the main branch, the build and deployment process is automatically triggered, ensuring that the latest changes are reflected on the live app without manual intervention.

**License**
This project is open-source and available under the MIT License.

Developed by Shreya Upadhyay © 2024
