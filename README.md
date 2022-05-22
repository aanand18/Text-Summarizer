
# Text-Summarizer-Flask-Deployment

![summarizer](https://user-images.githubusercontent.com/50799286/169695479-53c6883e-af9e-437f-b406-57864cb41421.png)






![Summarized](https://user-images.githubusercontent.com/50799286/169695463-28f82415-423c-4bfd-8e84-e9b20fdc59cb.png)


# Goal

**The goal is to provide a condensed representation of an input text that captures the original text's basic meaning.
To produce a condensed version, I've applied extractive based text summarization technique implemented using TextRank algorithm that crop out and stitch together Chunks of the text.
Tech Used: Python, Flask, HTML, Bootstrap CSS**

# Setting up Virtual environment

    pip install virtualenv
    source ./flaskenv/Scripts/activate

# Requirements Installation

**The Code is written in Python 3.7. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository**

    pip install -r requirements.txt
  
# Running the Project

    flask run
