# Working of Model

![functionality](https://github.com/Manvn48/Imdb-reviews-Sentiment-Analysis/blob/main/movie-sentiment-functionality.gif)


## Steps to run on Windows

* Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://www.markdownguide.org/basic-syntax/) Client 
* Open GIT CMD >> navigate to working directory >> Clone this Github Repo (or download project files from GitHub directly)

      git clone https://github.com/skillcate/sentiment-analysis-with-deep-neural-networks.git  
* Open Windows Powershell >> navigate to new working directory (cloned repo folder)
* Run Project in Flask


  * Using Conda Environment:

        conda env create -f conda_env_win.yml   # create conda environment called 'app_env'
        conda env list                          # check if app_env is created
        conda activate app_env                  # activate app_env
        python app.py                           # run the project
        conda deactivate                        # close conda environment once done

  * Using PIP + Virtualenv:
 
        pip install virtualenv                  # install virtual environment        
        virtualenv ENV                          # create virtual environment by the name ENV
        .\ENV\Scripts\activate                  # activate ENV
        pip install -r .\pip_requirements.txt       # install project dependencies
        python app.py                           # run the project
        deactivate                              # close virtual environment once done

        
