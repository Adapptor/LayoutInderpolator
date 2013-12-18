Layout Inderpolator
============================

The goal of this project is to provide a simple way to add a little bit of flavour animation to
what would otherwise be rather bland screens as part of a mobile app intro sections. It is inspired
by the end result of using the [Jazz Hands][1] library for iOS, but is not a port of functionality.


Integrating With A Project
============================
See provided sample.

TODO: Provide instructions for gradle integration

TODO: Provide .jar builds

Use
============================
InderpolatorView is a view group that presents each child one at a time. The user can scroll
between these pages, or advance using other means such as a button if desired. The views can be
added programatically or in xml as in the sample.

Interpolation is based on view ids. If a view id is only present in one page of a transition, it
will simply fade and animate off the screen. If a view id is present on both pages in the same
position, they will fade between the two, remaining stationary. If they are not in the same
position, the latter view takes precedence and will animate in from the size and shape of the, now
hidden, former view. The purpose of these is to make the two views represent the same object, but
in the sample they are coloured differently for clarity.


Sample Application
============================

TODO: Provide sample app build

 [1]: https://github.com/IFTTT/JazzHands