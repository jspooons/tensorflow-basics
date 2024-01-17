# tensorflow-basics
Repository created in aid of preparing for the tensorflow professional developer certificate

Setting up a virtual environment to install the `requirements.txt` file
1. Run `which python` to find where Python is installed
2. Run `virtualenv venv -p full_path_to_python`
3. Run `source venv/bin/activate` to activate the virtual environment
4. Run `pip install -r requirements.txt`

run `deactivate` to exit virtualenv

Cloning the repo and downloading the large datasets:
1. Run `brew install lfs`
2. Run `git lfs install` to initialize (or just run this command)
3. Open new terminal
4. Run `git clone <repository_url>`