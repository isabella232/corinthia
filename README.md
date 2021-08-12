# Corinthia

Arguably, one of the most popular fonts of the TypeSETit Library. Corinthia flows with perfect connections and beautiful curves. It’s a delightful design that offers wide usage...

This award winning font comes with over 500 glyphs, and character sets for European languages. All three weights are perfect for creating elegant design work from packaging and romance novels, to invitations and social expression products.

![Sample Image](Documentation/Corinthia.png)

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
