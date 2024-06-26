# nbstripout config


which nbstripout

git config filter.nbstripout.clean '.venv/bin/nbstripout'
git config filter.nbstripout.smudge cat
git config filter.nbstripout.required true
git config diff.ipynb.textconv '.venv/bin/nbstripout -t'