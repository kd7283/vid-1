# vid-1
vid 1
git clone https://github.com/your-username/video-showcase.git
cd video-showcase
video-showcase/
├── index.html
├── styles.css
└── videos/
    ├── video1.mp4
    ├── video2.mp4
    └── ...
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Video Showcase</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Video Showcase</h1>
        <p>Here are some of the videos I've made!</p>
    </header>

    <section class="video-gallery">
        <div class="video">
            <h2>Video 1</h2>
            <video controls>
                <source src="videos/video1.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <div class="video">
            <h2>Video 2</h2>
            <video controls>
                <source src="videos/video2.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <!-- Add more videos as needed -->
    </section>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    text-align: center;
    padding: 20px;
}

header {
    margin-bottom: 40px;
}

h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

p {
    font-size: 1.2rem;
}

.video-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.video {
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    width: 300px;
    padding: 10px;
    text-align: center;
}

video {
    width: 100%;
    border-radius: 8px;
}

h2 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}
git add .
git commit -m "Initial video showcase site"
git push origin main
