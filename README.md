<h1>Description</h1>

Developed an image style transfer app using Python and Streamlit. It lets users upload images and apply artistic styles to them using deep learning. 
The app provides an interactive, user-friendly interface for real-time style transfer results.

The app allows users to upload both an input image and a style image. Once the images are uploaded, the app processes them, displaying a loading animation until the style transfer is complete. 
The result? A beautifully stylized image that users can preview directly in the app.

Additionally, the app includes a feature to download the stylized image, making it user-friendly and efficient for anyone looking to apply artistic styles to their photos with ease. 
This project leverages deep learning techniques to bring artistic creativity to life in a seamless web interface

<h2>Installation Steps</h2>

1. Create Virtual Environment
   Create the venv for your directory using the following commands 
   <br>
   <br>
   <b>create venv</b>
       <pre>
         <code>
             python -m venv venv
         </code>
       </pre>
   <b>Activate venv</b>
       <pre>
         <code>
             venv\Scripts\activate
         </code>
       </pre>
2. Install the required libraries
   <br>
   <br>
   To run the program install the required libraries using the following command
   <br>
   <br>
       <pre>
         <code>
             pip install -r requirements.txt
         </code>
       </pre>
3. Run the download_saved_models.py
   <br>
   <br>
   For getting saved models to perform style transfer run this file
   <br>
   <br>
       <pre>
         <code>
             python run download_saved_models.py
         </code>
       </pre>
4. Move to neural_style Folder or directory
   <br>
   <br>
   After running the download_saved_models.py, will see the saved_models.zip in the current folder,
   unzip the folder and move to neural_style folder.
   <br>
   <br>
6. Run the main.py file
   <br>
   <br>
   Before run the main.py file change the directory
   <br>
   <br>
       <pre>
         <code>
             cd neural_style
         </code>
       </pre>
   Then run the <b>main.py</b> file
   <br>
   <br>
       <pre>
         <code>
             streamlit run main.py
         </code>
       </pre>
     
   
   
   
   
   
   
