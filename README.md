# beamer-uni-siegen
A LaTeX beamer theme for the new University of Siegen corporate design.

This template follows the official design guidelines and PowerPoint templates under https://design.uni-siegen.de/.

### Installation

If you are using a TeXlive distribution (recommended), all ``.sty`` files and the ``img`` folder in the repos' root need to be moved to your custom ``texmf`` folder, and there under

    texmf/tex/latex/beamertheme-siegen/

Finally, update your TeXlive database with (probably requires ``sudo``)

    texhash

### Color themes
This beamer theme provides color themes for all Uni Siegen faculties.
They can be loaded with

    \usecolortheme{default}
    
in your preamble where possible values are: ``default``, ``phil``, ``bak``, ``wir``, ``nt`` and ``lwf``.

### Special commands
There are some special commands now to control title, closing and section page designs.

For setting the title page layout, use the optional argument ``titlepage`` with ``\usetheme``:

    \usetheme[titlepage=4]{siegen}

in your preamble. Possible values are ``1`` to ``4``, default value is ``1``.

For setting the section page layout, use

    \sectiondesign{1}

with parameter 1 to 3 anywhere before calling ``\section``. For layout 3, you can also define a background image with

    \sectiondesign[path/to/your/image.jpg]{2}
    
The closing page consists of two fields, which is produced by the following command:

    \closingpage{<title>}{<info>}

### Example

The example can be built with the command

    xelatex siegen-example.tex

### Screenshots

![sst-01](https://user-images.githubusercontent.com/4593545/190432730-ea6f88ae-5337-4ad4-907c-530707135677.jpg)
![sst-02](https://user-images.githubusercontent.com/4593545/190432739-78b05821-2eb8-4e7e-8551-9454e323a5f7.jpg)
![sst-03](https://user-images.githubusercontent.com/4593545/190432743-dd53b585-d7f4-434c-b1cc-148ae502b6b6.jpg)
![sst-04](https://user-images.githubusercontent.com/4593545/190432746-dc0e2297-23fc-4eef-9f33-3831efa03764.jpg)
![sst-05](https://user-images.githubusercontent.com/4593545/190432754-e7deeca7-e006-4d61-8a20-b3cfb2695a88.jpg)
![sst-06](https://user-images.githubusercontent.com/4593545/190432757-3396045b-fc55-4735-ae9e-f40a1cac457e.jpg)
![sst-07](https://user-images.githubusercontent.com/4593545/190432760-3b52fa8a-67f6-4c63-a7e8-72b31cc99210.jpg)
![sst-08](https://user-images.githubusercontent.com/4593545/190432764-67f568db-539e-4981-8bca-af408fe5040e.jpg)
![sst-09](https://user-images.githubusercontent.com/4593545/190432772-2914a422-f818-4e78-abb2-d3282fe1f981.jpg)
![sst-10](https://user-images.githubusercontent.com/4593545/190432775-c36814b3-d4b4-4629-a64a-961f7f892efb.jpg)
![sst-11](https://user-images.githubusercontent.com/4593545/190432778-5216de27-f0a9-47c9-badf-1097a62016b6.jpg)
![sst-12](https://user-images.githubusercontent.com/4593545/190432782-f0aed8b8-d354-4ee3-9f6a-499df34ea2e9.jpg)
![sst-13](https://user-images.githubusercontent.com/4593545/190432785-416afcd1-29a0-43ef-b828-89461b4babd1.jpg)
