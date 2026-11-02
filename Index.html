# AI-story-generator 

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>H2O Generator</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #071426;
    color: white;
    text-align: center;
    padding: 25px;
}

.container {
    max-width: 750px;
    margin: 50px auto;
    padding: 30px;
    background: #102744;
    border-radius: 20px;
    box-shadow: 0 0 25px #087cff44;
}

h1 {
    font-size: 42px;
    color: #00d5ff;
    margin-bottom: 15px;
}

p {
    color: #c5d9ed;
    margin-bottom: 25px;
}

input {
    width: 100%;
    padding: 16px;
    border-radius: 10px;
    border: 2px solid #00cfff;
    background: #071426;
    color: white;
    font-size: 17px;
    margin-bottom: 20px;
}

button {
    padding: 15px 30px;
    border: none;
    border-radius: 10px;
    background: #00bfff;
    color: #001526;
    font-size: 18px;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background: #00e0ff;
}

#status {
    margin: 25px 0;
    color: #00e0ff;
    font-size: 17px;
}

video {
    width: 100%;
    margin-top: 20px;
    border-radius: 15px;
    display: none;
}

.download {
    display: none;
    margin-top: 20px;
    text-decoration: none;
    background: #00d68f;
    color: black;
    padding: 14px 25px;
    border-radius: 10px;
    font-weight: bold;
}
</style>
</head>

<body>

<div class="container">

    <h1>💧 H2O Generator</h1>

    <p>
        Enter your subject and create an amazing
        AI story video!
    </p>

    <input
        type="text"
        id="subject"
        placeholder="Enter your story subject..."
    >

    <button onclick="generateVideo()">
        🎬 Generate Story Video
    </button>

    <div id="status"></div>

    <video id="video" controls></video>

    <br>

    <a id="download" class="download" download>
        Download Video
    </a>

</div>

<script>

async function generateVideo() {

    const subject = document.getElementById("subject").value;
    const status = document.getElementById("status");
    const video = document.getElementById("video");
    const download = document.getElementById("download");

    if (!subject.trim()) {
        alert("Please enter a story subject!");
        return;
    }

    status.innerText = "✨ AI is creating your story video...";

    video.style.display = "none";
    download.style.display = "none";

    try {

        // Connect this endpoint to your AI video backend
        const response = await fetch("/api/generate-video", {
            method: "POST",

            headers: {
                "Content-Type": "application/json"
            },

            body: JSON.stringify({
                subject: subject
            })
        });

        if (!response.ok) {
            throw new Error("Video generation failed");
        }

        const data = await response.json();

        if (!data.video_url) {
            throw new Error("No video URL received");
        }

        video.src = data.video_url;
        video.style.display = "block";

        download.href = data.video_url;
        download.style.display = "inline-block";

        status.innerText = "🎉 Your video is ready!";

        video.play();

    } catch (error) {

        status.innerText =
        "⚠️ Video service is not connected yet. Please connect an AI video API.";

        console.error(error);
    }
}

</script>

</body>
</html>
