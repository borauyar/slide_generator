# Slide Generator

A markdown file is imported, the bulletpoints are used to search google images and 
slides are created inserting the downloaded image to each slide along with the text.  

```
# Title1
- bulletpoint 1
- bulletpoint 2

# Title2 
- bulletpoint 1
- bulletpoint 2
```

# Dependencies

```
conda create -n slide_generator python=3.9
conda activate slide_generator
pip install googlesearch-python
pip install Google-Images-Search
pip install python-pptx
```

# Usage 
To use this script, you'll need a Google API key and a Custom Search Engine ID (cx). 
You can obtain them by following the steps in the [official documentation](https://developers.google.com/custom-search/v1/introduction).

Once you have the API key and cx, you can run the script from the command line like this:

```
python slide_generator.py slides.md your_api_key your_cx
```

# Sample output

See `./sample/` folder for a sample output when the script is run with the `slides.md` input. 





