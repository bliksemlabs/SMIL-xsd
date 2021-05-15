# SMIL 3.0 unofficial XSD

I still consider SMIL the best example of a near perfect data model which is described at such depth (read: complex) that it is virtually impossible to come up with solutions that implement the data model holistically.

Starting with my own playout software based on SMIL (read: open standards) I have noticed in the past years the availability "better" XSD model generators slowly start to appear beyond the scope of JAXB. xsData is a great example of such. The need for maintained schemas is therefore a requirement for a proper implementation.

Historically SMIL only has seen DTD and Relax-NG for validation purposes, but never an XSD. Conversion software between DTD and XSD has been available two decades ago and used for this effort. This repository contains a Trang converted DTD, with a manual change to place the "correct" namespace.


Regarding copyright, the original W3 copyright has been added to the repository. As per copyright mandate: [the original location of the material](https://www.w3.org/TR/REC-smil/smil-DTD.html)

Copyright © 2008 W3C® (MIT, ERCIM, Keio), All Rights Reserved. W3C liability, trademark and document use rules apply.
