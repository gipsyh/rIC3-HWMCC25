# rIC3-HWMCC25 
rIC3 model checker for Hardware Model Checking Competition 2025([HWMCC'25](https://hwmcc.github.io/2025)) submission.

rIC3 participates in the bit-level safety track and the word-level safety without arrays track.

rIC3 can also produce unsat certificates for btor2. If the `certificate.unsat` is not provided, only certificates.sat will be generated.

```
rIC3 <aig/btor2> [certificate.sat] [certificate.unsat]
```

Please do not use these operators (saddo, sdivo, smulo, ssubo, uaddo, umulo, usubo), because btorsim does not support them.

# Authors
Yuheng Su, gipsyh.icu@gmail.com

University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences

Tianjun Bu, butianjun24@mails.ucas.ac.cn

University of Chinese Academy of Sciences; Institute of Software, Chinese Academy of Sciences
 
Qiusong Yang, qiusong@iscas.ac.cn

Institute of Software, Chinese Academy of Sciences

Yiwei Ci, yiwei@iscas.ac.cn

Institute of Software, Chinese Academy of Sciences