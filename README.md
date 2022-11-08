# yeu cầu chuc nang
- min 2 page
- Reponse mobile, table, laptop, pc
- Click Page to => diff page
  
# Ki thuat
- css: Scss
- Class Name: BEM
- Font Google: font
- Icon: Fontawesome
- Github Page
- Bootstrap 5.2
- Flex or Grid
- Min 1 Animation, 1 Effect Image Menu
  # Time Line
- 07/11/2022: 80% Reveview Part 1
- 09/11/2022: 100% Review Part 2 and UpGrade
- 11/11/2022: Thi va Thuyet trinh Project:  10phut
- 14/11/2022: Tong ket 

# struct
- index.html
- README.md
- assets
  - css
  - scss
    - partials
      - _variables.scss
      - _mixins.scss
      - _font.scss
      - _animation.scss
    - style.scss
    - main.scss
    - <diffpage>.scss
  - images
    - icons
    - uploads
      - products
      - users
  - js
- pages
  - detail.html
  - contact.html
  - about.html
  - product.html

# command git 
- create local repository
```bash
git init
```

- Link local repository with Remote repose
```bash
git remote add origin <linkremote> 
# git remote add origin https://github.com/huysynf/HTML_CSS_Template_lab.git
```

- add file
```bash
#  Add all file
git add .

# add file change 
git add -u

#  add a file

git add <file>
#  git add index.html
```

- commit 
```bash
git commit -m "message" 
```
- checkout 
```bash
git checkout -b main 
```
- push main
```bash
git push origin main 
```
# set up link compiler scss
- Files => preferences => settings => Extentions => Live sass compiler => settings: fomat=> edit in setting.json => edit savepath