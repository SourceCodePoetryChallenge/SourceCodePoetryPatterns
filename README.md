# Source code poetry patterns

## Pattern #1. Main Method
 
### Intent
Make your main method less boring by making boilerplate code rhyme. 

### Motivation / Problem Description
Most of Java applications need a boring entry point. This "entry point" is a static method that adheres to certain specific Java language conventions: i.e. it must be named "main", it has to accept certain type of parameters, return nothing etc.

![](https://static.wixstatic.com/media/2cf77c_7870a7a66d1e4f2a8fc7a3ba7e8fac32~mv2.png/v1/fill/w_740,h_308,al_c,usm_0.66_1.00_0.01/2cf77c_7870a7a66d1e4f2a8fc7a3ba7e8fac32~mv2.png)

Figure 1. A typical entry point of a typical Java application.


The Java language syntax enforces certain keywords that significantly restrain freedom of artistic expression.
However you yourself don't have to be that boring and restricted. 

### Implementation / Solution
The application's entry point can be written in a human-readable two-liner rhyme:

![](https://static.wixstatic.com/media/2cf77c_057f63793a3342cf8f9f422d94d0fad7~mv2.png/v1/fill/w_740,h_376,al_c,usm_0.66_1.00_0.01/2cf77c_057f63793a3342cf8f9f422d94d0fad7~mv2.png)
Figure 2. A main method that rhymes.



This two-liner is an instant dramatic improvement over the “standard” non-poetic code.
Obviously, the code above does need some extra code (a so called "boilerplate code") to actually work. 
In case you have sufficient degree of freedom in your project, you should be able to create necessary classes elsewhere in your application structure - or use a SourceCodePoetry.jar lib as a project dependency.
However it happens that team members are occasionally not that receptive to a poetic code. You would need to place all the boilerplate code within the same class, which makes entry point class somewhat less laconic as illustrated in a code below:

![](https://static.wixstatic.com/media/2cf77c_63886276c3d842d4a3596636c56adf26~mv2.png/v1/fill/w_637,h_852,al_c/2cf77c_63886276c3d842d4a3596636c56adf26~mv2.png)
Figure 3. Self-contained main class, rhymed entry point, and the boilerplate code.

### Consequences
The first committer of such code receives instant attention from peer reviews. 
An immediate feedback from your team may vary, depending on the individual level of poetic maturity of your team members. Some less-enlightened personalities are known to be rather melodramatic about the obviously improved code interestingness quality. 
This type of reaction helps you better experience the emotional state of world’s greatest artists like Vincent van Gogh or Paul Gauguin, who all faced severe adversity from their peers for being ahead of their time.
In either occasion, the emotional equilibrium of the project team gets an additional charge. 
From a scientific perspective, it has been empirically proven that Java programmers can be easily trained into a semi-automatic reaction, where a commonly used phrase “public static void main string” triggers an immediate sub-conscious response with “… is where new life shall begin”. 





