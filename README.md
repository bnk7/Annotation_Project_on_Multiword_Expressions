# Annotation of Multiword Expressions
Brynna Kilcline, Gabby Masini, Ruth Rosenblum, and Annika Sparrell

Our goal is to identify and categorize all multiword expressions
(MWEs) in our data. The annotated data will become
training data for an ML model that will be able to
identify different types of multiword expressions in text,
which could be useful for downstream tasks such as machine
translation, translation detection, synonym detection,
and syntactic parsing.

The annotation task comprises finding multiword expressions
and labeling their type, which we frame as spans. We
define a multiword expression as a string of multiple words
which act as a single semantic or syntactic element.
