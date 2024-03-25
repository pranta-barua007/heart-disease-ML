### Get started

Prerequisite : [Conda or MiniConda](https://docs.conda.io/projects/miniconda/en/latest/) 

# step 1
`bash conda env create --prefix ./env -f ./environment.yml`

optional Tip:  to export environment dependencies type after activating the project environemt
`bash  conda env export > environment.yml`

# or Using `requirements.txt`
`conda create --name <env> --file requirements.txt`

# step 2
download bulldozer price data from [kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

# stpe 3
edit on jupyter notebook