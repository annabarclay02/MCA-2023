[Home](README.md) | [Week 1](week1.md) | [Week 2](week2.md) | [Week 3](week3.md) | [Week 4](week4.md) | [Week 5](week5.md) | [Week 7](week7.md) | [Week 8](week8.md) | [Week 9](week9.md) | [Week 10](week10.md) 

# Week 3: Encoding Basics for Notation
## Task 1
This week we had the task of converting our mcsz file into a MusicXML file, and then from a MusicXML file into an MEI file.
This was done using MuseScore and Verovio.

My MusicXML file is linked [here](data/mirrorball.musicxml).

My MEI file available for download [here](data/mirrorball.mei).

Below is my MEI file of Taylor Swift's song 'Mirrorball' from her eighth studio album *folklore*.

## My Score

{% include_relative verovio_inline.html %}

## Differences of MEI and MusicXML
MEI and MusicXML have a large variety of differences, especially in terms of their respective hierarchies. XML focusses on 'note' as the parent element and most other elements as the child elements. MEI, on the other hand, focusses on staffs and measures as the parent elements. This means that the organisation of each of the files is very different. Another difference between XML and MEI is the treatment of key and time signature: for XML these are defined as elements, but in MEI they are attributes instead so are thought of as extra information to the element its attatched to. Another difference is MEI's implementation of IDs to identify staves and attributes, this can help if measures are repeated or need identifying later on in the piece, for example the ID determines the start and stop of a slur in MEI whereas in MusicXML slurs are defined by a start and stop attribute. 

I personally found the MEI organisation much more useful when looking at the code and it made more sense to me in this layout. MusicXML is  much more focussed on the needs of musicians and composers and is a good platform for the importing of scores to different notation softwares, whereas MEI is better suited to encoding extra notation information and processing metadata. Overall MusicXML is more widely used by musicians, and MEI is preferred by academics.

---

[<-- Previous - Week 2](week2.md) ---------------------------------------------------------------------------------------------------------------------------------------------------- [Next - Week 4 -->](week4.md)
