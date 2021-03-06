Facebook Puzzle Submitter
=========================

This project contains a user-friendly Python script for submitting puzzle
solutions to the [Facebook PuzzleBot](http://www.facebook.com/careers/puzzles.php).

Features
--------

Features of the script include--

* CC'ing puzzle submissions to the sender
* a "test mode" for sending submissions to a test e-mail address
* tarring and gzipping a directory
* automatic puzzle name detection and validation
* allowing the inclusion of a descriptive note in the e-mail body

Usage
-----

This script is especially useful for submitting solutions from a gmail
account, as the Facebook PuzzleBot is/was unable to read e-mail attachments
attached using gmail's GUI.  The script author has only tried this script
using gmail's SMTP servers at smtp.gmail.com.

For help documentation, execute this script with the -h or --help option.

    fbsubmit -h

Comments and suggestions are welcome.

Chris Jerdonek

Copyright
---------

Copyright (C) 2010 - 2011 Chris Jerdonek. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice,
  this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.
* The names of the copyright holders may not be used to endorse or promote
  products derived from this software without specific prior written
  permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
