# ttest_paired_app

##### Description

The T-test paired app determines if there is a significant difference between the means of two groups of paired samples. It performs Student's t-test on the data.

##### Details
The input data should be log or VSN transformed.

The workflow has 2 operators:

* [t_test_operator](https://github.com/tercen/t_test_operator)
* [scale_operator](https://github.com/tercen/scale_operator)

T_test operator settings:
* detailed = True
* var.equal = True
* paired = True
* reference index = 2 --> the group with starting letter earlier in the alphabet will be the reference / control group.

Views:

* Volcano plot
* Significant treatment effects

