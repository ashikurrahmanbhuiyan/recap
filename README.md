<h1>Assignment 0: Markdown</h1>
<h3>You have to write markdown</h2><hr>

<h3>Some Math Equation</h3>
<div align = "center">
     <p>First equation: <b>Y</b>=<b>X</b>β+ϵ<sub>y</sub>, ∀<b>X</b></p>
     <p>Second equation: <b>X</b>=<b>Z</b>γ+ε<sub>x</sub></p>
     <p>f<sub>1</sub>(ω)=σ<sup>2</sup>/2π, ω∈[−π,π]</p>
</div>
<ol type="1">
    <li>First item a. first sub-item A) first sub-sub-item b. second sub-item</li>
    <li>Second item</li>
    <li>Third item a. second sub item</li>
    <li>Fourth Item</li>
</ol>
<ul>
    <li>First Item</li>
    <li>Second Item</li>
    <ul>
        <li>first sub-item</li>
        <ul>
            <li>first sub-sub-item</li>
        </ul>
        <li>second sub-item</li>
    </ul>
</ul>
<img src="https://camo.githubusercontent.com/e6947af48fb1f3bb4f8238ee96f307dc6ddc9c9640c373484badd0cd42a3a25d/68747470733a2f2f69636f6e732e69636f6e617263686976652e636f6d2f69636f6e732f69636f6e6b612f6d656f772f3235362f6361742d636167652d69636f6e2e706e67" alt="">
<p>
    library(tidyverse)<br>
    library(mdsr)<br>
    SAT_2010 %>% ggplot(aes(write,..density..)) + geom_histogram() +<br>
    geom_density() + theme_minimal() + labs(title = "SAT Writing Scores")
</p>
<br>
<br>
<h1>Table with alignment</h1>

<p>You can align text in the columns to the left, right, or center by adding a colon (:) to the left,<br>
right, or on both side of the hyphens within the header row.</p>
    <table border="1">
        <tr>
            <th><b>Syntax</b></th>
            <th><b>Description</b></th>
            <th><b>Test Text</b></th>    
        </tr>
        <tr>
            <td>Header</td>
            <td>Title</td>
            <td>Here's this</td>
        </tr>
        <tr>
            <td>Paragraph</td>
            <td>Text</td>
            <td>And more</td>
        </tr>
    </table>
<h1>Instructions</h1>

<p>6.S191 software labs are designed to be completed at your own pace. At the end of each<br>
of the labs, there will be instructions on how you can submit your notebook for grade.<br>
Additionally, if you would like to submit your lab as part of the 6.S191 lab competitions,<br>
instructions regarding what information must be submitted is also provided at the end of<br>
each lab.</p>

<h1>License</h1>

<p>All code in this repository is copyright 2022 MIT 6.S191 Introduction to Deep Learning. All<br>
Rights Reserved.<br>
<br>
Licensed under the MIT License. You may not use this file except in compliance with the<br>
License. Use and/or modification of this code outside of 6.S191 must reference:</p>
<div style="border-left: 5px solid gray;height: 65px;">
    <div style="padding-left: 10px;"><p style="color:gray">© MIT 6.S191: Introduction to Deep Learning</p>
    <a href="http://introtodeeplearning.com">http://introtodeeplearning.com</a>
    </div></div>

