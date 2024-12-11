<h1>Image Style Transfer</h1>
<p align = "justify">
Developed an image-style transfer app using Python and Streamlit. It lets users upload images and apply artistic styles using deep learning. 
The app provides an interactive, user-friendly interface for real-time style transfer results.

The app allows users to upload both input and style images. Once the images are uploaded, the app processes them, displaying a loading animation until the style transfer is complete. 
A beautifully stylized image that users can preview directly in the app.

Additionally, the app includes a feature to download the stylized image, making it user-friendly and efficient for anyone looking to apply artistic styles to their photos with ease. 
This project leverages deep learning techniques to bring artistic creativity to life in a seamless web interface.
</p>

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
3. Run the <b>download_saved_models.py</b>
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
   After running the <b>download_saved_models.py</b>, will see the <b>saved_models.zip</b> in the current folder,
   unzip the folder, and move to the neural_style folder.
   <br>
   <br>
6. Run the <b>main.py</b> file
   <br>
   <br>
   Before run the <b>main.py</b> file change the directory
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
     

<h2>Sample Output</h2>
<br>
<br>
   <img src="https://github.com/mariyaviswa/Image_Style_Transfer_Streamlit/blob/master/sample_output%20(1).png">
   <br>
   <br>
   <img src="https://github.com/mariyaviswa/Image_Style_Transfer_Streamlit/blob/master/sample_output%20(2).png">
<h2> Downloaded Image </h2>
   <br>
   <br>
   <img src="https://github.com/mariyaviswa/Image_Style_Transfer_Streamlit/blob/master/sample_output%20(1).jpg">


   
   
   
   
   
