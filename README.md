# Text Generator application 
This is a NLP(Natural Language Processing) project which is implemented using RNN(Recurrent Neural Network) deep learning model. Also instead of standard RNN GRU(Gated Recurrent Unit) is used. 
For project orchestration ML Flow is beign utilized.
## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository
```bash
git clone <repository_url>
``` 

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.7 -y
```

```bash
conda activate ./env
```
#### Alternate command to activate environment 
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05 - Create conda.yaml file -
```bash
conda env export > conda.yaml
```

### STEP 06- commit and push the changes to the remote repository (execute below commands only once to push changes first time)
```bash
git add .
git status
git commit -m "commit message"
git remote add origin 'your_repository_url'
git branch -m master main
git push -u origin main
```

#### After first commit for subsequent changes just execute below commands
```bash
git add .
git commit -m "commit message"
git push
``` 
