+++
date = '{{ .Date }}'
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
image = '{{ append .File.ContentBaseName ".png" }}'
myCustomVariable =  "default value" 
anotherVariable = 123
+++
