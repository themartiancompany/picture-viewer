..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


===================
picture-viewer
===================

-------------------------------------
Cross-platform picture viewer
-------------------------------------
:Version: picture-viewer |version|
:Manual section: 1


Synopsis
========

picture-viewer *[options]* *file*


Description
===========

Powerful cross-platform picture viewer.

Works seamlessly on Android and GNU/Linux, both
in a KMS console and when a GUI is running.


Options
========

-t image_type           It can be 'raw' or 'text'
-p target_viewer        Use a specific viewer
                        ('cacaview', 'termux-open',
                        'xdg-open')

-h                      This message.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/picture-viewer/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* libcrash-bash
* cacaview
* termux-open
* xdg-open

.. include:: variables.rst
