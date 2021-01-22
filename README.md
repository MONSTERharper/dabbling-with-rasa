![error](/images/rasa.png)

# dabbling-with-rasa
Rasa NLU
# creating a new environment
# yourname name of your environment and you can specify any version of python
conda create -n yourenv python=3.6 anaconda

# To activate this environment, use
#
#     $ conda activate rasa
#
# To deactivate an active environment, use
#
#     $ conda deactivate
conda activate rasa

# install rasa
pip install rasa
# if you getting error like ERROR: Cannot uninstall ‘ruamel-yaml’.
# Install using this 
pip install rasa --ignore-installed ruamel.yaml

# cls command to clear the screen in anaconda terminal
cls

# create a directory or go to the directory example
cd C:\Users\sarve\Downloads\Chatbot

# to install basic rasa framework
rasa init

# to select the directory to download the frame work, give "." for current directory
Please enter a path where the project will be created [default: current directory] .

# to train the rasa framework model, Press "y" or "n"
Do you want to train an initial model? 💪🏽  Yes
