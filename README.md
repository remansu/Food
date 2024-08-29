echo "# Assignment Submission" > README.md
echo "This repository includes the changes required by the assignment." >> README.md
echo "Changes made:" >> README.md
echo "- Created cabbage file in vegetables folder" >> README.md
echo "- Deleted apple file and created watermelon file in fruit folder" >> README.md
git add README.md
git commit -m "Added README file with details of the changes"
git push origin main
