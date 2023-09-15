# video-summary
Get summary of YouTube videos almost instantly. No more spending hours watching long tutorials, meetings, or lectures.  
Get the gist in minutes! 🚀


## Table of Contents
Features    
Usage  
How it Works  
License  

## Features 🌟
👨‍💻 Why is this Important?  
Time-Saving: Get the information you need quickly.  
Accessibility: Makes content easier to digest for everyone.  
Versatility: Can be used for personal learning, business meetings, academic lectures, and more!    

The following features could be easily implemented with some more time.  
Customizable Summary Lengths: Generate summaries that fit your specific needs.  
Multi-language Support: Works with transcripts from various languages.  
Export Options: Save your summaries in multiple formats (Text, PDF, etc.).  

## Usage
As of now, I am putting up a jupyter notebook (ipynb) file. You can run the code cells in your local installation, Google Colab etc. You will need to provide your own gpt-3.5-turbo API key. Just replace the placeholder for the key with your own API key.    
In the future, I would like to create a Python package even possibly a user interface. Any contribution from the community is welcome. 

## How it works
Scrape Transcript: The tool scrapes the transcript of the provided YouTube video URL (thanks to Jonas Depoix's Python package, link to package is provided below)   
Text Processing: The raw transcript is processed using Python libraries  
Generate Summary: A concise and coherent summary is generated using Open AI's gpt-3.5-turbo and can be exported in various formats.  

## License
This project is licensed under the MIT License

This project uses the following third-party software, covered by the MIT License:

- [youtube-transcript-api]([Link to Package Repository](https://pypi.org/project/youtube-transcript-api/))
