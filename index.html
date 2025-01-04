<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Schedule Planner</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 5px;
            padding: 0;
            background-color: #f3f3f3;
        }
        form {
            max-width: 560px; /* Reduced width */
            margin: auto;
            padding: 5px;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .hour-label {
            margin-top: 3px;
            font-weight: bold;
            font-size: 0.7em; /* Reduced font size */
        }
        textarea {
            width: 100%;
            height: 25px; /* Reduced height */
            margin-bottom: 5px;
            font-size: 0.7em; /* Reduced font size */
            padding: 3px;
        }
        button {
            display: block;
            width: 100%;
            padding: 6px;
            margin-top: 6px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.9em;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
<h1 style="text-align: center; font-size: 1.2em; margin-bottom: 10px;">Daily Schedule Planner</h1>
<form id="schedule-form">
    <div id="hour-inputs"></div>
    <button type="button" id="generate-btn" onclick="generateImage()">Generate Image</button>
</form>

<script>
    // Generate hour input fields dynamically
    const hourInputsContainer = document.getElementById('hour-inputs');
    for (let hour = 6; hour < 22; hour++) {
        const label = document.createElement('label');
        label.className = 'hour-label';
        label.textContent = `${hour}:00 - ${hour + 1}:00`;

        const textarea = document.createElement('textarea');
        textarea.name = `hour-${hour}`;
        textarea.placeholder = `Activity for ${hour}:00 - ${hour + 1}:00`;

        hourInputsContainer.appendChild(label);
        hourInputsContainer.appendChild(textarea);
    }

    // Function to generate image
    async function generateImage() {
        const formElement = document.getElementById('schedule-form');
        const generateBtn = document.getElementById('generate-btn');

        // Hide the button before generating the image
        generateBtn.style.display = 'none';

        // Set the dimensions of the canvas to fit the mobile screen size (1080x1920)
        const width =  formElement.offsetWidth;  // Width of the mobile screen (adjust as needed)
        const height = formElement.offsetHeight; // Height of the mobile screen (adjust as needed)

        html2canvas(formElement, {
            scale: 2, // Increase resolution for better clarity
            width: width, // Set the width to 1080px
            height: height, // Set the height to 1920px
            x: 0, // Start x position
            y: 0, // Start y position
            scrollX: 0,
            scrollY: 0,
        }).then(canvas => {
            const image = canvas.toDataURL('image/png');

            // Create a link to download the image
            const link = document.createElement('a');
            link.href = image;
            link.download = 'Daily_Schedule.png';
            link.click();

            // Show the button again after image is generated
            generateBtn.style.display = 'block';
        }).catch(error => {
            console.error('Error generating image:', error);
            alert('An error occurred while generating the image. Check the console for details.');

            // Show the button again in case of error
            generateBtn.style.display = 'block';
        });
    }
</script>
</body>
</html>
