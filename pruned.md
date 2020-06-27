This project is a pruned copy of https://github.com/jo-pol/GroundForge
keeping only what lead to the index on the bobbin lace sampler and book by Gertrude Whiting.

Many files moved a lot, so what to prune beyond the obvious was found
by trial and error while browsing through the remaining history.

It might not be the best approach according to https://git-scm.com/docs/git-filter-branch

    git filter-branch -f --tree-filter "rm -rf README.md build.sbt pom.xml project src toJS.bat toJS.sh 404.md API _config.yml docs/404.md docs/API docs/_config.yml docs/css docs/images docs/js docs/sheet.html docs/tiles.html docs/_includes/README.md docs/_includes/gallery.html docs/_includes/site-map.svg docs/_includes/stitches.html docs/help/A*.md docs/help/B*.md docs/help/C*.md docs/help/D*.md docs/help/F*.md docs/help/N*.md docs/help/P*.md docs/help/R*.md docs/help/S*.md docs/help/T*.md docs/help/Undo.md docs/help/animation docs/help/bloopers docs/help/footside.html docs/help/images docs/help/index.md docs/help/stitches docs/help/tl" --prune-empty HEAD 
    
    git filter-branch -f --tree-filter "rm -rf index.html *.js colorpicker *.png *.md target patterns images js debugD3js-v4 move-nodes docs/thumbs docs/*.html docs/D3jsForces thumbs css docs/README.md .travis.yml .github/PULL* .github/ISSUE* tl wiki* docs/animation bloopers docs/help/examples/tl docs/*.md docs/stitches stitches animation docs/help/Home.md help/examples/Tesse* docs/help/Para* help/examples/index.md help/examples/Droste* docs/help/Choose* docs/help/Thread* docs/help/Reshape* docs/help/examples/Droste* docs/_includes/stitch*  docs/_includes/tess* docs/help/*.png docs/help/*.gif " --prune-empty HEAD 
    
    git filter-branch -f --tree-filter "rm -rf *.html docs/help/examples/T*.md docs/help/examples/index.md docs/help/examples/stitch* docs/help/*NL* docs/help/M*.md" --prune-empty HEAD 
    
    git filter-branch -f --tree-filter "rm -rf docs/help/examples.md" --prune-empty HEAD 
    
    
