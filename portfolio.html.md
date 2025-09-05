# Untitled

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Clean Portfolio</title>
<link rel="stylesheet" href="[https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css)">
<style>
* {
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

```
    :root {
        --primary: #2563eb;
        --secondary: #4f46e5;
        --dark: #1e293b;
        --light: #f8fafc;
        --gray: #64748b;
    }

    body {
        background-color: #f1f5f9;
        color: var(--dark);
        line-height: 1.6;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
    }

    /* Header */
    header {
        background: linear-gradient(135deg, var(--primary), var(--secondary));
        color: white;
        padding: 20px 0;
        position: fixed;
        width: 100%;
        top: 0;
        z-index: 100;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .logo {
        font-size: 1.8rem;
        font-weight: 700;
    }

    .nav-links {
        display: flex;
        list-style: none;
    }

    .nav-links li {
        margin-left: 30px;
    }

    .nav-links a {
        color: white;
        text-decoration: none;
        font-weight: 500;
        transition: all 0.3s ease;
    }

    .nav-links a:hover {
        color: #e0f2fe;
    }

    /* Hero Section */
    .hero {
        padding: 150px 0 100px;
        text-align: center;
        background: linear-gradient(rgba(37, 99, 235, 0.9), rgba(79, 70, 229, 0.9)), url('<https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1500&q=80>');
        background-size: cover;
        background-position: center;
        color: white;
    }

    .hero h1 {
        font-size: 3.5rem;
        margin-bottom: 20px;
    }

    .hero p {
        font-size: 1.5rem;
        max-width: 700px;
        margin: 0 auto 30px;
    }

    .btn {
        display: inline-block;
        background: white;
        color: var(--primary);
        padding: 12px 30px;
        border-radius: 30px;
        text-decoration: none;
        font-weight: 600;
        transition: all 0.3s ease;
    }

    .btn:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
    }

    /* Projects Section */
    .section {
        padding: 80px 0;
    }

    .section-title {
        text-align: center;
        margin-bottom: 60px;
    }

    .section-title h2 {
        font-size: 2.5rem;
        color: var(--dark);
        margin-bottom: 15px;
    }

    .section-title p {
        color: var(--gray);
        max-width: 600px;
        margin: 0 auto;
    }

    .projects-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 30px;
    }

    .project-card {
        background: white;
        border-radius: 10px;
        overflow: hidden;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease;
    }

    .project-card:hover {
        transform: translateY(-10px);
    }

    .project-img {
        height: 200px;
        background-color: #ddd;
        background-position: center;
        background-size: cover;
    }

    .project-info {
        padding: 20px;
    }

    .project-info h3 {
        margin-bottom: 10px;
        color: var(--dark);
    }

    .project-info p {
        color: var(--gray);
        margin-bottom: 15px;
    }

    .project-link {
        color: var(--primary);
        text-decoration: none;
        font-weight: 600;
        display: inline-flex;
        align-items: center;
    }

    .project-link i {
        margin-left: 5px;
    }

    /* About Section */
    .about {
        background-color: white;
    }

    .about-content {
        display: flex;
        align-items: center;
        gap: 50px;
    }

    .about-img {
        flex: 1;
        height: 400px;
        background-color: #ddd;
        border-radius: 10px;
        background-image: url('<https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80>');
        background-size: cover;
        background-position: center;
    }

    .about-text {
        flex: 1;
    }

    .about-text h2 {
        font-size: 2.2rem;
        margin-bottom: 20px;
        color: var(--dark);
    }

    .about-text p {
        margin-bottom: 15px;
        color: var(--gray);
    }

    .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
        margin-top: 20px;
    }

    .skill {
        background: #e0f2fe;
        color: var(--primary);
        padding: 5px 15px;
        border-radius: 20px;
        font-size: 0.9rem;
    }

    /* Contact Section */
    .contact {
        text-align: center;
    }

    .contact-form {
        max-width: 600px;
        margin: 0 auto;
    }

    .form-group {
        margin-bottom: 20px;
    }

    .form-control {
        width: 100%;
        padding: 15px;
        border: 1px solid #ddd;
        border-radius: 5px;
        font-size:

```