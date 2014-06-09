IJULIA_NOTEBOOK_PATH=/Users/jiahao/IJuliaNotebooks/public
NOTEBOOK_FILES=$(wildcard $(IJULIA_NOTEBOOK_PATH)/*.ipynb)

all: $(NOTEBOOK_FILES)
	ipython nbconvert --profile julia $<

