# ExampleStack
Analyzing and Supporting Adaptation of Online Code Examples (ICSE 2019)

## Summary of ExampleStack 
Developers often resort to online Q&A forums such as Stack Overflow (SO) for filling their programming needs. Although code examples on those forums are good starting points, they are often incomplete and inadequate for developers' local program contexts; adaptation of those examples is necessary to integrate them to production code. As a consequence, the process of adapting online code examples is done over and over again, by multiple developers independently. Our work extensively studies these adaptations and variations, serving as the basis for a tool that helps integrate these online code examples in a target context in an interactive manner.
We perform a large-scale empirical study about the nature and extent of adaptations and variations of SO snippets. We construct a comprehensive dataset linking SO posts to GitHub counterparts based on clone detection, time stamp analysis, and explicit URL references. We then qualitatively inspect 400 SO examples and their GitHub counterparts and develop a taxonomy of 24 adaptation types. Using this taxonomy, we build an automated adaptation analysis technique on top of GumTree to classify the entire dataset into these types. We build a Chrome extension called ExampleStack that automatically lifts an adaptation-aware template from each SO example and its GitHub counterparts to identify hot spots where most changes happen. A user study with sixteen programmers shows that seeing the commonalities and variations in similar GitHub counterparts increases their confidence about the given SO example, and helps them grasp a more comprehensive view about how to reuse the example differently and avoid common pitfalls.

## Team 
This project is developed by Professor [Miryung Kim](http://web.cs.ucla.edu/~miryung/)'s Software Engineering and Analysis Laboratory at UCLA. 
If you encounter any problems, please open an issue or feel free to contact us:

[Tianyi Zhang](https://https://tianyi-zhang.github.io): PhD student and now an assistant professor at Purdue; tianyi@purdue.edu

[Di Yang](https://isr.uci.edu/users/di-yang): PhD student at UC Irvine and now a software engineer at [Microsoft](https://www.linkedin.com/in/di-yang-uci/)  

[Crista Lopes](https://www.ics.uci.edu/~lopes/): Professor at UC Irvine; lopes@ics.uci.edu

[Miryung Kim](http://web.cs.ucla.edu/~miryung/): Professor at UCLA; miryung@cs.ucla.edu
## How to cite 
Please refer to our ICSE'19 paper, [Analyzing and supporting adaptation of online code examples
](http://web.cs.ucla.edu/~miryung/Publications/icse2019-examplestack.pdf) for more details. 

### Bibtex  
@inproceedings{10.1109/ICSE.2019.00046, author = {Zhang, Tianyi and Yang, Di and Lopes, Crista and Kim, Miryung}, title = {Analyzing and Supporting Adaptation of Online Code Examples}, year = {2019}, publisher = {IEEE Press}, url = {https://doi.org/10.1109/ICSE.2019.00046}, doi = {10.1109/ICSE.2019.00046}, booktitle = {Proceedings of the 41st International Conference on Software Engineering}, pages = {316–327}, numpages = {12}, keywords = {code adaptation, online code examples}, location = {Montreal, Quebec, Canada}, series = {ICSE '19} }

[DOI Link](https://dl.acm.org/doi/10.1109/ICSE.2019.00046)

## ICSE 2019 Artifact Evaluation Link.
This GitHub project [link](https://github.com/tianyi-zhang/ExampleStack-ICSE-Artifact) contains data sets and code for ICSE 2019 artifact evaluation. 

