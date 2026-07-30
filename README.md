# Real-Time-Virtual-Background-Gesture-Control-System
An interactive Computer Vision application built with Python, OpenCV, and MediaPipe. This system removes the camera's original background in real-time without requiring a green screen and allows users to switch between different dynamic virtual cityscapes using simple hand gestures.
Features
•	Instant Background Removal: Uses MediaPipe's lightweight Image Segmenter to extract the user's foreground and replace the background with zero noticeable lag.
•	Hand Gesture Navigation: Swipe your hand left or right in front of the camera to toggle between different cityscapes (e.g., Cyberpunk City, Tokyo Neon Night, Sunset Sky).
•	Gesture Photo Snap: Raise a Victory sign to capture and automatically save high-resolution snapshots directly to your local workspace.
•	Low Latency & High Frame Rate: Optimized matrix manipulations using NumPy ensure smooth video performance on standard CPUs
