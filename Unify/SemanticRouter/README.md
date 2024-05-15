# Semantic Router
[Demo](https://github.com/ithanigaikumar/demos/assets/107815119/33ceff47-3495-44a9-aad7-c0a3ba3433a8)

<video width="640" height="480" controls>
  <source src="../../../../_static/semanticrouterapplication.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


A live version of the application is hosted on Streamlit, try it out yourself using the link below: 

[Semantic Router on Streamlit](https://semanticrouterchatbot.streamlit.app/)

## Introduction:
This semantic router Streamit application optimizes user query handling by dynamically routing each query to the most appropriate model based on semantic similarity.A routing layer is included to help with this process. This system supports predefined routes for domains like maths and coding, and allows users to create custom routes for unique needs. By ensuring that queries are processed by the best-suited model, the semantic router enhances output quality and improves cost efficiency. This approach not only delivers more accurate and contextually relevant responses but also enhances overall user satisfaction.


## Repository and deployment
Access using the following URL: [https://semanticrouterchatbot.streamlit.app/](https://semanticrouterchatbot.streamlit.app/) or follow the sections below to get started.
Fork from this respository:[https://github.com/ithanigaikumar/SemanticRouter]
To set up the project, you will need to install several Python packages. You can do this using pip, Python's package installer. Execute the following commands in your terminal or command prompt to install the required packages.

**Install Required Packages:**
```
   pip install streamlit
   pip install -U semantic-router==0.0.34
   pip install unifyai
   pip install transformers
   pip install torch

```
Make sure that each command completes successfully before proceeding to the next step. If you encounter any issues during the installation process, check your Python and pip versions, and ensure your environment is configured correctly.

 **Launch the App :**


    
    streamlit run app.py


  
## Contributors

| Name                          | GitHub Username |
|-------------------------------|-----------------|
| Indiradharshini Thanigaikumar | [ithanigaikumar](https://github.com/ithanigaikumar)  |
| Jeyabalan Nadar               | [jeyabalang](https://github.com/jeyabalang)    |
