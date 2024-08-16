# Portfolio Website

Welcome to my personal portfolio website! This website showcases my projects, skills, and experiences. It's built with HTML, CSS, and JavaScript, and it's hosted on GitHub Pages with a custom domain name.

## Features

- **Responsive Design**: The website is fully responsive, making it accessible and visually appealing on all devices.
- **Projects Showcase**: A dedicated section to showcase my projects with preview images and links to their GitHub repositories.
- **Contact Form**: A functional contact form for visitors to get in touch with me.
- **Google Analytics**: Integrated Google Analytics to track and analyze website traffic.
- **Custom Domain Name**: The website is accessible through a custom domain name.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **GitHub Pages**
- **Google Analytics**

## Setup and Deployment

### Prerequisites

- A GitHub account
- A domain name (optional but recommended for a custom domain setup)

### Steps to Set Up Locally

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/Portfolio-Website.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Portfolio-Website
   ```

3. **Open `index.html` in Your Browser**:

   You can open the `index.html` file directly in your browser to view the website locally.

### Deploying to GitHub Pages

1. **Push Your Code to GitHub**:

   Make sure your changes are committed and pushed to your GitHub repository.

   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin master
   ```

2. **Configure GitHub Pages**:

   - Go to your repository on GitHub.
   - Click on the "Settings" tab.
   - Scroll down to the "Pages" section.
   - Under "Source," select the branch you want to deploy (e.g., `master`).
   - Click "Save."

3. **Set Up a Custom Domain Name (Optional)**:

   - Purchase a domain name from a domain registrar.
   - Configure the DNS settings to point to GitHub Pages. Typically, you'll need to set up an `A` record and a `CNAME` record.
   - Add your custom domain name in the GitHub Pages settings under "Custom domain."

### Integrating Google Analytics

1. **Create a Google Analytics Account**:

   - Sign up for Google Analytics at [analytics.google.com](https://analytics.google.com/).
   - Create a new property for your website.

2. **Add the Tracking Code**:

   - Google Analytics will provide you with a tracking code.
   - Add this tracking code to the `<head>` section of your `index.html` file.

   ```html
   <head>
     <!-- Google Analytics -->
     <script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID"></script>
     <script>
       window.dataLayer = window.dataLayer || [];
       function gtag(){dataLayer.push(arguments);}
       gtag('js', new Date());
       gtag('config', 'YOUR_TRACKING_ID');
     </script>
     <!-- End Google Analytics -->
     ...
   </head>
   ```

## Contact

If you have any questions or suggestions, feel free to reach out to me via the contact form on my website or directly through my email: [cyrilobouharb@outlook.com](mailto:cyrilobouharb@outlook.com).

