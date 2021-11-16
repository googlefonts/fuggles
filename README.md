Take a little Inspiration, mix in some Sassy Frass and a splash of Waterfall; add hundreds of alternate forms and you have the recipe for a versatile hand writing font.

This fun, scribbly little font can fool you. At first glance it looks crude and simple. But, with over 1600 glyphs, combine the right character pairs and suddenly Fuggles is a powerful script that can be used for sophisticated commercial design. Some characters are quirky, some are swashy, some are scribbly and others are elegant.

The name comes from classic English beer brewing, a kind of aroma hop cultivated in 1875 by Mr Richard Fuggle.

The Latin glyph set supports Western, Central, Eastern european languages and also Vietnamese.

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
