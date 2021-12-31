
for .S

npm install -g vsce

vsce package && vsce unpublish -f && vsce publish
