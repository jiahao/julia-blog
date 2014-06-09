IJULIA_NOTEBOOK_PATH=/Users/jiahao/IJuliaNotebooks/public

all: 2014-06-09-colors-chemistry.html

2014-06-09-colors-chemistry.html: $(IJULIA_NOTEBOOK_PATH)/Colors\ of\ chemistry.ipynb
	ipython nbconvert $(IJULIA_NOTEBOOK_PATH)/Colors\ of\ chemistry.ipynb
	mv Colors\ of\ chemistry.html 2014-06-09-colors-chemistry.html
