# NJC
NCJ website repo - this repository contains the content for the website of the Journal Club.

To create the new blog post you need to:
1. have Hugo and rights to upload
2. clone this repository to your local storage
git clone https://github.com/neuroengineering/njc

3. create a submodule of njc-page as public folder
git submodule add https://github.com/neuroengineering/njc /public

3. create a submodule of kube theme in themes folder
cd themes/
git submodule add https://github.com/neuroengineering/kube 
 
4. update a new blog post in content/ folder (with style same as in other .md files)
5. check if everything works with: hugo server
6. run the page creation: hugo
7. upload all of the changes to each of the repositories
