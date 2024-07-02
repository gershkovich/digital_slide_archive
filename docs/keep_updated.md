# Add the upstream repository
git remote add upstream https://github.com/DigitalSlideArchive/digital_slide_archive.git

# Fetch the latest updates from upstream
git fetch upstream

# Checkout your master branch
git checkout master

# Merge updates into your master branch
git merge upstream/master

# Push updates to your fork
git push origin master
