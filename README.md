# Python notebooks with sample workflows for text/data mining using select University of Notre Dame digitized archival collections

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

This GitHub repository includes Jupyter notebook (`.ipynb`) files with sample Python workflows for using text and data mining workflows with select collections of digitized material from the [University of Notre Dame Archives](http://archives.nd.edu/).

## Acknowledgements

Any text and data mining endeavor is supported by heroic and ongoing work that happens at the nexus of digital infrastructure, archives/special collections, metadata, digital preservation. The workflows outlined in this project would not be possible without significant past, present, and ongoing work from colleagues in the University of Notre Dame Libraries, specifically (but not exclusively)...
- [University Archives](http://archives.nd.edu/) (Patrick Milhoan, Scott Kirycki, Joseph Smith, and Matthew Wilken)
- [Rare Books and Special Collections](https://rarebooks.library.nd.edu/) (Rachel Bohlmann, Tracy Bergstrom, Sara Weber)
- [Navari Family Center for Digital Scholarship](https://cds.library.nd.edu/) (Daniel Johnson, Eric Lease Morgan, Matthew Sisk)
- [Digital Services](https://directory.library.nd.edu/directory/departments/1195) (Mikala Narlock)

# Table of Contents

- [Bulk Download](#bulk-download)
  * [Alumnus](#alumnus)
  * [Bagby Glass Plate Negatives](#bagby-glass-plate-negative-collection)
  * [Annual Bulletins and Catalogs](#annual-bulletins-and-catalogs)
  * [Capstan](#capstan)
  * [Commencement Programs](#commencement-programs)
  * [Daily](#daily)
  * [Directories](#directories)
  * [Magazine](#magazine)
  * [Observer](#observer)
  * [Scholastic](#scholastic)
  * [Scholastic Football Review](#scholastic-football-review)
  * [Voice](#voice)
- [Optical Character Recognition](#optical-character-recognition)
  * [OCR Next Steps and Additional Resources](#ocr-next-steps-and-additional-resources) 
    * [Acrobat Adobe Pro](#acrobat-adobe-pro)
- [Text Analysis](#text-analysis)
  * [Python Text Analysis Next Steps and Additional Resources](#python-text-analysis-next-steps-and-additional-resources)
    * [More documentation on the tools covered in this notebook](#more-documentation-on-the-tools-covered-in-this-notebook)
    * [Other Tutorials, Packages, and Methods](#other-tutorials-packages-and-methods)
- [Next Steps and Additional Resources](#next-steps-and-additional-resources)  

# Bulk Download

The repository includes Jupyter notebooks for bulk downloading PDFs for the following collections.

## Alumnus

From the [University Archives](http://archives.nd.edu/digital/):
- "The Alumnus, published by the Alumni Association from January of 1923 until December of 1971, provided news and feature articles of interest to Notre Dame graduates. Notre Dame Magazine replaced it starting in 1972."
- [Alumnus Digital Collection](http://archives.nd.edu/Alumnus/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/alumnus.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/alumnus.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1ZgGuymWQTX1IeTwWamr88RkPPuOeujS-/view?usp=sharing) *ND users*

## Bagby Glass Plate Negative Collection

From the [University Archives](http://archives.nd.edu/digital/):
- "The Bagby company, a South Bend photographic studio, took pictures of athletes for Notre Dame. The digitized Glass Plate Negative Collection is part of a [larger Bagby collection](http://archives.nd.edu/findaids/ead/xml/bby.xml)."
- [Bagby Glass Plate Negative Collection (Notre Dame Sports), 1920s-1930s](http://archives.nd.edu/Bagby/index.htm/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/bagby_negatives.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/bagby_negatives.ipynb)
- [Google CoLab](https://drive.google.com/file/d/18Z19MYeu3iJzcjbItJQ97FPHWvSBVV4i/view?usp=sharing) *ND users*

## Annual Bulletins and Catalogs

From the [University Archives](http://archives.nd.edu/digital/):
- "Notre Dame's catalogues or bulletins included descriptions of courses, programs, curricula, facilities, and faculty. They generally [listed students](http://archives.nd.edu/bulletin/stdnts.htm) and provided information on [graduation ceremonies](http://archives.nd.edu/bulletin/cmmncmts.htm), degree recipients, and academic prizes won by students."
- [Notre Dame Annual Catalogues or Bulletins, 1850 - 1914](http://archives.nd.edu/bulletin/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/bulletins_catalogs.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/bulletins_catalogs.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1D3_LhB3TcuNOiePnz8VubWpiP2Xl3rzn/view?usp=sharing) *ND users*

## Capstan

From the [University Archives](http://archives.nd.edu/digital/):
- "During World War II, the United States Navy trained many officers at Notre Dame. The naval program published its own yearbook, called Capstan."
- [Capstan, 1943-1945, Digital Collection](http://archives.nd.edu/Capstan/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/capstan.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/capstan.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1cH6qsO5F5kh6KBYhk-rsugraGjt3gs-Z/view?usp=sharing) *ND users*

## Commencement Programs

From the [University Archives](http://archives.nd.edu/digital/):
- "Programs for graduations at the University of Notre Dame. The number of commencements per year varies. The content of programs also varies, but they generally provide information about graduating students, speakers, related events and ceremonies."
- [Notre Dame Commencement Programs, 1845 - 2018](http://archives.nd.edu/Commencement/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/commencement_programs.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/commencement_programs.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1Cssj7PnOnb1XI0WuLKzQLDi5mWSna-E9/view?usp=sharing) *ND users*

## Daily

From the [University Archives](http://archives.nd.edu/digital/):
- "The Notre Dame Daily first appeared on the twentieth of May, 1923. It published thirteen issue in its first volume, concluding at the end of the academic year on the sixth of June. Its second and final volume covered the 1923-1924 academic year in 128 issues beginning on the twenty-third of September and ending on the fifteenth of June."
- [Notre Dame Daily (student newspaper), 1923 - 1924](http://archives.nd.edu/Daily/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/daily.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/daily.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1zwheUyZaZ9ut-ewYIx90ltFsaxXQgESS/view?usp=sharing) *ND users*

## Directories

From the [University Archives](http://archives.nd.edu/digital/):
- "Lists of Notre Dame officers, administrators, rectors, prefects, faculty, post-doctoral research fellows, and students. The alphabetical list of faculty generally indicates academic department, campus address and home address. The alphabetical list of students gives major subject or academic program, dorm or local address, and home address."
- [Notre Dame Directories, 1922 - 1974](http://archives.nd.edu/dir/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/directories.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/directories.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1Usoq-kxdywEnuUzp0F4GZKSjlI0YWx9V/view?usp=sharing) *ND users*

## Magazine

From the [University Archives](http://archives.nd.edu/digital/):
- "The Notre Dame Foundation published this quarterly magazine, which includes much of general interest to anyone studying Notre Dame in the middle of the twentieth century."
- [Notre Dame: A Magazine, 1948-1965](http://archives.nd.edu/ndm/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/magazine.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/magazine.ipynb)
- [Google CoLab](https://drive.google.com/file/d/19qTFmbhp7qJTdpCHcKTk-0GXvPc_N2-D/view?usp=sharing) *ND users*

## Observer

From the [University Archives](http://archives.nd.edu/digital/):
- "The Observer started providing news for the University of Notre Dame and Saint Mary's College starting in the fall of 1966, first as a weekly, then bi-weekly, and soon as a daily newspaper. Starting with the issue of October 10, 2009, the Notre Dame / Saint Mary's Observer appeared online (http://ndsmcobserver.com/)."
- [The Observer (student newspaper), 1966 - 2015](http://archives.nd.edu/Observer/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/observer.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/observer.ipynb)
- [Google CoLab](https://drive.google.com/file/d/19qTFmbhp7qJTdpCHcKTk-0GXvPc_N2-D/view?usp=sharing) *ND users*

## Scholastic

From the [University Archives](http://archives.nd.edu/digital/):
- "The Scholastic, a student weekly, began in 1867 as The Scholastic Year. For most of its history it provided news about Notre Dame as well as feature articles, literary works, essays, and alumni notes."
- [Notre Dame Scholastic (student magazine), 1867 - 2011](http://archives.nd.edu/Scholastic/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/scholastic.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/scholastic.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1_rygfLHBoADkQqnfhTUd0xzUkF51n7Kp/view?usp=sharing) *ND users*

## Scholastic Football Review

From the [University Archives](http://archives.nd.edu/digital/):
- "The Notre Dame Scholastic published reviews of the football season starting in 1901. In 1910 a separate publication covered the "Gridiron Season" and from 1919 to 1921 a Football Review provided competition for the Scholastic. From 1924 to 1932 the Football Review prevailed as the Scholastic provided little or no commentary. In later years the Scholastic generally published its own special issue on the football season, though Irish Eye took over for a time in the 1980s."
- [Notre Dame Football Review, 1901 - 2010](http://archives.nd.edu/Football/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/scholastic_football_review.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/scholastic_football_review.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1oDtiH6hbeWhbAaAoZCU5-cSlojaDy88A/view?usp=sharing) *ND users*

## Voice

From the [University Archives](http://archives.nd.edu/digital/):
- "The Voice of Notre Dame, predecessor of the more familiar daily Observer, appeared somewhat irregularly every week or so between 1963 and 1966, though issues were sometimes printed as little as two days apart."
- [Notre Dame Voice (student newspaper), 1963 - 1966](http://archives.nd.edu/Voice/)

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/collections/voice.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/collections/voice.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1ydyMMAf43Aw7ltgB9CobTukR__MEO-P6/view?usp=sharing) *ND users*

# Optical Character Recognition

The repository includes a Jupyter notebook that outlines a preliminary optical character recognition (OCR) workflow, using the Scholastic Football Review publications as an example.

The OCR workflow uses the following programs and Python modules:
- `tesseract`
- `pytesseract`
- `opencv`
- `pillow`
- `pdf2image`

The OCR workflow includes the following steps:
- Creates sub-directories for each `PDF`
- Converts each page in a `PDF` to a `PNG` file
- Saves the image files for a single `PDF` in a sub-directory
- Runs OCR on image files with sample code for `pytesseract` and `pytesseract`/`opencv` workflows
- Writes OCR output to a `txt` file in the main directory, with one `txt` file for each `PDF`

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/ocr-roadmap.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/ocr-roadmap.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1WbGTAvs1WCGrC5XZeADyhminFn8QMEHT/view?usp=sharing) *ND users*

## OCR Next Steps and Additional Resources

There are a number of options and next steps for refining or further building out an OCR workflow.

**More documentation on tools covered in this notebook**:
- Tesseract
  * ["Tesseract documentation"](https://tesseract-ocr.github.io/tessdoc/)
    * ["Improving the quality of the output"](https://tesseract-ocr.github.io/tessdoc/ImproveQuality)
  * University of Illinois Scholarly Commons, "[Introduction to OCR and Searchable PDFs: Tesseract](https://guides.library.illinois.edu/c.php?g=347520&p=4116757)" *University of Illinois Library*
  * NYU Libraries Scholarly Communications and Information Policy Department, "[Tesseract OCR Software Tutorial](https://guides.nyu.edu/tesseract/home)" *New York University Libraries*
     * The NYU guide covers how to convert PDF or PNG files to TIFF high-resolution images, improving image quality using command-line tool ImageMagick, and optimizing the command-line version of Tesseract
   * Andrew Akhlaghi, "OCR and Machine Translation," The Programming Historian 10 (2021), https://doi.org/10.46430/phen0091.
     * Tutorial that covers ImagMagick to Tesseract workflow.
   * Moritz Mähr, "Working with batches of PDF files," The Programming Historian 9 (2020), https://doi.org/10.46430/phen0088.
     * Tutorial that covers using `poppler` to extract images from PDF and preliminary topic modeling
- OpenCV
  * ["OpenCV documentation"](https://opencv.org/)
    * `OpenCV` has a number of more advanced features and functions, including rotation/deskewing, removing shadows, object detection, etc. OpenCV's [Python Tutorials](https://docs.opencv.org/4.5.3/d6/d00/tutorial_py_root.html) are a good place to start.

**Other tools/packages that can get you started with more advanced work**:
- [Leptonica](http://www.leptonica.org/): variety of resources related to image processing/analysis (affine transformations, binary/grayscale morphology, pixelwise masking/blending, etc)
- [ImageMagick](https://imagemagick.org/index.php): program that uses multi-threaded processing for large-scale image processing workflows (color management, image features, morphology, noise reduction, etc)
- [ScanTailor](https://github.com/4lex4/scantailor-advanced): designed for post-processing scanned pages (before OCR) to improve OCR results (margins, picture zones, dewarping, etc)
- [unpaper](https://github.com/unpaper/unpaper): another tool designed for post-processing scanned material (before OCR) to improve OCR results (dark edges, margins, deskewing, etc)
- [PRLib](https://github.com/leha-bot/PRLib): pre-recognition library (before OCR) designed to improve OCR results (binarization, deskew, noise, etc)

### Acrobat Adobe Pro

But, depending on the number of documents you're working with as well as the quality of OCR output needed for your project, Adobe Acrobat Pro will likely get you where you need to go.
- NOTE: This is a different program than the Adobe Acrobat Reader DC free program you may have on your computer.

Notre Dame students have access to the Adobe Pro software title through the Adobe Creative Cloud Desktop Application, available free through OIT.
- NOTE: The full Adobe Creative Cloud suite is available on any [OIT lab computer](https://nd.service-now.com/kb_view.do?sysparm_article=KB0013524) and can be accessed through the OIT general purpose [Virtual Computer Lab](https://inside.nd.edu/task/all/virtual-computer-lab)

To get Adobe Pro on your own computer:
- Download the program: [OIT, Adobe Creative Cloud Desktop Application](https://oit.nd.edu/services/software/software-downloads/adobe-creative-cloud-desktop-application/)
- Request a license: OIT, "[Request a license for Adobe Creative Cloud](https://nd.service-now.com/kb_view.do?sysparm_article=KB0017960)," *ND Service Now*

Once you have Adobe Pro on your own computer, you can use the expanded features to run an OCR workflow on a single PDF or multiple PDFs. 

Adobe Pro also allows you to export the contents of a single PDF or multiple PDFs to plain-text (`.txt`) files.

To run OCR within Adobe Pro:
- University of Illinois Scholarly Commons, "[Introduction to OCR and Searchable PDFs: Adobe Acrobat Pro](https://guides.library.illinois.edu/c.php?g=347520&p=4116755)" *University of Illinois Library*
- Rowan University Library Digital Scholarship Center, "[Acrobat Pro: Optical Character Recognition for Research, Learning, and Accessibility](https://youtu.be/HxSYtQdaAp0)" *YouTube video* (20 August 2020)
- Pixascene, "[Perform an OCR on a PDF document using Adobe Acrobat Pro](https://youtu.be/zZT34zmc0kw)" *YouTube video* (15 June 2020)
- Tulane University Libraries, "[Digitize Your Sources: OCR and Adobe Acrobat Pro](https://libguides.tulane.edu/diy_digital/acrobat)" *Tulane University Library Guide*

To export a single PDF as TXT from Adobe Pro (using "Export"):
- Adobe Acrobat User Guide, "[Convert or export PDFs to other file formats](https://helpx.adobe.com/acrobat/using/exporting-pdfs-file-formats.html)" *Adobe* (26 August 2021)
 
To export multiple PDFs as TXT files from Adobe Pro (using "Action Wizard"):
1. `View -> Tools -> Action Wizard -> Create New Action`
2. `Choose 'Save & Export' -> Save -> add to right-hand pane`
3. At `right-hand pane -> choose folder` and click `Specify Settings` to change export format to `TXT`
- Source: StackOverflow, "[How to convert batch pdf files to text using Adobe Acrobat Pro?](https://stackoverflow.com/questions/25212228/how-to-convert-batch-i-e-huge-pdf-files-to-text-using-adobe-acrobat-pro)" *StackOverflow* (2015)
- For more on Action Wizard: Adobe Acrobat User Guide, "[Action Wizard (Acrobat Pro)](https://helpx.adobe.com/acrobat/using/action-wizard-acrobat-pro.html#about_action_wizards)" *Adobe* (2 June 2020)

# Text Analysis

The repository includes a Jupyter notebook that outlines a preliminary text analysis workflow, using the Scholastic Football Review publications as an example.

The text analysis workflow is based on the back-end stack for Eric Lease Morgan's Distant Reader.
- Morgan, Eric Lease. (2020, April 10). Distant Reader (Version Alpha). Zenodo. https://doi.org/10.5281/zenodo.3747777.

The workflow uses the following Python modules:
- `wordcloud`
- `matplotlib`
- `spaCy`
- `nltk`
- `gensim`

The workflow includes sample code for the following steps or tasks:
- Generate a word cloud using `wordcloud` and `matplotlib`
- Analyze syntax using `spaCy`
- Part-of-speech tagging using `spaCy`
- Named entity extraction and visualization using `spaCy`
- Tokenizing text and tag tokens using `nltk`
- Named entity extraction using `nltk`
- Generate unique word list using `nltk`
- Plot term frequency and distribution using `nltk` and `matplotlib`
- Generate dictionary and corpus from text file using `gensim`
- Show word weights in corpus using `gensim`
- Create bag of words from single text file using `gensim`
- Create TD-IDF model and show TD-IDF weights using `gensim`

Jupyter Notebook:
- [GitHub](https://github.com/kwaldenphd/nd-digital-archives/blob/main/text-analysis-roadmap.ipynb)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/github/kwaldenphd/nd-digital-archives/blob/main/text-analysis-roadmap.ipynb)
- [Google CoLab](https://drive.google.com/file/d/1S2W6NQfLC_9kbcg7_RwYZ163yZ6R7n1K/view?usp=sharing) *ND users*

## Python Text Analysis Next Steps and Additional Resources

## More documentation on tools covered in this notebook

**`wordcloud`**
- wordcloud, "[WordCloud for Python documentation](https://amueller.github.io/word_cloud/)"
- wordcloud, "[Gallery of Examples](https://amueller.github.io/word_cloud/auto_examples/index.html#example-gallery)"
- Duong Vu, "[Generating Word Clouds in Python](https://www.datacamp.com/community/tutorials/wordcloud-python)" *DataCamp* (8 November 2019)
- Zolzaya Luvsandorj, "[Simple Word Cloud in Python](https://towardsdatascience.com/simple-wordcloud-in-python-2ae54a9f58e5)" *Towards Data Science* (20 June 2020)

**`spaCy`**
- spaCy, "[spaCy 101: Everything you need to know](https://spacy.io/usage/spacy-101)"
- spaCy, "[Advanced NLP with spaCy](https://course.spacy.io/en/)"
- Ines Montani, "[spaCy Cheat Sheet: Advanced NLP in Python](https://www.datacamp.com/community/blog/spacy-cheatsheet)" *DataCamp* (14 July 2021)
- Conor Mc., "[A short introduction to NLP in Python with spaCy](https://towardsdatascience.com/a-short-introduction-to-nlp-in-python-with-spacy-d0aa819af3ad)" *Towards Data Science* (17 March 2017)

**`nltk`**
- Steven Bird, Ewan Klein, and Edward Loper, *[Natural Language Processing With Python: Analyzing Text with the Natural Language Toolkit](http://www.nltk.org/book/)* (O'Reilly, 2009).
  * Free online book includes chapters on processing tasks, categorizing/tagging words, classifying text, extracting information, analyzing sentence structure, and other tasks.
- Avinash Navlani, "[Text Analytics for Beginners using NLTK](https://www.datacamp.com/community/tutorials/text-analytics-beginners-nltk)" *DataCamp* (13 December 2019)
- Michelle Morales, "[How to Work with Language Data in Python 3 Using the Natural Language Toolkit (NLTK)](https://www.digitalocean.com/community/tutorials/how-to-work-with-language-data-in-python-3-using-the-natural-language-toolkit-nltk)" *Digital Ocean* (3 January 2017)
- Shaumik Daityari, "[How to Perform Sentiment Analysis in Python 3 using the Natural Langauge Toolkit (NLTK)](https://www.digitalocean.com/community/tutorials/how-to-perform-sentiment-analysis-in-python-3-using-the-natural-language-toolkit-nltk)" *Digital Ocean* (26 September 2019)
- Zoë Wilkinson Saldaña, "Sentiment Analysis for Exploratory Data Analysis," The Programming Historian 7 (2018), https://doi.org/10.46430/phen0079.
- François Dominic Laramée, "Introduction to stylometry with Python," The Programming Historian 7 (2018), https://doi.org/10.46430/phen0078.

## Other Tutorials, Packages, and Methods

For a more detailed overview of text analysis methods- START HERE before diving into a new method/tutorial:
- Heather Froelich, "[Text Analysis: An Introduction, Methods](https://guides.libraries.psu.edu/c.php?g=829065&p=5922906)" *PennState University Library Guide*
- Stéfan Sinclair & Geoffrey Rockwell, *[The Art of Literary Text Analysis](https://nbviewer.jupyter.org/github/sgsinclair/alta/blob/master/ipynb/ArtOfLiteraryTextAnalysis.ipynb)*, edited by Melissa Mony (last modified 12 January 2018)
  * Includes Jupyter notebooks with more resources on `nltk`, visualizing textual data, and a variety of analysis methods 

For a more detailed overview of various tools and tutorials (beyond those listed here):
- Alan Liu, "[Tutorials for DH Tools and Methods, Text Analysis](http://dhresourcesforprojectbuilding.pbworks.com/w/page/69244314/Tutorials%20for%20DH%20Tools%20and%20Methods#tutorials-text-analysis)" *digital humanities resources for project building* (2019)

**List of words and word frequency**
- William J. Turkel and Adam Crymble, "Normalizing Textual Data with Python," The Programming Historian 1 (2012), https://doi.org/10.46430/phen0014.
- William J. Turkel and Adam Crymble, "Counting Word Frequencies with Python," The Programming Historian 1 (2012), https://doi.org/10.46430/phen0003.
- William J. Turkel and Adam Crymble, "Keywords in Context (Using n-grams) with Python," The Programming Historian 1 (2012), https://doi.org/10.46430/phen0010.

**TF-IDF (term frequency, inverse document frequency)**
- Matthew J. Lavin, "Analyzing Documents with TF-IDF," The Programming Historian 8 (2019), https://doi.org/10.46430/phen0082.
- John R. Ladd, "Understanding and Using Common Similarity Measures for Text Analysis," The Programming Historian 9 (2020), https://doi.org/10.46430/phen0089.
  * Both of these tutorials use [`scikit-learn`'s tf-idf implementation](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)

**Topic Modeling (looking for patterns of words in text/corpus to build topics, builds on td-idf)**
- For more specifics on topic modeling as a methodology: 
  * Ted Underwood, "[Topic modeling made just simple enough](https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/) *blog* (7 April 2012)
  * Scott Weingart, "[Topic Modeling for Humanists: A Guided Tour](http://scottbot.net/topic-modeling-for-humanists-a-guided-tour/)" *blog* (25 July 2012)
- Shawn Graham, Scott Weingart, and Ian Milligan, "Getting Started with Topic Modeling and MALLET," The Programming Historian 1 (2012), https://doi.org/10.46430/phen0017.
- Shanshank Kapadia, "[Topic Modeling in Python: Latent Dirichlet Allocation (LDA)](https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0)" *Towards Data Science* (14 April 2019)
- Susan Li, "[Topic Modelling in Python with NLTK and Gensim](https://towardsdatascience.com/topic-modelling-in-python-with-nltk-and-gensim-4ef03213cd21)" *Towards Data Science* (30 March 2018)

**Sentiment analysis (emotional intensity/weight for words and phrases in a text)**
- Zoë Wilkinson Saldaña, "Sentiment Analysis for Exploratory Data Analysis," The Programming Historian 7 (2018), https://doi.org/10.46430/phen0079.

**Stylometry (literary style, authorship attribution)**
- François Dominic Laramée, "Introduction to stylometry with Python," The Programming Historian 7 (2018), https://doi.org/10.46430/phen0078.

**Geoparsing (extracting and plotting location information)**
- Beatrice Alex, "Geoparsing English-Language Text with the Edinburgh Geoparser," The Programming Historian 6 (2017), https://doi.org/10.46430/phen0067.

**Working with other source material (other archives, APIs, etc)**
- Stephen Krewson, "Extracting Illustrated Pages from Digital Libraries with Python," The Programming Historian 8 (2019), https://doi.org/10.46430/phen0084.
  *  Tutorial covers workflows for getting digital image content from HathiTrust and Internet Archive, but could also get you started with an OCR workflow for texts in these collections.
- Resources for using the Library of Congress' "Chronicling America" collection (wide variety of national and local U.S. newspapers, 1777-1963)
  * Library of Congress, "[About the Site and API](https://chroniclingamerica.loc.gov/about/api/)" *Chronicling America: Historic American Newspapers*
  * Library of Congress, "[Available Tutorials](https://libraryofcongress.github.io/data-exploration/all-tutorials.html)" *loc.gov JSON API*
  * Hugo van Kemenade, "[chroniclingamerica.py: Python API to search Chronicling America newspaper pages](https://github.com/hugovk/chroniclingamerica.py)" *GitHub* (2016)
  * Jason Heppler, "[Working with the Chronicling America API](https://observablehq.com/@hepplerj/working-with-the-chronicling-america-api)" *Observable* (6 July 2020)

**Stanford Natural Language Processing Group**

From their "[Software](https://nlp.stanford.edu/software/)" page: "The Stanford NLP Group makes some of our Natural Language Processing software available to everyone! We provide statistical NLP, deep learning NLP, and rule-based NLP tools for major computational linguistics problems, which can be incorporated into applications with human language technology needs. These packages are widely used in industry, academia, and government...All our supported software distributions are written in Java."

**`scikit-learn`**
- `scikit-learn`, "[Working With Text Data](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html)": The `scikit-learn` machine-larning library includes a nubmer of modules and resources for natural language processing, including tasks like feature extraction and linear models for categorization.

# Next Steps and Additional Resources

For more background and context on the various University Archive publications and collections, users are encouraged to consult Thomas E. Blantz's *[The University of Notre Dame: A History](https://undpress.nd.edu/9780268108212/the-university-of-notre-dame/)* (University of Notre Dame Press, 2020).
- [Link to online access via Hesburgh Libraries (ND users)](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_cdi_askewsholts_vlebooks_9780268108243)
