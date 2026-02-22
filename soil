<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Tariq Aziz | Soil Scientist & Environmental Researcher</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-color: #2c5f2d;
            --secondary-color: #97bc62;
            --accent-color: #1a3a1c;
            --text-dark: #333;
            --text-light: #666;
            --bg-light: #f8f9fa;
            --bg-white: #ffffff;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --shadow-hover: 0 8px 15px rgba(0, 0, 0, 0.15);
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--bg-light);
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: var(--bg-white);
            box-shadow: var(--shadow);
            z-index: 1000;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .nav-brand {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-color);
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--text-dark);
            font-weight: 500;
            transition: color 0.3s ease;
            font-size: 0.95rem;
        }

        .nav-links a:hover {
            color: var(--primary-color);
        }

        .mobile-menu {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--primary-color) 0%, var(--secondary-color) 100%);
            color: white;
            padding: 8rem 5% 4rem;
            text-align: center;
            min-height: 70vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .hero-content {
            max-width: 900px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            animation: fadeInUp 0.8s ease;
        }

        .hero .title {
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            opacity: 0.9;
            animation: fadeInUp 0.8s ease 0.2s both;
        }

        .hero .affiliation {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            opacity: 0.85;
            animation: fadeInUp 0.8s ease 0.4s both;
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            animation: fadeInUp 0.8s ease 0.6s both;
        }

        .btn {
            padding: 0.8rem 2rem;
            border: none;
            border-radius: 50px;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .btn-primary {
            background: white;
            color: var(--primary-color);
        }

        .btn-secondary {
            background: transparent;
            color: white;
            border: 2px solid white;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-hover);
        }

        /* Section Styles */
        section {
            padding: 5rem 5%;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
        }

        .section-title h2 {
            font-size: 2.2rem;
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }

        .section-title .underline {
            width: 80px;
            height: 4px;
            background: var(--secondary-color);
            margin: 0 auto;
            border-radius: 2px;
        }

        /* About Section */
        .about {
            background: var(--bg-white);
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 3rem;
            align-items: start;
        }

        .about-image {
            text-align: center;
        }

        .about-image img {
            width: 100%;
            max-width: 300px;
            border-radius: 10px;
            box-shadow: var(--shadow);
        }

        .about-text p {
            margin-bottom: 1.5rem;
            color: var(--text-light);
            font-size: 1.05rem;
        }

        .about-stats {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .stat-box {
            text-align: center;
            padding: 1.5rem;
            background: var(--bg-light);
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .stat-box:hover {
            transform: translateY(-5px);
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary-color);
        }

        .stat-label {
            color: var(--text-light);
            font-size: 0.9rem;
        }

        /* Positions Section */
        .positions {
            background: var(--bg-light);
        }

        .positions-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .position-card {
            background: var(--bg-white);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            border-left: 4px solid var(--primary-color);
        }

        .position-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
        }

        .position-card h3 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
            font-size: 1.3rem;
        }

        .position-card .institution {
            font-weight: 600;
            color: var(--text-dark);
            margin-bottom: 0.5rem;
        }

        .position-card .period {
            color: var(--text-light);
            font-size: 0.9rem;
            margin-bottom: 1rem;
        }

        .position-card p {
            color: var(--text-light);
            font-size: 0.95rem;
        }

        /* Research Interests */
        .research {
            background: var(--bg-white);
        }

        .research-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        .research-card {
            padding: 2rem;
            background: var(--bg-light);
            border-radius: 10px;
            transition: all 0.3s ease;
            text-align: center;
        }

        .research-card:hover {
            transform: translateY(-5px);
            background: var(--primary-color);
            color: white;
        }

        .research-card:hover .research-icon {
            color: white;
        }

        .research-icon {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 1rem;
            transition: color 0.3s ease;
        }

        .research-card h3 {
            margin-bottom: 0.8rem;
            font-size: 1.1rem;
        }

        .research-card p {
            font-size: 0.9rem;
            color: var(--text-light);
        }

        .research-card:hover p {
            color: rgba(255, 255, 255, 0.85);
        }

        /* Publications Section */
        .publications {
            background: var(--bg-light);
        }

        .publication-filters {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-bottom: 2rem;
            flex-wrap: wrap;
        }

        .filter-btn {
            padding: 0.6rem 1.5rem;
            border: 2px solid var(--primary-color);
            background: transparent;
            color: var(--primary-color);
            border-radius: 25px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 500;
        }

        .filter-btn.active,
        .filter-btn:hover {
            background: var(--primary-color);
            color: white;
        }

        .publications-list {
            max-width: 1000px;
            margin: 0 auto;
        }

        .publication-item {
            background: var(--bg-white);
            padding: 1.5rem;
            margin-bottom: 1rem;
            border-radius: 8px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            border-left: 3px solid transparent;
        }

        .publication-item:hover {
            border-left-color: var(--primary-color);
            transform: translateX(5px);
        }

        .publication-item h4 {
            color: var(--text-dark);
            margin-bottom: 0.5rem;
            font-size: 1.05rem;
        }

        .publication-item .authors {
            color: var(--text-light);
            font-size: 0.9rem;
            margin-bottom: 0.3rem;
        }

        .publication-item .journal {
            color: var(--primary-color);
            font-weight: 600;
            font-size: 0.95rem;
        }

        .publication-item .meta {
            display: flex;
            gap: 1rem;
            margin-top: 0.8rem;
            font-size: 0.85rem;
            color: var(--text-light);
        }

        .publication-item .links {
            margin-top: 1rem;
        }

        .pub-link {
            display: inline-block;
            padding: 0.4rem 1rem;
            background: var(--bg-light);
            color: var(--primary-color);
            text-decoration: none;
            border-radius: 5px;
            font-size: 0.85rem;
            margin-right: 0.5rem;
            transition: all 0.3s ease;
        }

        .pub-link:hover {
            background: var(--primary-color);
            color: white;
        }

        /* Projects Section */
        .projects {
            background: var(--bg-white);
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .project-card {
            background: var(--bg-light);
            border-radius: 10px;
            overflow: hidden;
            transition: all 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
        }

        .project-header {
            background: var(--primary-color);
            color: white;
            padding: 1.5rem;
        }

        .project-header h3 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
        }

        .project-header span {
            font-size: 0.85rem;
            opacity: 0.85;
        }

        .project-body {
            padding: 1.5rem;
        }

        .project-body p {
            color: var(--text-light);
            font-size: 0.95rem;
            margin-bottom: 1rem;
        }

        .project-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
        }

        .tag {
            padding: 0.3rem 0.8rem;
            background: var(--secondary-color);
            color: var(--accent-color);
            border-radius: 15px;
            font-size: 0.8rem;
            font-weight: 500;
        }

        /* Events Section */
        .events {
            background: var(--bg-light);
        }

        .events-timeline {
            max-width: 900px;
            margin: 0 auto;
            position: relative;
        }

        .events-timeline::before {
            content: '';
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            width: 3px;
            height: 100%;
            background: var(--secondary-color);
        }

        .event-item {
            display: flex;
            justify-content: flex-end;
            padding-right: 50%;
            position: relative;
            margin-bottom: 2rem;
        }

        .event-item:nth-child(even) {
            justify-content: flex-start;
            padding-right: 0;
            padding-left: 50%;
        }

        .event-content {
            background: var(--bg-white);
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: var(--shadow);
            max-width: 400px;
            position: relative;
            transition: all 0.3s ease;
        }

        .event-content:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-hover);
        }

        .event-content::before {
            content: '';
            position: absolute;
            width: 15px;
            height: 15px;
            background: var(--primary-color);
            border-radius: 50%;
            top: 50%;
            transform: translateY(-50%);
        }

        .event-item:nth-child(odd) .event-content::before {
            right: -42px;
        }

        .event-item:nth-child(even) .event-content::before {
            left: -42px;
        }

        .event-date {
            color: var(--primary-color);
            font-weight: 600;
            font-size: 0.9rem;
            margin-bottom: 0.5rem;
        }

        .event-content h4 {
            color: var(--text-dark);
            margin-bottom: 0.5rem;
        }

        .event-content p {
            color: var(--text-light);
            font-size: 0.9rem;
        }

        .event-type {
            display: inline-block;
            padding: 0.3rem 0.8rem;
            background: var(--secondary-color);
            color: var(--accent-color);
            border-radius: 15px;
            font-size: 0.75rem;
            margin-top: 0.8rem;
            font-weight: 500;
        }

        /* International Tours Section */
        .tours {
            background: var(--bg-white);
        }

        .tours-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .tour-card {
            background: var(--bg-light);
            border-radius: 10px;
            overflow: hidden;
            transition: all 0.3s ease;
        }

        .tour-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
        }

        .tour-image {
            height: 150px;
            background: var(--primary-color);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 3rem;
        }

        .tour-content {
            padding: 1.5rem;
        }

        .tour-content h3 {
            color: var(--text-dark);
            margin-bottom: 0.5rem;
        }

        .tour-content .country {
            color: var(--primary-color);
            font-weight: 600;
            font-size: 0.9rem;
            margin-bottom: 0.5rem;
        }

        .tour-content .date {
            color: var(--text-light);
            font-size: 0.85rem;
            margin-bottom: 0.8rem;
        }

        .tour-content p {
            color: var(--
