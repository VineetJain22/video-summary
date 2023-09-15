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
Currently, the project includes a Jupyter notebook titled Youtube video summary.ipynb. You can download and run the notebook in your local installation or in the Cloud like Google Colab. Note that you'll need to supply your own GPT-3.5 Turbo API key; simply swap out the existing placeholder with your personal key.  

Looking ahead, the project could be developed into a standalone Python package and potentially with a user interface. Contributions from the community are highly encouraged and appreciated.

## How it works
Scrape Transcript: The tool scrapes the transcript of the provided YouTube video URL (thanks to Jonas Depoix's Python package, link to package is provided below)   
Text Processing: The raw transcript is processed using Python libraries  
Generate Summary: A concise and coherent summary is generated using Open AI's gpt-3.5-turbo and can be exported in various formats.  

## License
This project is licensed under the MIT License

This project uses the following third-party software, covered by the MIT License:

- [youtube-transcript-api]([Link to Package Repository](https://pypi.org/project/youtube-transcript-api/))
