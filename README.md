Preparing and Submitting Manuscripts Using LaTeX
================================================

The ACS Paragon Plus Environment supports LaTeX. If you experience any difficulty with your LaTeX submission, please feel free to contact ACS Publications Support directly.

File Preparation
----------------
Note that your submission must include all referenced files, including all necessary resource files such as bibliographic files, images, etc.

Achemso Style Package
---------------------
Use of the freely available achemso style package to help prepare your submission is strongly encouraged. The achemso package provides the official macros for ACS (achemso.cls) and BibTeX styles (achemso.bst and biochem.bst) for submission to ACS journals. The package and instructions are available from CTAN, the Comprehensive TeX Archive Network.

Additional Guidelines
---------------------
Additional guidelines for LaTeX file preparation are also available.
Manuscript files prepared in TeX/LaTeX will be used in journal production provided you adhere to these guidelines.
* Minimal formatting is all that is required in the document.
* Use additional packages only when they are required to support your content.
* Include all sections of the article in a single file. Include the list of references within the LaTeX file. Captions must be created in the LaTeX document.
* References should be cited in text using \cite{} and BibTeX (or \bibtem{}).
* Use \frac to build fractions. Do not use \over or \stackrel to build fractions in displayed equations.
* Use \sum_{}^{} for summations and \prod_{}^{} for products.
* Use the array environment only to build true matrices, not for aligning multiline equations. (Load the amsmath package loaded for the latter.)
* Load font packages only when required to provide additional symbols.
* Avoid extensive use of \newcommand and \def.

File Submission
---------------
Submit your own Manuscript PDF File—and provide your native LaTeX manuscript package as a ZIP archive.

Compress the following into a single ZIP archive (.zip) file:
* Main body of the LaTeX document (i.e., a file ending with .tex or .ltx)
* All files referenced by the main LaTeX document (including other .tex files)
* Any BibTeX database (.bib) files used
* Any graphics files

Remember to embed or include the bibliography, etc., in the main file or the ZIP Archive.

File Designation	Files Needed for Submission
Manuscript File	Submit a ZIP Archive of all TeX files, graphics, and referenced files.
Manuscript PDF File	Submit your own author-generated PDF.