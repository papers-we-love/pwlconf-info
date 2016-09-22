# Claire Le Goues / Automatic Patch Generation

<img src="https://github.com/papers-we-love/pwlconf2016/blob/master/assets/ClaireLeGoues.png" align="right">

Research in automated program patching seeks to improve programs by, e.g., fixing bugs, porting functionality, or improving non-functional properties. The past eight years have seen a rapid expansion of techniques proposed and evaluated in this space.

In this talk I will discuss the progression of the area of automated bug repair in particular. I will especially focus on the key challenge of assuring, measuring, and reasoning about the quality of bug-fixing patches. Most such techniques, whether heuristic or semantic, rely on test cases to validate transformation correctness, in the absence of formal correctness specifications, but otherwise vary in the way they construct candidate patches and traverse the infinite space of possibilities. I will outline recent results on the relationship between test suite quality and origin and output quality, with observations about both semantic and heuristic approaches. I will conclude with a discussion of potentially promising future directions and open questions.

### Referenced Papers

- [Automatic Program Repair with Evolutionary Computation](https://www.cs.virginia.edu/~weimer/p/p109-weimer.pdf)
- [Angelix: scalable multiline program patch synthesis via symbolic analysis](https://www.comp.nus.edu.sg/~abhik/pdf/ICSE16-angelix.pdf)
- [Repairing Programs with Semantic Code Search](http://people.cs.umass.edu/~brun/pubs/pubs/Ke15ase.pdf)
