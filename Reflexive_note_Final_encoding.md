# Reflexive note_Final encoding project

# Understanding XML

These various assignments allowed me to understand both the technical and conceptual dimensions of TEI encoding. At the beginning of the course (Assigment 1), my understanding of TEI was mostly descriptive : I was it mainly as a way to "markup" texts using perdefined tags. The most difficult thing for me as I progressed was understanding its usefulness in the professional world. However, I found myself faced with a situation at my work-study placement where I had to encode a letter to facilitate an exhibition at the Museum. As part of my project, my main difficulty was understanding the logic behind TEI modules and element hierarchies, especially the difference between structural elements (such as **div**, **lg**, and **l**) and metadata elements in the header.

# Using of TEI

Working of ODD helped me realize that encoding is a form of interpretation. Choosing to restrict **div** to poems, **lg** to stanzas, and **l** tp poetic lines forced me to thik carefully about the structure of poetry and about the consistency of my data. 

# Difficulties encountered

I also struggled with Schematron constraints at first. My initial rules did not work as expected, but by simplifying the XPath expressions and testing them step by step, I managed to enforce stanza length constraints successfully. This last part was particularly difficult for me. Oxygen kept crashing and I really struggled to associate my RNG document with my 3 XML schemas. 
I wasn't able to achieve my goal. I managed to create a valid ODD document, from which I generated the HTML documents and the RNG file. It took me several weeks to find a solution to the validation problems with my XML documents. Especially regarding the <div> element; in the <l> tag, I wasn't clearly specifying the applicable parameters. I also struggled to properly create and reference my modules, so I could apply the child elements that reference them. That is why I had to delete my files and re-upload them to github; given the quality of the teaching received, I set myself the goal of having my files validated by my RNG.



