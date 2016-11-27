This is a utility helps replacing words in docx file

Usage: go run Replace.go <source.docx> <target.docx> <originalWord> <newWord>
       e.g. go run replace.go ./sample.docx ./newfile.docx xyz abc\n")

docx is a compressed zip file, following Office Open XML specifcations. It contains various xml files. It follows ECMA-376 specfication. More details about ECMA are available here http://www.ecma-international.org/publications/standards/Ecma-376.htm

All important data for a docx file is present in word/document.xml. This utility looks through the document.xml for given words.

