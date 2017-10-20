xmms2-mpris2
============

This is a bridge for xmms2 to control it with the MPRIS2 standard.
This is the result of me (simpoir) being annoyed about everyone supporting
MPRIS2, the lack of MPRIS2 support in xmms2 and the spec having a couple
of mentions of xmms2 as examples. This is my one-night attempt at making thing
right.


Installation
============

.. code:: bash

  cp ./xmms2-mpris2 ~/.config/xmms2/startup.d/
  chmod +x ~/.config/xmms2/startup.d/xmms2-mpris2
  # then restart
  xmms2 server shutdown
  xmms2 list

You probably also want to install libxmmsclient (the c lib, not the python)
because it's using that. (worked out of the box with python3)


Bug
===

Yes and I don't really care.


Roadmap
=======

None.


Contributing
============

I'd rather prefer you spend your effort on something else. I won't maintain.
I may or may not look in my inbox once in a while for pull requests.
Notice how there are no tests and no documentation or comments…


References
==========

If you sumbled here for another reason, here are some references.
Note that the properties implementation is not great (slow), so if that's what
you were looking for, I suggest you look at it and learn how not to do it.

- https://doxygen.xmms2.org/clientlib/DrJekyll/xmmsclient/modules.html
- https://dbus.freedesktop.org/doc/dbus-python/doc/tutorial.html
- https://specifications.freedesktop.org/mpris-spec/latest/
- https://dbus.freedesktop.org/doc/dbus-specification.html#standard-interfaces-properties
