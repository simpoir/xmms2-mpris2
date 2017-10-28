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

You probably also want to install libxmmsclient (the c lib, not the python lib)
because it's using that. (the py lib is not packaged for python3)


Bug
===

Yes, and I don't really care.


Roadmap
=======

I plan to do exactly nothing more about this code. Hopefully, I'll stick to
that plan.


Contributing
============

I'd rather prefer you spend your effort on something else. I won't maintain.
I may or may not look in my inbox once in a while for pull requests.
Notice how there are no tests and no documentation or comments…
That was intentional.


References
==========

If you sumbled here for another reason, here are some references.

- https://doxygen.xmms2.org/clientlib/DrJekyll/xmmsclient/modules.html
- https://dbus.freedesktop.org/doc/dbus-python/doc/tutorial.html
- https://specifications.freedesktop.org/mpris-spec/latest/
- https://dbus.freedesktop.org/doc/dbus-specification.html#standard-interfaces-properties
