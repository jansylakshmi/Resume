<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DevOps CI/CD Pipeline Demo</title>

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(120deg, #0f2027, #203a43, #2c5364);
            color: #ffffff;
            animation: fadeIn 1.5s ease-in;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            animation: slideDown 1.2s ease-out;
        }

        header h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
            opacity: 0.9;
        }

        section {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 25px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            backdrop-filter: blur(6px);
            animation: floatUp 1.5s ease forwards;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px
