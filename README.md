# lexical_diversity
Keywords: lexical diversity MTLD HDD vocabulary type token python

The code in this repository contains implementations for two methods of scoring lexical diversity, MTLD and HD-D. Lexical diversity is a measure of how many different words are used in a text. MTLD and HD-D are necessary because Type-Token Ratio (Which is simply the number of different words, types, divided by the number of words, tokens) has an inverse relationship with sample size, introducing a bias when comparing texts of different lengths. MTLD and HD-D correct for this bias.

HD-D is an idealized version of voc-D. For more information see McCarthy, P.M. & Jarvis, S. (2007). vocd: A theoretical and empirical evaluation. Language Testing, 24(4), 459-488.

MTLD (Measure of Textual Lexical Diversity, or LDAT, Lexical Diversity Assessment Tool) is derived from the average length of continuous text units above a certain Type-Token Ratio. For more information see McCarthy, P. M., & Jarvis, S. (2010). MTLD, vocd-D, and HD-D: A validation study of sophisticated approaches to lexical diversity assessment. Behavior research methods, 42(2), 381-392.
