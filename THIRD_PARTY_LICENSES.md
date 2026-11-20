```markdown
# Third-Party Software Notices and Information

**Holmium File Explorer**

This software incorporates third-party components that are subject to their own copyright and license agreements. The following is a list of such components along with their respective copyright notices, license identifiers, and full license texts.

---

## 1. PySide2

- **Version:** 5.15.2.1
- **License:** LGPL-3.0-only (also available under GPL-2.0, GPL-3.0, and a commercial license)
- **Copyright:** Copyright (C) 2016-2020 The Qt Company Ltd.
- **Project URL:** [https://www.qt.io/qt-for-python](https://www.qt.io/qt-for-python)

### License Text (LGPL-3.0)

The full text of the GNU Lesser General Public License v3.0 is provided in the separate file [`LGPL-3.0.txt`](LGPL-3.0.txt) in the root of this repository. In accordance with the LGPL-3.0, you have the right to replace the PySide2 libraries used by this software with compatible versions.

> **Note:** PySide2 also incorporates some components under other licenses (e.g., BSD-3-Clause for certain examples and documentation files). For a complete list, please refer to the official PySide2 source repository.

---

## 2. psutil

- **Version:** 5.9.8
- **License:** BSD-3-Clause
- **Copyright:** Copyright (c) 2009, Jay Loden, Dave Daeschler, Giampaolo Rodola. All rights reserved.
- **Project URL:** [https://github.com/giampaolo/psutil](https://github.com/giampaolo/psutil)

### License Text (BSD-3-Clause)

```text
BSD 3-Clause License

Copyright (c) 2009, Jay Loden, Dave Daeschler, Giampaolo Rodola
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of the psutil authors nor the names of its contributors
  may be used to endorse or promote products derived from this software
  without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

---

3. Send2Trash

· Version: 1.8.3
· License: BSD-3-Clause
· Copyright: Copyright (c) 2017, Virgil Dupras. All rights reserved.
· Project URL: https://github.com/arsenetar/send2trash

License Text (BSD-3-Clause)

```text
Copyright (c) 2017, Virgil Dupras
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of Hardcoded Software Inc. nor the names of its
  contributors may be used to endorse or promote products derived from this
  software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

---

4. screeninfo

· Version: 0.8.1
· License: MIT
· Copyright: Copyright (c) 2015, Marcin Kurczewski
· Project URL: https://github.com/rr-/screeninfo

License Text (MIT)

```text
MIT License

Copyright (c) 2015 Marcin Kurczewski

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

5. rarfile

· Version: 4.x
· License: ISC
· Copyright: Copyright (c) 2005-2024 Marko Kreen
· Project URL: https://github.com/markokr/rarfile

Purpose in this project

Used to read RAR archives. rarfile is a pure-Python wrapper that invokes the bundled UnRAR.exe binary (see section 6) for actual decompression.

License Text (ISC)

```text
Copyright (c) 2005-2024 Marko Kreen

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY
SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR
IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

---

6. UnRAR

· Version: bundled binary, bin/UnRAR.exe (from RARLAB)
· License: UnRAR freeware license (custom, see text below)
· Copyright: Copyright (C) Alexander Roshal
· Project URL: https://www.rarlab.com/rar_add.htm

Purpose in this project

UnRAR.exe is bundled as a command-line helper and is invoked by rarfile to decompress RAR archives. It is not used to create RAR archives, and the RAR compression algorithm is not reimplemented in this software.

License Text (UnRAR)

```text
UnRAR is a freeware. You can use it freely for any legal purposes.
The UnRAR sources may be used in any software to handle RAR archives
without limitations free of charge, but cannot be used to re-create
the RAR compression algorithm, which is proprietary. Distribution of
modified UnRAR sources in separate form or as a part of other software
is permitted, provided that it is clearly stated in the documentation
and source that the UnRAR sources may be used only for RAR decompression.

This software is provided "as is", without warranty of any kind, either
express or implied, including but not limited to the warranties of
merchantability, fitness for a particular purpose and noninfringement.
In no event shall the authors or copyright holders be liable for any
claim, damages or other liability, whether in an action of contract,
tort or otherwise, arising from, out of or in connection with the
software or the use or other dealings in the software.

The full and current text of the UnRAR license is available at:
https://www.rarlab.com/license.htm
```

---

7. Python Standard Library modules (no separate license required)

This software uses the following modules from the Python Standard Library:

· zipfile — ZIP archive handling
· tarfile — TAR, TAR.GZ, TAR.BZ2, TAR.XZ archive handling
· shutil, os, pathlib, subprocess, json, threading, etc.

These modules are distributed as part of the Python interpreter itself and are covered by the Python Software Foundation License (PSF-2.0), not by a separate component license. Full text: https://docs.python.org/3/license.html

Note: If this software is distributed as a frozen bundle (e.g., built with PyInstaller), the Python interpreter itself is included in the distribution. In that case, the PSF License applies to the bundled interpreter. The notice above is retained for completeness.

---

This file is provided for informational purposes only and does not modify the terms of the EULA or the LGPL-3.0.

```