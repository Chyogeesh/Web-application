# Web-application
#It is a internship assignment
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exam Portal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Exam Portal</h1>
    </header>
    <main>
        <section id="upload-section">
            <h2>Upload Exam Paper</h2>
            <input type="file" id="file-upload">
            <button onclick="uploadExam()">Upload</button>
        </section>
        <section id="review-section">
            <h2>Review Exam Papers</h2>
            <ul id="exam-list"></ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Exam Portal</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
