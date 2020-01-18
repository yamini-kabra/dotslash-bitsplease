# dotslash-bitsplease

We propose a system for automated  currency recognition using image processing techniques. The
proposed method can be used for recognizing both the country or origin as well as the denomination or value of a given banknote.
Only paper currencies have been considered. This method works by first identifying the country of origin using certain predefined
areas of interest, and then extracting the denomination value using characteristics such as size, color, or text on the note,
depending on how much the notes within the same country differ.

We are Implementing "template matching" in order to identify whether the currency is Indian or not. Here the template that is being traced over the input image is the "4 headed lion emblem" that serves as a unique feature that differs the indian currency from the rest of the notes from other countries.
