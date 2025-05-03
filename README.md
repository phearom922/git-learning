//==========first Only config===========
1. git config --global user.name "phearom"
2. git config --global user.email "ronphearom2540@gmail.com"

3. git config --global -l // check error
4. git status
5. git init
6. git status
// ================ករណីមានការកែប្រែ files ត្រូវចាប់ផ្តើមពីចំនុចទី 7 ទៅ===============
7. git add . // add all files in projects
8. git commit -m "first commit" // Save all ករណីមានការបង្កើត file ថែមទៀចូលក្នុង Project របស់យើង
   git commit -a -m "first commit" // Save all ករណីមិនមានការបង្កើត file ថែមទៀចូលក្នុង Project របស់យើង តែមានការកែប្រែ File ណាមួយក្នុង Project របស់យើង
9. git log // show person save and modify projects // show one line use ==> git log --oneline

//============back to old version=============
git checkout <commit id>

//==========go to last version===============
git switch -


//==============first Upload to GitHub=============
1. git branch -M main
2. git remote add origin <តើយើងចង់ដាក់ចូលទៅក្នុង Repoo របស់យើងមួយណា Ex. git remote add origin https://github.com/phearom922/git-learning.git>
3. git push -u origin main // use this line first upload files to your github

//==============Second Upload to GitHub after modify ready =============
1. git commit -m "first commit" // Save all ករណីមានការបង្កើត file ថែមទៀចូលក្នុង Project របស់យើង
   git commit -a -m "first commit" // Save all ករណីមិនមានការបង្កើត file ថែមទៀចូលក្នុង Project របស់យើង តែមានការកែប្រែ File
2. git push