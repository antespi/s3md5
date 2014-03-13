s3md5
=====

Bash script to calculate Etag/S3 MD5 sum for very big files uploaded using multipart S3 API



Description
===========

Calculates the Etag/S3 MD5 Sum of a file, using the same algorithm that S3 uses on multipart uploaded files.
Specially usefull on files bigger than 5GB uploaded using multipart S3 API. You can check file integrity
comparing S3 Etag with the value returns by 's3md5 file'



Usage
=====
```
Usage : $APP <size> <file>

- size : Multipart chunk size in MB
- file : Calculate Etag of this file
```


Example
=======

* Use 15 MB chunk size (as default in s3cmd .s3cfg config file)

    ~> s3md5 15 myfile.dat



LICENSE
=======

s3md5 is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the
Free Software Foundation, either version 3 of the License, or (at your
option) any later version.

s3md5 is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with s3md5. For license details you can read
[LICENSE](https://github.com/teachnova/s3md5/blob/master/LICENSE)
file. Also you can read GPLv3 from [GNU Licenses](http://www.gnu.org/licenses/).



AUTHOR
======

Copyright (C) 2013<br />
Antonio Espinosa<br />
Email    : aespinosa at teachnova dot com<br />
Twitter  : [@antespi](http://twitter.com/antespi)<br />
LinkedIn : [Antonio Espinosa](http://es.linkedin.com/in/antonioespinosa)<br />
Web      : [Teachnova](http://www.teachnova.com)
