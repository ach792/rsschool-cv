# Andrei Chuyanov

## Contact Information

* e-mail: <achuyanov@gmail.com>
* GitHub : achuyanov, ach792
* mobile: +375297540133

## Self-Introduction

* I want to update my knowledge and gain skills in new technologies

## Skills

* Windows, Linux, MacOS, FreeBSD
* SVN, Git
* HTML/CSS/JS
* NodeJS
* base knowledge C++/C#, Python, Dart(Flutter), VB
* SQL, CMS systems

## Code Example

```JavaScript
function (files = [], zipFilename) {
  const
    fs = require('fs'),
    JSZip = require('jszip'),
    zip = new JSZip();

  for (let file of files) {
    zip.file(file.fileName, fs.readFileSync(file.fullFilePath));
  }

  const outputzip = R.getOutputFile(zipFilename);

  zip.generateAsync({ type: "nodebuffer" })
     .then(function (blob) { fs.writeFileSync(outputzip, blob); })
}
```

## Work Experience

* Engineering automation projects ~ 10 years.

## Education

* Belarusian National Technical University \  Mechanical Engineering Department 2003
* Codecademy courses : Introduction to HTML, Learn CSS, Introduction to JavaScript
* RSSchool courses : JS/FE19, RS IOS, RS NodeJS

## English Language

* English - B2
* Polish - A2
