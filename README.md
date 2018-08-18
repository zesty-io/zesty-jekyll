# Jekyll-Zesty

## Getting Started

1. [Installing Jekyll](#Installing-Jekyll)
2. [Creating your hugo project](#creating-your-hugo-project)
2. [Installing Hugo-Zesty](#Installing-Hugo-Zesty)
3. [Usage](#usage)

### Installing Jekyll

	gem install bundler jekyll

[See the Jekyll Website For More Help](https://jekyllrb.com/docs/installation/)


### Installing Jekyll-Zesty

#### Get Node.js with NPM First
**macOS**
	
	brew install node
	
**debian / ubuntu**

	curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
	sudo apt-get install -y nodejs
	
**other platforms**

[See the Node.js website](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions)

#### Clone the repository
	git clone https://github.com/ronakdev/jekyll-zesty/
	cd jekyll-zesty
	npm install

### Usage

#### Edit the `zesty.yaml` file in the jekyll-zesty folder
	vim zesty.yaml # or nano / vi / emacs
	

#### Commands

- `npm start` # rebuilds data from zesty.io and runs a hugo server
- `npm run-script build-jekyll` # rebuilds data from zesty.io and runs hugo to build a folder in `docs/`
- `npm run-script all` # rebuilds data from zesty.io, runs hugo to build a folder in `docs/`, and runs a hugo server
