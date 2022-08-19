# RL_financ

# Setup and Baseline

## Tools(and basic tutorial):

1. Google Colab Pro (for enable terminal)

2. Github

Video : https://www.youtube.com/watch?v=RGOj5yH7evk

Docs : https://docs.github.com/en/get-started/quickstart/hello-world

3. VS Code




## Baseline
I upload a jupyter notebook on my [github](https://github.com/iamlilAJ/RL_finance/blob/main/RL_baseline.ipynb). It's a reproduction of [gym_anytrading](https://github.com/AminHP/gym-anytrading) and I will update it after I am famliar with the package.
And the new baeline using stable_baseline could be found in the project.
##### Clone and Run via

```console
git clone https://github.com/iamlilAJ/RL_finance.git
```

## For Teamwork on Github using Colab
Read this tutorial [colab](https://github.com/WassimBenzarti/colab-ssh)

##### (Optional) Using Colab in VS Code

Tutorial1 : https://colab.research.google.com/github/JayThibs/jacques-blog/blob/master/_notebooks/2021-09-27-connect-to-colab-from-local-vscode.ipynb#scrollTo=0AbYYRo5pa6W

PS : I am in China now （which restricts some software and websites so I have to use a more complecated method
to connect it. So I am not that sure this method works for you guys.





#####  Some example code

In Colab
```python


!pip install colab_ssh --upgrade
!git init
!git remote add origin https://<username>:<password>@github.com/iamlilAJ/RL_finance.git
from colab_ssh import launch_ssh_cloudflared, init_git_cloudflared
launch_ssh_cloudflared(password="password for ssh connection")

init_git_cloudflared('https://github.com/iamlilAJ/RL_finance')

# Connect to drive
from google.colab import drive
drive.mount('/content/gdrive/')
```

In Terminal
```console
git clone https://github.com/iamlilAJ/RL_finance.git
###After some change
git add .
git commit -m "message for commit"
git push
```
