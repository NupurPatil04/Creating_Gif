 GIF Creator from Images
This simple Python script reads multiple image files and creates an animated .gif using the imageio.v3 library.

📜 Requirements
Python 3.7+
imageio

Install with:
bash
Copy
Edit
pip install imageio

📂 Files Used
Make sure the following image files are present in the same directory as your script:
team-pic1.png
team-pic2.png

 How It Works
The script:
Loads image files using imageio.v3.imread()
Stores them in a list
Writes the images into a .gif using imageio.v3.imwrite()
