🤖 AI Human-o-Meter
An interactive, browser-based human detection tool powered by TensorFlow.js. This project uses a pre-trained COCO-SSD (Common Objects in Context) model to identify people in a live video stream and calculate a "resemblance" score based on AI confidence.

Key Features
Real-Time Detection: Low-latency object detection directly in the browser.

Neural Network Integration: Utilizes the COCO-SSD model for identifying the "person" class.

Dynamic UI: A responsive dashboard that changes color (Green/Yellow/Red) based on detection confidence.

Canvas Overlay: Real-time drawing of bounding boxes over the video feed using the HTML5 Canvas API.

Privacy-Focused: Since it uses TensorFlow.js, all processing happens locally on the user's machine—no video data is sent to a server.