# Start with Python

**

## Installation

Installing dependencies in a virtual environment :
`
virtualenv venv && source venv / bin / activate
`

Installing the requirements :
`
pip install -r requirements.txt
`

**

## Path

Do not forget to change the path of your python programs :
`
#!/sgoinfre/goinfre/Perso/gozsertt/miniconda3/bin/python
#!/Your/Path/miniconda3/bin/python
`

**

## Parser

Start the scraper:

Start by removing the old file:
`
rm -rf output_file.json
`

Then start the scraper:
`
scrapy runspider characters_scraper.py -s FEED_EXPORT_ENCODING=utf8 -o characters.json
scrapy runspider quotes_scraper.py -s FEED_EXPORT_ENCODING=utf8 -o quotes.json
`

**

## Run the program

Finaly use the following command for run the program :

`
python3 san_antonio.py
`

**

Enjoy !